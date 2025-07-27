# fMRI Brain Emotion Processing NX-421 Project 1
This repository contains the code and report of our work on the NX-421 mini-project 1. 

---
We employ the publicly available OpenNeuro ds000171 dataset which contains neural responses to 
emotionally charged auditory stimuli using functional magnetic resonance imaging (fMRI).
We apply relational modeling and multivariate pattern analysis to single-subject fMRI data to map emotional states onto specific brain regions and functional networks.
The aim of this project is to familiarize ourselves with the processing and analysis of fMRI datasets and to deepen our understanding of how the brain encodes emotionally varied auditory tones.

We implement:
1. **BIDS-compliant preprocessing** (slice timing, motion correction, smoothing, concatenation)  
2. **First-level GLM analysis** (design matrix, contrasts, Z-maps)  
3. **Dimensionality reduction via PCA** (artifact inspection, component selection)  
4. **Report & figures** documenting methods and results

---
The code and environment.yml are provided for reproducibility. See the [report](./Report.pdf) for details about results and analysis.
