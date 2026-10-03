
# Dataset Description

## Overview

This repository contains the research code and supporting resources used for multimodal brain tumor segmentation and classification experiments based on the Brain Tumor Segmentation (BraTS) 2023 Adult Glioma (GLI) Challenge dataset.

The imaging data used in this study were obtained from the ASNR-MICCAI-BraTS2023-GLI dataset available through the official Synapse repository. The dataset provides multimodal brain MRI data and corresponding tumor segmentation annotations for the applicable training data.

## MRI Modalities

The BraTS 2023 Adult Glioma dataset includes the following MRI sequences:

- T1n – Native T1-weighted MRI
- T1c – Contrast-enhanced T1-weighted MRI
- T2w – T2-weighted MRI
- T2-FLAIR (T2f) – Fluid-Attenuated Inversion Recovery MRI

## Use in This Research

The dataset was used for developing and evaluating the proposed deep learning framework. The research workflow includes:

1. MRI data preprocessing and normalization
2. Multimodal MRI processing
3. Tumor segmentation
4. Tumor-region and feature extraction
5. Tumor classification
6. Performance evaluation using segmentation and classification metrics

The exact subset, preprocessing procedures, data partitioning, and experimental configuration used in the study are described in the corresponding research manuscript and source-code directories.

## Dataset Availability

The original BraTS MRI data are not redistributed in this repository. Users should obtain the dataset directly from the official Synapse repository and comply with the applicable BraTS data-access requirements, terms and conditions, and citation requirements.

## Official Dataset

Dataset: ASNR-MICCAI-BraTS2023-GLI

Challenge: BraTS 2023 Adult Glioma (GLI) Challenge

Official Repository:
https://www.synapse.org/#!Synapse:syn51156910

## Reproducibility

To reproduce the experiments, obtain the BraTS 2023 Adult Glioma dataset from the official repository, place the data in the dataset location expected by the provided code, install the dependencies listed in requirements.txt, and follow the instructions provided in the relevant source-code directories.

## Citation

Users of the BraTS dataset should cite the official BraTS challenge/resource publications and follow the citation requirements specified by the dataset organizers.
