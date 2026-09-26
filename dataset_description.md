# Dataset Description

## Dataset used

This project uses the publicly available **BraTS 2023 Adult Glioma (BraTS-GLI)** dataset. The dataset is associated with the RSNA-ASNR-MICCAI Brain Tumor Segmentation (BraTS) challenge.

For this software release, the dataset itself is **not redistributed**. The repository contains the code, documentation and experimental outputs. Users should obtain the dataset from an authorized source and comply with the applicable dataset terms.

## Kaggle source used in this project

The BraTS 2023 Adult Glioma dataset is available through a Kaggle mirror:

https://www.kaggle.com/datasets/shakilrana/brats-2023-adult-glioma

The Kaggle dataset is a distribution point for the dataset; the original BraTS challenge/data-use conditions remain relevant.

## Data characteristics

BraTS 2023 Adult Glioma data comprise multimodal pre-operative brain MRI. The BraTS data use NIfTI imaging files and include multimodal MRI sequences such as T1, post-contrast T1 (T1c/T1Gd), T2 and T2-FLAIR. The training data include tumor segmentation annotations.

## Use in this project

### Segmentation

The 3D U-Net implementation uses multimodal MRI inputs and processes the data using the preprocessing and volume configuration defined in the segmentation notebook.

The notebook uses:
- T2-FLAIR
- T1c
- T2-weighted MRI
- 48 slices
- 128 × 128 spatial representation
- 3 input modalities

### Classification

The classification notebook uses image data derived/organized from the BraTS-related data for binary classification:
- Tumor
- No Tumor

The exact image preparation, split and preprocessing should be taken from the classification notebook.

## Important dataset note

The repository should not be interpreted as redistributing the BraTS dataset. Do not upload the original MRI volumes, segmentation masks or other third-party dataset files to this Zenodo record unless redistribution is explicitly permitted by the applicable dataset terms.

## Dataset citation

Users should cite the original BraTS publications/data source as required by the dataset terms, in addition to citing this software record.
