# CNN Model for Colon and Lung Cancer Classification

## Model Overview

**Overview**

This repository contains a Convolutional Neural Network (CNN) model designed to classify histopathology images into five distinct categories of colon and lung cancer. The model is capable of classifying the following cancer types:

- **Colon Adenocarcinoma**
- **Colon Benign Tissue**
- **Lung Adenocarcinoma**
- **Lung Benign Tissue**
- **Lung Squamous Cell Carcinoma**

The primary goal of this project is to provide a tool that aids medical professionals in accurately diagnosing different cancer types based on microscopic tissue images.

## Model Architecture

**The CNN model is built using the Keras framework with a TensorFlow backend. It utilizes a pretrained architecture as the base network (in this case, EfficientNetB7), followed by custom fully connected layers for classification.**

## Data Preparation

**Lung and colon histopathology dataset: [Link text Here](https://github.com/tampapath/lung_colon_image_set)**

**The histopathology image dataset is organized into five folders, each corresponding to one of the cancer types. The images are preprocessed and augmented using OpenCV and the ImageDataGenerator from Keras. Data augmentation techniques include random rotations, shifts, flips, and brightness adjustments.**

## Training and Evaluation

**The model is trained on a training dataset and validated using a separate validation dataset. After training, the model's performance is evaluated on a test dataset using various metrics, including accuracy, precision, recall, and F1-score.**

## Accuracy
**98%**
