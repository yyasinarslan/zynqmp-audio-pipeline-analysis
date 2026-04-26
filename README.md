# ZynqMP Audio Pipeline Latency Analysis

This repository contains the final project for the **CMP720 Embedded System Design** course at Hacettepe University (Spring 2026).

## Overview
The project investigates the real-time performance of audio pipelines on Linux-based heterogeneous systems. Using the **Renode** simulation platform, we emulate a **Zynq UltraScale+ MPSoC** to measure and analyze audio latency and jitter.

The main goal is to evaluate how predictable audio processing remains under system stress, comparing a standard Linux kernel against one with the **PREEMPT_RT** real-time patch. This analysis is crucial for understanding the reliability of communication systems in safety-critical environments.

## Key Features
- **Simulation-Based:** Uses Renode for deterministic and reproducible testing without physical hardware.
- **Latency Benchmarking:** Compares standard vs. real-time Linux kernels.
- **Stress Testing:** Analyzes performance under synthetic CPU and memory loads.
- **Predictive Modeling:** Validates experimental results against a theoretical latency budget.

## Directory Structure
```text
.
├── extended-project-proposal/
│   ├── cmp720_extended_zynqmp-audio-pipeline-analysis.zip  # LaTeX source files of extended proposal
│   ├── conference_101719.pdf                               # Finalized proposal document of extended proposal
│   └── Presentation-of-Extended-Proposal.pdf               # Presentation slides of extended proposal
├── midterm-project-presentations-peer-evaluation/          # Peer evaluation forms for midterm presentations
│   ├── evaluation-form-sertac-ust/                         # Evaluation forms submitted by Sertac Ust
│   └── evaluation-form-yasin-arslan/                       # Evaluation forms submitted by Yasin Arslan
├── project-proposal/
│   ├── cmp720_zynqmp-audio-pipeline-analysis.zip           # LaTeX source files of initial proposal
│   └── main.pdf                                            # Initial proposal document of initial proposal
└── README.md                                               # Project overview and documentation
```

## Authors
- **Yasin Arslan**
- **Süleyman Sertaç Üst**
