

# COVID-19 Image Classification Project

This project aims to classify X-ray images into two categories: COVID-19 and Normal, using Convolutional Neural Networks (CNNs) and Transfer Learning.

## Project Overview

The project started with a simple CNN model, which achieved an accuracy of around 56%. To improve the model's performance, several strategies were implemented:

1. Data augmentation: Random horizontal flips and rotations were added to the training images to increase the diversity of the training data.

2. Transfer learning: A pre-trained VGG16 model was used, with the final layer replaced to suit our binary classification task. This significantly improved the accuracy to around 72-80%.

3. TensorBoard: TensorBoard was used for visualization purposes, providing insights into the training process, and helping to fine-tune the model.

![Alt text](https://github.com/ChngJeremy/CSC3009-Assignment/blob/master/image/2665401.png)

![Alt text](https://github.com/ChngJeremy/CSC3009-Assignment/blob/master/image/individualImage.png)
## Dataset

The dataset consists of X-ray images, divided into two categories: COVID-19 and Normal. The images were preprocessed and augmented before being fed into the model.

## Requirements

To install the necessary libraries for this project, use the following command:

```
pip install -r requirements.txt
```
