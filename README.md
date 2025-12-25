# Unified Action via Informational Coherence

This repository accompanies the paper:

 "A Distributed Coherence-Driven System: A Unified Action Framework for Decentralized Self-Organizing Networks"  
Henry Matuchaki, 2025.

## Overview
This project implements a decentralized dynamical system in which global order
emerges from local optimization of a unified action function combining:
- informational coherence (ICOER),
- interaction potential,
- structural tension.

The system requires no central authority, no global consensus, and no semantic control.

## Repository Structure
- `paper/` — LaTeX source and figures for the arXiv paper
- `src/` — core model and metrics
- `experiments/` — scripts to reproduce figures
- `data/` — optional experiment outputs

## Reproducibility
To reproduce the figures:
```bash
pip install -r requirements.txt
python experiments/run_baseline.py
python experiments/run_churn.py

## License
MIT License. See LICENSE.

## Citation
See CITATION.cff.
