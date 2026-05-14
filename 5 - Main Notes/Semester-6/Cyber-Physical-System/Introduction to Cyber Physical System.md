---
date: 2026-02-15 17:27
status: growing
tags: [cyber-physical-system, course]
source: Kuliah Cyber Physical System - Semester 6
---

# Introduction to Cyber Physical System

## What is a Cyber Physical System (CPS)?
A **Cyber Physical System** is an integration of **computation**, **networking**, and **physical processes**. Embedded computers and networks monitor and control physical processes, with feedback loops where physical processes affect computations and vice versa.

> Simply put: CPS = Cyber (computation/software) + Physical (real-world processes) working together in a feedback loop.

## Key Characteristics
- **Real-time** — must respond to physical events within strict time constraints
- **Embedded** — computation is built into the physical system, not separate
- **Networked** — components communicate through wired or wireless networks
- **Safety-critical** — failures can have physical, life-threatening consequences
- **Feedback loops** — physical state informs computation, computation controls physical state

## Core Components
| Component | Role |
|---|---|
| **Sensors** | Read physical signals (temperature, pressure, motion, etc.) |
| **Actuators** | Exert physical effect (motors, valves, displays) |
| **Embedded Processors** | Compute and make decisions |
| **Communication Network** | Connect all components |
| **Physical Plant** | The real-world system being controlled |

## Examples of CPS
- **Medical devices** — pacemakers, insulin pumps, patient monitoring systems
- **Autonomous vehicles** — sensor fusion + real-time control
- **Smart grids** — power distribution with dynamic load balancing
- **Industrial automation** — manufacturing robots, SCADA systems
- **Smart buildings** — HVAC, fire systems, access control

## CPS vs. IoT vs. Embedded Systems
| | Embedded | IoT | CPS |
|---|---|---|---|
| Connectivity | Optional | Required | Required |
| Physical feedback loop | Possible | Rare | Core requirement |
| Real-time control | Often | Rarely | Always |
| Safety-critical | Sometimes | Rarely | Often |

## Topics to Cover This Semester
- [ ] Modeling physical systems
- [ ] Sensing & actuation
- [ ] Real-time scheduling
- [ ] Network protocols for CPS
- [ ] Fault tolerance in CPS
- [ ] Security in CPS

## 🔗 Related
- [[Biosignal, Sinyal Bioelectric, Biopotensial]]
- [[Semester-6 MOC]]

## References
- 
