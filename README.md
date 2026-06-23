# Loo Zong Poh — Portfolio

Personal portfolio website for Loo Zong Poh, a computer engineer specialising in machine learning, reinforcement learning, and computer vision.

## Overview

A single-page portfolio built with plain HTML and CSS — no frameworks, no build step. It features:

- **Hero** — brief introduction and call-to-action links
- **About** — background, approach, and skill chips
- **Featured Project** — Project ML Racing (Unity + PPO RL agent)
- **Earlier Work** — internship work at PTV Group (embedded YouTube clips)
- **Contact** — email, LinkedIn, and GitHub links

## Project ML Racing

A Unity-based racing environment connected to a PPO reinforcement learning agent that learns to drive using computer vision and vehicle telemetry. Key areas explored:

- Canny edge detection for lane detection
- CNN-based lane detection with MobileNet
- Unity-to-Python integration for camera & telemetry
- PPO reinforcement learning & reward shaping

## Running locally

No build step required — just open `index.html` in a browser:

```bash
# macOS / Linux
open index.html

# Windows
start index.html
```

Or serve it with any static file server:

```bash
npx serve .
# or
python -m http.server
```

## Structure

```
ZongPoh/
└── index.html   # entire site — styles, markup, and a one-liner script
```
