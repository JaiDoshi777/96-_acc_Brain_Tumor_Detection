# 96-_acc_Brain_Tumor_Detection
Implementation of a Convolutional Neural Network (CNN)-based model for brain tumor classification using the Kaggle Brain Tumor MRI Dataset

# Introduction

Brain tumor detection is a crucial task in medical imaging, as early diagnosis can significantly improve treatment outcomes. This report summarizes the methodology and implementation of a Convolutional Neural Network (CNN)-based model for brain tumor classification using the Kaggle Brain Tumor MRI Dataset.

# Dataset Overview

The dataset consists of MRI images stored in a directory named "Training." The images are categorized into different classes, likely representing "Tumor" and "No Tumor." The code processes these images to prepare them for training a deep learning model.

# Methodology

A. Data Preprocessing

1. The dataset is loaded, and image file paths and labels are extracted.

2. Images are resized and converted into arrays using PIL.

3. Normalization is applied to standardize pixel values.

4. ImageDataGenerator is used for data augmentation to enhance model generalization.

5. The dataset is split into training and validation sets using train_test_split
