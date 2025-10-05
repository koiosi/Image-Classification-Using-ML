---
# 
title: Sports Image Classification Project
author: "Canberk Atak"
date: "08/2024-09/2024"
output: Python(VSCode, Kaggle)

---

## Overview

This project focuses on building a **deep learning model for sports image classification** using PyTorch and torchvision. The goal is to classify images from multiple sports categories with high accuracy while leveraging GPU acceleration for faster training. The project also includes data augmentation, preprocessing, and visualization to ensure model robustness.

---

---

## Features

- Preprocessing and augmentation of image datasets for training, validation, and testing.
- Loading and visualizing image datasets using `ImageFolder` and `DataLoader`.
- GPU support for accelerated model training using PyTorch.
- Easy integration with Kaggle datasets using `kagglehub`.
- Visualization of image batches and labels to inspect data quality.

---

## Setup

Install required Python packages using pip:

```{r, engine='bash'}
pip install torch torchvision torchinfo matplotlib seaborn pandas numpy scikit-learn kagglehub
```

## Data

This dataset contains images from 100 different sports. Each image is in JPG format with a resolution of 224×224×3. The data is organized into separate folders for training, testing, and validation.
