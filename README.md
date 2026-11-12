
# PILL — Physics-Informed Landslide Learning

PILL is a deep learning implementation for landslide mapping using multispectral remote sensing imagery and terrain information. The repository contains the implementation of a physics-informed learning pipeline that combines data-driven prediction with numerical representations of slope stability.

## Repository Purpose

This repository provides the implementation, experimental configuration, and evaluation pipeline associated with PILL. It is intended to support reproducibility and facilitate further research on physics-informed landslide prediction.

## Dataset

Experiments are conducted using the [Landslide4Sense Dataset](https://github.com/iarai/Landslide4Sense).

The dataset contains multispectral satellite observations, terrain attributes, and corresponding landslide annotations. The implementation expects spatial patches with 14 input channels and pixel-level binary segmentation masks.

**Note:** Dataset files are not distributed with this repository. Please obtain the dataset from its official source and organize it according to the expected directory structure.

## Implementation Highlights

- Deep learning-based landslide segmentation.
- Spatial geotechnical parameter estimation.
- Fourier Neural Operator-based physical response modelling.
- Intermediate physical field prediction.
- Physics-regularized optimization.
- Pixel-level landslide probability estimation.

## Experimental Setup

The implementation supports model training and evaluation on Landslide4Sense. The experimental pipeline includes:

- Dataset loading and preprocessing.
- Model initialization and optimization.
- Physics-informed loss computation.
- Validation and performance evaluation.
- Landslide map generation.
- Intermediate physical response visualization.

## Model Outputs

The trained network provides spatial predictions that can be used for:

- Landslide map generation.
- Visualization of predicted physical fields.
- Quantitative evaluation against reference masks.
- Analysis of model behaviour under different experimental configurations.

## Reproducibility

For reproducibility, users should configure the dataset paths, computational environment, and training parameters according to their experimental setup.

Additional instructions for installation, training, and inference are provided in the corresponding sections of this repository.
