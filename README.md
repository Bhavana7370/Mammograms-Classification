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

## Data Visualization :
![counter3](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/3c4a2953-df10-4368-8e2a-8e8ffec86e4d)

![counter4](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/14ee2ac1-a42a-41a6-8fc9-77b78740159f)

![counter5](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/67e9ddae-0c92-4099-af43-004fc4c64ea6)

![counter-1](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/3d07d364-d6d3-4a52-b100-064fc0064299)

![counter-2](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/b8360b34-5f9c-4ddd-adb4-27171a23fd2a)




## Displaying images first five images in the dataset:
![displaying_images1](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/f1cd83a0-2fc1-4530-8e41-e37fd9c35acd)

![displaying_images2](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/6583ff85-6c92-4b6c-9d17-def30b878a2b)



## Loss & Accuracy:

![accuracy](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/ba48568f-8f72-44ee-b443-a1212496b3aa)



## Loss Curves:

![model-1](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/264159f7-25d3-4299-9be7-ad73f2e437c8)

![model-2](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/95e271e7-99cd-46e6-a90c-8dc3a2ecd609)

![model-3](https://github.com/Bhavana7370/Mammograms-Classification/assets/121118344/9f2e9d30-a7c1-47b5-b2af-0a1ea2d5eaaa)



