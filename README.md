# Audio Visual Speech Enhancement System

> Isolating and clarifying speech for hearing aid users and deaf individuals in multi-speaker environments — through the fusion of sound and sight.

---

## Overview

Understanding speech when multiple people talk at once is one of the hardest perceptual challenges — even for those with full hearing. For individuals who rely on hearing aids or visual cues to communicate, it can be overwhelming.

This system addresses that problem by combining audio and video signals to isolate a target speaker's voice, suppress overlapping speech and noise, and deliver the result in a form suited to each user's needs — cleaner audio for hearing aid users, or text and visual feedback for deaf users.

---

## How It Works

The system operates in three stages:

**1. Input Capture**  
A microphone captures the raw audio stream while a camera records the target speaker's face — specifically lip movements and facial dynamics.

**2. Audio-Visual Fusion**  
Visual features extracted from lip motion are fused with audio features to build a joint representation of the target speaker. This multimodal signal serves as a strong anchor when separating the speaker from a noisy, multi-speaker mixture.

**3. Output Delivery**  
- Hearing aid users receive an enhanced, noise-suppressed audio stream  
- Deaf users receive synchronized visual feedback and/or real-time transcription

---

## Key Features

- Real-time multi-speaker separation using audio-visual cues  
- Lip-reading-informed speech enhancement  
- Dual output modes — audio and text/visual  
- Designed for challenging real-world settings: meetings, classrooms, social gatherings  
- Accessible-first architecture — built for users with hearing challenges

---

## Target Users

| User Group | Primary Output |
|---|---|
| Hearing aid users | Enhanced, denoised audio stream |
| Deaf individuals | Real-time captions and visual feedback |
| Researchers / Developers | Modular pipeline for AV speech processing |

---

## Architecture

```
Input
├── Microphone  ──────────────────────────────┐
│                                             ▼
│                                    Audio-Visual Fusion
│                                             │
└── Camera (Lip / Face Tracking)  ───────────┘
                                              │
                                              ▼
                                    Speaker Separation
                                              │
                              ┌───────────────┴──────────────┐
                              ▼                              ▼
                     Enhanced Audio                  Text / Visual
                   (Hearing Aid Users)              (Deaf Users)
```

---

## Technology Stack

> To be updated as the stack is finalized.

- **Audio Processing** — to be defined  
- **Visual Processing / Lip Detection** — to be defined  
- **Speech Enhancement Model** — to be defined  
- **ASR / Transcription** — to be defined  
- **Interface / Output Layer** — to be defined

---

## Getting Started

> Setup instructions will be added as the project develops.

```bash
# Clone the repository
https://github.com/Akashj-aj/Cocktail-party.git
cd Cocktail-party

# Install dependencies
# (instructions coming soon)
```

---

## Project Status

This project is currently in early development. Contributions, feedback, and collaboration are welcome.

---

## Motivation

Communication is a fundamental human right. For the roughly 1.5 billion people worldwide living with some degree of hearing loss, participating in everyday conversations — especially in noisy environments — requires significant effort and often leads to exclusion.

This project exists to reduce that barrier through technology that is both intelligent and empathetic.

---

## License

To be decided.

---


*Built with the belief that accessibility and technical ambition are not in conflict — they are the same goal.*
