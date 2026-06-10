---
date: 2025-11-04 07:55
status: evergreen
tags: [personal, gaming, machine-learning]
source: Lossless Scaling Discord
---

# Lossless Scaling Basics

Developed by THS, this tool provides both spatial upscaling (increasing image quality when running at lower resolutions) and temporal scaling (frame generation to increase perceived smoothness).

## Model
- **LSFG (Lossless Scaling Frame Generation)**: Uses fixed multipliers (2x or 3x) to double or triple your perceived frame rate
- **AFG (Adaptive Frame Generation)**: Dynamically adjusts the frame generation to maintain a targeted frame rate (deprecated)

## Scaling Options
- **LS1**: A proprietary machine learning-based algorithm with good detail preservation
- **AMD FSR 1.0**: Implementation of AMD's open-source upscaler, balanced for quality and performance
- **NVIDIA Image Scaling (NIS)**: NVIDIA's spatial upscaling algorithm
- **Integer Scaling**: Perfect for pixel art games, preserving sharp pixel edges
- **xBR**: Specialized algorithms for smoother pixel art upscaling
- **Anime4K**: Optimized for anime and cartoon-style content
- **Bicubic CAS**: Combines bicubic interpolation with AMD's Contrast Adaptive Sharpening

## How to Use Scaler
The scalers present in LS require Borderless Fullscreen and Windowed Mode to work. To upscale games in Borderless Fullscreen, the **Scaling Mode** needs to be set to Custom with **Resize before scaling** enabled. This requires the use of a manual scaling factor where at 4k for example: a factor of 1.2/1.5/2.0 would result in an upscale of 1800p/1440p/1080p to 4k respectively. The Status Tab at the very bottom also displays the resized -> output resolution.

## General Usage Priority & Compute Cost

```
LS1 > SGSR/BCAS > FSR > NIS > xBR
```

The general order above represents how good each of the scalers are likely to look in any given 3D/2D game. The final image quality of the scaler vary depending on the game and content. All the upscalers in LS work best with ingame Anti-Aliasing (TAA, FXAA, MSAA) enabled.

The scalers within LS can also be used at native resolution alongside in-game TAA upscalers (DLSS/FSR2/XeSS). This can help with soft/poor in-game TAA implementations, where the LS scaler can improve edge resolve.

## Use Case & Tendency

- **LS1** — Recommended for games/videos with good motion handling. Sharpness values of 0 and 1 preferred to minimise aliasing. Can effectively reduce both occlusion artifacts and motion smearing. Generally performs the best for complex 3D scenes, foliage, particles, and reflections.

- **SGSR1** — Light, good image quality. Often superior to Bicubic CAS. Looks good with 2D pixel art and 3D games. Uses a 12-tap Lanczos-like scaling filter and adaptive sharpening. Can struggle with colour banding from very low internal resolutions.

- **BCAS** — Combines Bicubic upscaling with CAS. Well suited for pixel art and softer art styles, very low performance overhead. Can have difficulty with texture blending & gradient handling.

- **FSR** — AMD's spatial upscaler. FSR1.1 works well with most content and has low compute overhead. Sharpness values of 3-5 look best. Can look more pixelated and smeary in fast motion around bright foliage.

- **NIS** — Generally not preferred due to aggressive sharpening. Has general issues with edge contrast, leading to haloing and a dithered look in motion. Avoid if possible.

- **xBR** — Semi-popular pixel art/retro game upscaler. Performs diagonal smoothing very aggressively. A mostly artistic shader — generally ruins the intended look of older games.

- **Anime4K** — Strictly intended for 1080p sources upscaled to 4k. Does not work well with low bitrate/resolution sources. Can be very computationally heavy with Very Large/Ultra Large models.

## My System Specs
- **Device**: DESKTOP-HTS7PDK
- **CPU**: 12th Gen Intel Core i9-12900H @ 2.50 GHz
- **RAM**: 16.0 GB (15.7 GB usable)
- **Storage**: 954 GB SSD NVMe Micron_2450_MTFDKBK1T0TFK
- **GPU**: Intel Iris Xe Graphics (128 MB), NVIDIA RTX3050Ti
- **OS**: 64-bit, x64-based

## Tips
- **Stable Frame Rate**: Lock your base frame rate using in-game options or RTSS before enabling frame generation
- **GPU Headroom**: Aim for 70-80% GPU utilization before enabling frame generation
- **Disable Interfering Overlays**: Turn off Steam, Discord overlays if you have issues

## Related
- 

## References
- Lossless Scaling Discord
