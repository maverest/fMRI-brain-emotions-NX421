# EPFL NSSP fMRI Emotion Project 1

**Authors:** Jean Ciardo, Romain Frossard, Hugo Jeannin, Mathieu Verest  
**Affiliation:** École Polytechnique Fédérale de Lausanne (EPFL)  
**Project:** Neural Signals and Signal Processing — Mini-Project 1  
**DOI / Archive link:** _(add Zenodo / OpenNeuro DOI here)_

---

## Overview

This repository contains the code, data pointers, and report for our fMRI analysis of emotionally charged auditory stimuli (positive vs. negative music vs. neutral tones) in healthy control subjects.

We implement:

1. **BIDS-compliant preprocessing** (slice timing, motion correction, smoothing, concatenation)  
2. **First-level GLM analysis** (design matrix, contrasts, Z-maps)  
3. **Dimensionality reduction via PCA** (artifact inspection, component selection)  
4. **Report & figures** documenting methods and results

---

## Repository Structure

```text
epfl-nssp-fmri-emotion-project1/
├── README.md                 ← this file
├── LICENSE                   ← choose e.g. MIT or BSD 3-Clause
├── CITATION.cff              ← citation metadata for GitHub
├── .gitignore
│
├── data/                     
│   ├── raw/                  ← BIDS‐style raw NIfTI + .tsv/.json (not committed)
│   └── derivatives/          ← preprocessed outputs (hall-of-mirrors)
│
├── code/                     
│   ├── preprocessing/        ← nipype / FSL scripts
│   ├── glm/                  ← first-level model & contrasts
│   ├── pca/                  ← PCA pipeline
│   └── utils/                ← helper functions
│
├── notebooks/                
│   ├── 01_preprocessing.ipynb
│   └── 02_analysis.ipynb
│
├── figures/                  ← final PNGs / PDF plots
│
├── report/                   
│   ├── NSSP_mini_project1.pdf
│   └── source/               ← LaTeX or Markdown source
│
├── environment.yml           ← Conda environment
└── Dockerfile                ← reproducible container (optional)
