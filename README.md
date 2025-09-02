# Landmark Detection for mosquito wings

## Project Overview
This project focuses on detecting wing landmarks across different mosquito species.
It aims to systematically analyse wing morphology using geometric morphometrics and deep learning, with a focus on comparing different neural network architectures (CNN vs UNet) for landmark detection.

## Data
- **Wing images:** High-resolution images of mosquito wings from various species.
- **Normalized landmark coordinates:** Annotated landmarks corresponding to each wing image, used for training and evaluation.

Full datasets are hosted on Zenodo (LINK).

## Installation and Setup
This Repository contains all scripts for Preprocessing, Training and Evaluation.
The notebooks were originally developed in Google Colab, but can be run locally as well.

### Repository Structure
- /data: placeholder for datasets (main data in Zenodo), and analysis of the dataframe, containing metadata
- /preprocessing: scrip for preprocessing, creates all Numpys for training and evaluation
- /training/
-   /training CNN: training scripts and notebooks for all experiments using CNN model
-   /training UNet: training scripts and notebooks for all experiments using UNet model
- /evaluation: jupyter notebooks for model evaluation
- /README.md: project documentation

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
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- statsmodels

