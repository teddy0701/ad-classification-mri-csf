# Alzheimer’s Disease Classification Using MRI and CSF Biomarkers

This repository contains early-stage research exploring deep learning approaches
for Alzheimer’s disease (AD) classification using structural MRI data and
longitudinal cerebrospinal fluid (CSF) biomarkers.

The project focuses on evaluating neural network–based models for medical imaging
and biomarker analysis, with an emphasis on interpretability and methodological
experimentation.

## Project Overview
Accurate and interpretable models for Alzheimer’s disease classification are
critical for understanding disease progression and supporting clinical research.
This project investigates how deep learning models can be applied to multimodal
biomedical data, including brain MRI and longitudinal CSF measurements.

The work in this repository represents an exploratory phase of model development
and serves as a foundation for subsequent, more advanced research projects.

## Methods
The following approaches are explored:
- 3D convolutional neural networks (3D CNNs) applied to structural MRI volumes
- Grad-CAM–based visualization to identify brain regions contributing to model predictions
- Temporal modeling of longitudinal CSF biomarkers using sequence-based approaches

These methods were used to assess feasibility, performance trends, and
interpretability rather than to produce a finalized clinical model.

## Data
The analyses assume de-identified research data derived from established
Alzheimer’s disease datasets. Raw imaging and biomarker data are not included in
this repository due to privacy and data-sharing restrictions.

## Repository Contents
- `696_project.ipynb`  
  Notebook containing data preprocessing, model training, Grad-CAM visualization,
  and evaluation experiments.

## Context and Notes
This repository documents an earlier phase of research and model experimentation.
More recent and refined work building on these ideas, including advanced modeling
and improved documentation, is available in related repositories on this profile.

This code is provided for research and educational purposes only and is not
intended for clinical decision-making.
