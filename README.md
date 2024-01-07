# Mammogram Classification with CNN

## Overview:

This repository contains the code and resources for a Convolutional Neural Network (CNN) based classification system for mammograms. The model is trained on a dataset comprising approximately 3,000 mammogram images.

## Key Features:

- **Convolutional Neural Network (CNN):** Utilized a deep learning architecture for image classification tailored to mammograms.
  
- **Dataset:** The model was trained on a diverse dataset consisting of around 3,000 mammogram images, ensuring a broad representation of cases.

- **Model Evaluation:** Detailed evaluation metrics, including accuracy are provided to assess the model's performance.



## Model Summary:

```plaintext
Model: "sequential_3"
_________________________________________________________________
Layer (type)                Output Shape              Param #   
=================================================================
conv2d_12 (Conv2D)          (None, 222, 222, 32)      896       
max_pooling2d_12 (MaxPooling (None, 111, 111, 32)      0         
conv2d_13 (Conv2D)          (None, 109, 109, 64)      18496     
max_pooling2d_13 (MaxPooling (None, 54, 54, 64)        0         
conv2d_14 (Conv2D)          (None, 52, 52, 128)       73856     
max_pooling2d_14 (MaxPooling (None, 26, 26, 128)       0         
conv2d_15 (Conv2D)          (None, 24, 24, 128)       147584    
max_pooling2d_15 (MaxPooling (None, 12, 12, 128)       0         
flatten_3 (Flatten)         (None, 18432)             0         
```

