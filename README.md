# Soil Classification and Crop Yield Prediction

## Introduction

This project consists of two separate tasks: soil classification and crop yield prediction. 

1. **Soil Classification**: Uses a Convolutional Neural Network (CNN) to classify soil images into three categories: Gravel, Sand, and Silt.
2. **Crop Yield Prediction**: Utilizes various regression models to predict crop yields based on a dataset of 28,242 entries.

## Soil Classification Project

### Overview

The soil classification project employs a CNN to categorize soil images into three classes: Gravel, Sand, and Silt. The model is trained on a dataset of 75 images and achieves an accuracy of approximately 80% on the test set.

### Model Architecture

The CNN model consists of the following layers:

- **Conv2D Layer**
- **Activation Layer**
- **MaxPooling2D Layer**
- **Flatten Layer**
- **Dense Layer**
- **Output Layer**

### Training

- **Optimizer**: Adam
- **Loss Function**: Categorical cross-entropy


## Crop Yield Prediction Project

### Overview

The crop yield prediction project uses various regression models to forecast crop yields based on a dataset of 28,242 entries. Models are trained on a subset of the data and evaluated on a separate test set.

### Models Used

- **Linear Regression**
- **Lasso Regression**
- **Ridge Regression**
- **Decision Tree Regressor**


## Model Performance

- **Linear Regression**:
  - MAE: 29,907.48
  - R-squared Score: 0.7473

- **Lasso Regression**:
  - MAE: 29,893.99
  - R-squared Score: 0.7473

- **Ridge Regression**:
  - MAE: 29,863.35
  - R-squared Score: 0.7473

- **Decision Tree Regressor**:
  - MAE: 3,916.23
  - R-squared Score: 0.9801


