# 96-_acc_Brain_Tumor_Detection
Implementation of a Convolutional Neural Network (CNN)-based model for brain tumor classification using the Kaggle Brain Tumor MRI Dataset

# Introduction

Brain tumor detection is a crucial task in medical imaging, as early diagnosis can significantly improve treatment outcomes. This report summarizes the methodology and implementation of a Convolutional Neural Network (CNN)-based model for brain tumor classification using the Kaggle Brain Tumor MRI Dataset.

# Dataset Overview

The dataset consists of MRI images stored in a directory named "Training." The images are categorized into different classes, likely representing "Tumor" and "No Tumor." The code processes these images to prepare them for training a deep learning model.

# Methodology

A. Data Preprocessing - A Sequential Convolutional Neural Network (CNN) model is designed with the following layers:

1. The dataset is loaded, and image file paths and labels are extracted.
2. Images are resized and converted into arrays using PIL.
3. Normalization is applied to standardize pixel values.
4. ImageDataGenerator is used for data augmentation to enhance model generalization.
5. The dataset is split into training and validation sets using train_test_split
   
B. Model Architecture

1. Convolutional Layers - Feature extraction using Conv2D.
2. MaxPooling Layers - Reduces spatial dimensions.
3. Flatten Layer - Converts feature maps into a vector.
4. Fully Connected (Dense) Layers - Performs classification.
5. Dropout Layers - Prevents overfitting.
6. Activation Function - Uses ReLU for hidden layers and Softmax for output.
7. Optimizer - Adamax optimizer is employed for training.

C. Model Training

1. The model is compiled with appropriate loss and optimizer settings.
2. The training process includes early stopping to prevent overfitting.
3. The model is trained using fit() with a defined batch size and epochs.

D. Model Evaluation

1. A Confusion Matrix and Classification Report are generated to evaluate the model's performance.
2. Accuracy and loss trends are visualized using Matplotlib and Seaborn.

# Results and Findings

1. The CNN successfully learns to differentiate between tumor and non-tumor MRI scans.
2. Performance metrics such as accuracy, precision, recall, and F1-score indicate the model's effectiveness.
3. Visualizations of loss and accuracy trends provide insights into the training process.

# Conclusion

This project demonstrates the feasibility of using deep learning for brain tumor classification. The CNN model efficiently processes MRI scans and classifies them with promising accuracy. Further improvements can be made by fine-tuning hyperparameters, using larger datasets, or implementing advanced architectures such as transfer learning.

![image](https://github.com/user-attachments/assets/23dc821c-05c5-481f-bd24-e859148de54e)
![image](https://github.com/user-attachments/assets/c05b8e05-fb02-4de5-8cf2-33ea0f2df0a6)
![image](https://github.com/user-attachments/assets/d938bd0a-522f-4e1d-9810-0069c7ebf12d)
![image](https://github.com/user-attachments/assets/ebddb360-fd6a-4e18-91b8-bd28776335ae)






