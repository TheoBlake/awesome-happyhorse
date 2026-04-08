# Awesome HappyHorse-1.0 🎠

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

| [English](./README.md) | [简体中文](./README-zh.md) | [Deutsch](./README-de.md) | [Francais](./README-fr.md) | [Espanol](./README-es.md) | [日本語](./README-ja.md) |

> A curated collection of prompts, benchmark notes, and generation examples for **HappyHorse-1.0**.

This repository tracks reproducible prompt cases for HappyHorse-1.0.  
It starts with publicly available Arena examples and will expand as more official details are released.

---

## 📖 Table of Contents

1. [What We Know So Far](#1-what-we-know-so-far)
2. [Example Prompts with Local Videos](#2-example-prompts-with-local-videos)
3. [Benchmark Recording Template](#3-benchmark-recording-template)
4. [Contributing](#4-contributing)
5. [Roadmap](#5-roadmap)
6. [Disclaimer](#6-disclaimer)

---

## 1. What We Know So Far

Based on the public post by Artificial Analysis (2026-04-08):

> We’ve added a new pseudonymous video model to our Text to Video and Image to Video Arenas.  
> ‘HappyHorse-1.0’ is currently landing in the #1 spot for Text and Image to Video (No Audio) and the #2 spot for Text and Image to Video (With Audio).  
> Further details coming soon.

### Confirmed signals

- **#1** in Text/Image to Video (**No Audio**)
- **#2** in Text/Image to Video (**With Audio**)
- Public examples were compared against:
  - Dreamina Seedance 2.0
  - Kling 3.0 Pro
  - grok-video-imagine
  - PixVerse V6

---

## 2. Example Prompts with Local Videos

### 2.1 Prompt [1/4] - Hula Hoop Motion Control

**Prompt:**

```text
A hula hoop spinning on a kid's waist, gradually climbing to their chest, then dropping to knees, then ...
```

**Local video:** [./videos/prompt-1-hula-hoop.mp4](./videos/prompt-1-hula-hoop.mp4)

**Checkpoints:**
- Long-range motion continuity (waist -> chest -> knees)
- Trajectory stability of the hoop
- Body-prop interaction quality

### 2.2 Prompt [2/4] - Golf Ball Rim Count + Audio

**Prompt:**

```text
A golf ball in a cup rolling around the rim three times before finally dropping in. The golfer's body language matches each rotation. Audio: Ball rattle, exhale, plop.
```

**Local video:** [./videos/prompt-2-golf-ball.mp4](./videos/prompt-2-golf-ball.mp4)

**Checkpoints:**
- Exact action counting (exactly 3 rotations)
- Small-object physics precision
- Audio-to-action timing alignment

### 2.3 Prompt [3/4] - Reflection Behavior + Audio

**Prompt:**

```text
A cat staring at its own reflection in a toaster, paw tapping the chrome surface. The distorted cat reflection taps back. Audio: Paw taps, confused meow.
```

**Local video:** [./videos/prompt-3-cat-toaster.mp4](./videos/prompt-3-cat-toaster.mp4)

**Checkpoints:**
- Metallic reflection realism and distortion behavior
- Interaction timing between real subject and reflection
- Sync quality of taps and meow

### 2.4 Prompt [4/4] - Latte Art Fluid Dynamics + Audio

**Prompt:**

```text
A barista creating latte art by pouring steamed milk into espresso. The white milk submerges beneath the brown crema initially, then breaks through the surface as the cup fills. The barista's wrist makes precise oscillating movements, creating a rosetta pattern. The milk and espresso maintain their distinct colors while interacting at the boundary. Audio: The gentle pour of liquid, the hiss of the steam wand in the background.
```

**Local video:** [./videos/prompt-4-latte-art.mp4](./videos/prompt-4-latte-art.mp4)

**Checkpoints:**
- Fluid boundary preservation (milk vs crema)
- Fine-grained wrist micro-motion fidelity
- Audio ambiance consistency

---

## 3. Benchmark Recording Template

Use this template when adding new results:

1. **Model/Version**: `HappyHorse-1.0`
2. **Mode**: `T2V` or `I2V`
3. **Audio setting**: `with-audio` / `no-audio`
4. **Prompt**: original or edited
5. **Generation settings**: duration, resolution, seed (if available)
6. **Observations**: motion control, physical realism, style stability
7. **Failure cases**: counting errors, geometry breaks, desync issues

---

## 4. Contributing

Contributions are welcome.

Please include:
- Prompt text
- Mode (`T2V`/`I2V`) and audio setting
- Generation settings (if public)
- Output file/link
- Your concise analysis (strengths + failure points)

---

## 5. Roadmap

- [ ] Add category pages under `prompts/`
- [ ] Add scorecards for consistency/physics/audio alignment
- [ ] Add side-by-side comparisons with baseline models
- [ ] Add official docs and platform links when available

---

## 6. Disclaimer

- This is a community-curated repository, not an official model source.
- Current information is limited and will be updated as new details are published.

