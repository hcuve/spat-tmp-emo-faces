# Spatiotemporal Structure and Substates in Emotional Facial Expressions

This repository contains the code for processing and modelling associated with the manuscript:

**Cuve, H. C. J., Sowden, S., & Cook, J.** *Spatiotemporal structure and substates in emotional facial expressions.*

## Repository Contents

All scripts related to the paper can be found in the `Paper` folder. The scripts are organised in the following order, which corresponds to the sequence of steps outlined in the manuscript:

1. **Pre-processing:** Scripts for processing OpenFace data, specifically for expression-only and emotive speech data.
2. **NMF Fitting:** Code to fit Non-negative Matrix Factorisation (NMF) models to learn the spatiotemporal structure based on AU (Action Unit) time series.
3. **Validation:** A series of validation steps to assess the NMF models.
4. **Feature Extraction:** Scripts to derive time series features from the spatiotemporal components.
5. **Supervised Classification:** Scripts for performing supervised classification analysis.
6. **Figures:** Scripts to generate the figures presented in the paper.

Please follow the order of the scripts as they appear in the manuscript for accurate replication of the results.

## Data Availability

The raw data used in this study is available at: [https://osf.io/3nzk7/](https://osf.io/3nzk7/)



## To-Do
- [ ] Move older code to local env folder

- [ ] Write a few wiki walkthroughs for different parts of the code to aid understanding and usage.
