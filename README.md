# Machine Learning for Essential Gene Prediction in *E. coli*

This project replicates and extends the results of a recent scientific publication on essential gene prediction using flux-coupled features and Support Vector Machines (SVMs). It was completed as part of the Winter 2025 course **CSI 5180 – Machine Learning for Bioinformatics** at the University of Ottawa.

## Reference Paper

> **An integrative machine learning strategy for improved prediction of essential genes in *Escherichia coli* metabolism using flux-coupled features**  
> DOI	https://doi.org/10.1039/C7MB00234C

## Project Summary

As an individual course project, I independently reimplemented the SVM-based prediction workflow described in the paper. The process involved:

- Processed and balanced 1,000 gene datasets.
- Reproduced classification performance using an SVM model implementation.
- Accelerated the training pipeline with GPU-backed cuML from the RAPIDS ecosystem.
- Tuned and compared alternative ML classifiers for benchmarking.
