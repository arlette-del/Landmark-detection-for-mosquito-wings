# Landmark Detection for mosquito wings

## Project Overview
This project focuses on detecting wing landmarks across different mosquito species.
It aims to systematically analyse wing morphology using geometric morphometrics and deep learning, with a focus on comparing different neural network architectures (CNN vs UNet) for landmark detection.

## Data
- **Wing images:** High-resolution images of mosquito wings from various species.
- **Normalized landmark coordinates:** Annotated landmarks corresponding to each wing image, used for training and evaluation.

The datasets are stored on a private Google Drive and are **not publicly accessible**.  
They were provided exclusively for this bachelor thesis.

## Installation and Setup
This Repository contains all scripts for Preprocessing, Training and Evaluation.
The notebooks were originally developed in Google Colab, but can be run locally as well.

### Repository Structure
- data/ # Placeholder for datasets (main data in Zenodo), incl. dataframe analysis (metadata)
- preprocessing/ # Script for preprocessing, creates NumPy arrays for training & evaluation
- training/
-   cnn/ # Training scripts and notebooks for CNN experiments
-   unet/ # Training scripts and notebooks for U-Net experiments
- evaluation/ # Jupyter notebooks for model evaluation
- README.md # Project documentation**

## Dependencies
The project requires the following Python libraries:

### Preprocessing:
- pandas
- numpy
- matplotlib
- opencv-python ('cv2')
- albumentations
- tensorflow
- scikit-learn
- scipy

### Training (CNN & UNet):
- pandas
- numpy
- matplotlib
- tensorflow / keras
- scikit-learn
- wandb (Weights & Biases)
- google-colab (for running in Colab)

### Evaluation:
- collections
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- statsmodels

