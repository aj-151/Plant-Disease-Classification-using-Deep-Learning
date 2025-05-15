# Plant Disease Classification using Deep Learning

## Overview

This project focuses on classifying plant diseases using deep learning techniques. The goal is to assist in early and accurate detection of plant diseases, contributing to improved crop health and agricultural productivity.

## Dataset

The dataset consists of over 50,000 labeled images across 48 plant disease categories, including healthy leaves and various common infections. It was sourced from the [PlantVillage dataset](https://www.kaggle.com/datasets/emmarex/plantdisease) and split into training, validation, and test sets.

# Technologies Used

Python

PyTorch

torchvision

NumPy

Matplotlib

scikit-learn

# Model Implementation

Multiple CNN architectures were evaluated for performance, including Inception, and MobileNet. After comparative analysis, ResNet was selected for its balance of accuracy and training efficiency. The model was fine-tuned using transfer learning techniques, with data augmentation and regularization to prevent overfitting.

Key steps:

    Data preprocessing and augmentation

    Transfer learning with pretrained ResNet

    Cross-entropy loss and Adam optimizer

    Training loop with early stopping

# Installation

git clone https://github.com/aakashjha123/plant-disease-classification.git
cd plant-disease-classification
pip install -r requirements.txt
python train.py


# Results and Insights

Achieved 95% test accuracy across 48 plant disease classes

ResNet outperformed other tested architectures in both accuracy and training time

Demonstrated strong generalization across unseen plant images, showing practical potential for real-world deployment

# Contributing

Contributions are welcome. Feel free to open issues or submit pull requests to enhance the project.

# Author

Aakash Jha


