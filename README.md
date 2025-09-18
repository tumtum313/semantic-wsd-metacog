# Semantic WSD with Meta-Cognition

Code and dataset for the research paper:  
**"Semantic Understanding in AI via Meta-Cognition and Self-Referential Reasoning: A Modular Cognitive Architecture"**

## Overview
This repository provides:
- **Baseline Word Sense Disambiguation (WSD)** using a Lesk-style gloss overlap.
- **Meta-cognitive WSD** with anomaly detection, reflection, and correction.
- Quantitative results: Baseline 62% → Meta-Cognitive 78%.
- Figures and error analysis.

## Files
- `baseline_wsd.py` — naive baseline WSD implementation.
- `meta_wsd.py` — meta-cognitive anomaly-corrected version.
- `combined_wsd.ipynb` — Colab-ready notebook that runs baseline & meta, computes accuracy, and generates figures.
- `data/sample_dataset.json` — toy dataset with ambiguous words (*field, organ, bass, mole, java*).
- `figures/` — pre-generated figures for the paper.

## Requirements
```bash
pip install matplotlib

