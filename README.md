# Medical Image Analysis and Classification

To develop an interactive deep learning-based system that enables users to classify medical images, such as blood and breast images, using a web-based platform.

## Objectives

- Implement state-of-the-art machine learning solutions to support the classification of BloodMNIST and BreastMNIST datasets.
- Provide a comprehensive standalone solution with dynamic user interactions.
- Analyze the performance of both existing and pre-trained models.
- Accurately classify images within the datasets.

## Introduction

This project focuses on two key datasets:

1. **BloodMNIST**: A dataset of blood cell images from patients diagnosed with eight different types of blood cancer.
2. **BreastMNIST**: A dataset used to predict breast cancer, with binary classes: 0 (benign) and 1 (malignant).

The provided images are 28x28 pixels, which are too low in resolution for manual classification. By leveraging machine learning techniques, we aim to create a system capable of accurate classification despite these limitations.

## Methodology

We utilized TensorFlow and Keras to build six neural networks, three of which are custom models. These models were trained and evaluated on the BloodMNIST and BreastMNIST datasets to assess their performance and accuracy in classifying medical images.
