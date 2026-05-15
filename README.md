# Aerial Road Segmentation using PyTorch

![Aerial\_Image\_Segmentation](https://github.com/user-attachments/assets/62ab7e9c-dbcb-4bf8-a201-43b471495dff)

## Overview

Deep learning project for road segmentation from aerial imagery using **U-Net** with an **EfficientNet-B0** backbone. Built with PyTorch and trained on the Massachusetts Roads Dataset.

## Features

* Road segmentation from aerial images
* U-Net + EfficientNet-B0 architecture
* Data augmentation with Albumentations
* Dice Loss + Binary Cross Entropy
* Training and inference pipeline

## Dataset

* Massachusetts Roads Dataset
* Source: [https://www.kaggle.com/datasets/balraj98/massachusetts-roads-dataset](https://www.kaggle.com/datasets/balraj98/massachusetts-roads-dataset)

## Tech Stack

* PyTorch
* segmentation-models-pytorch
* Albumentations
* OpenCV
* NumPy

## Hyperparameters

* Learning Rate: `0.003`
* Batch Size: `8`
* Image Size: `512×512`
* Epochs: `25`

## Workflow

Aerial Image → Preprocessing → U-Net Segmentation → Road Mask Prediction

## Future Improvements

* Train on larger datasets
* Try advanced segmentation architectures
* Improve augmentation and accuracy
