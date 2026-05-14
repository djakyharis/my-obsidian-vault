---
date: 2026-05-14
status: evergreen
---

# 🏷️ Tag Taxonomy

This note defines all tags used in this vault. Always pick from this list — don't freestyle new tags.

---

## Status Tags
These go in the YAML frontmatter `status:` field of every note.

| Tag | Meaning |
|---|---|
| `seed` | Just captured, raw and unprocessed |
| `growing` | Actively being developed and expanded |
| `evergreen` | Complete, stable, and polished |

---

## Topic Tags
These go in the YAML frontmatter `tags:` field.

### Computer Science
| Tag | Use For |
|---|---|
| `computer-science` | General CS theory, concepts |
| `algorithm` | Algorithm notes |
| `c-language` | C programming notes |
| `javascript` | JavaScript notes |
| `database` | SQL, MySQL, database concepts |

### AI & Data
| Tag | Use For |
|---|---|
| `artificial-intelligence` | General AI concepts and workflows |
| `machine-learning` | ML models, training, data |
| `data` | Data types, datasets, data infrastructure |

### Engineering & Systems
| Tag | Use For |
|---|---|
| `embedded-systems` | Arduino, ESP32, microcontrollers |
| `biomedical` | Biosignals, ECG, PPG, HRV |
| `cloud-computing` | Cloud, distributed systems, security |
| `cyber-physical-system` | CPS course notes |

### Personal
| Tag | Use For |
|---|---|
| `personal` | Personal interest, not academic |
| `gaming` | Gaming-related notes (e.g. Lossless Scaling) |
| `course` | Notes tied to a specific university course |

---

## How to Use

### In YAML frontmatter (Main Notes & Source Material):
```yaml
---
date: 2026-05-14 21:00
status: growing
tags: [machine-learning, artificial-intelligence]
source: Dicoding - Belajar Dasar AI
---
```

### In Rough Notes frontmatter:
```yaml
---
date: 2026-05-14 21:00
status: seed
promote-to: 5 - Main Notes/AI/Data untuk AI.md
---
```

---

## References
- Internal vault standard
