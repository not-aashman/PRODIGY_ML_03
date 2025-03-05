# PRODIGY_ML_03: Image Classification of Cat vs. Dog Using SVM

## Task Overview
This repository contains the implementation of an image classification model using Support Vector Machines (SVM) to classify Cat vs. Dog images. The task was performed as part of the Machine Learning Internship Program at Prodigy InfoTech.

## Dataset
The dataset used for this task consists of 12,500 images of cats and dogs, with 6,250 images for each class (cat and dog). These images were resized to 64x64 pixels and labeled accordingly. Due to the large size of the dataset, it cannot be uploaded directly to this repository. You can download the dataset from the following link:

**[Download Cat vs. Dog Dataset](#)**

Once downloaded, place the dataset in the appropriate directory as outlined in the code.

### Dataset Features:
- **Images**: 64x64 pixel images, with two categories: Cat and Dog.
- **Labels**: 'cat' or 'dog'.

## Task Description
The task involved implementing a classification model to identify whether an image represents a cat or a dog using SVM.

### Steps Performed:
#### Data Preprocessing:
- Loaded and resized images into a consistent size (64x64 pixels).
- Split the dataset into a training set and a test set.
- Encoded the labels ('cat' and 'dog') into numerical values (0 and 1) using LabelEncoder.
- Scaled the features using StandardScaler for improved model performance.

#### Model Implementation:
- Implemented a Linear Support Vector Machine (SVM) model using scikit-learn.
- Trained the model on the training data.
- Made predictions on the test data.

#### Model Evaluation:
- Evaluated the model using accuracy and classification metrics (precision, recall, f1-score).
- Visualized predictions alongside the corresponding images.

## Model Performance:
- **Accuracy on Test Set**: 77.36%
- **Precision**: 0.77 for both 'cat' and 'dog'.
- **Recall**: 0.77 for both 'cat' and 'dog'.
- **F1-Score**: 0.77 for both 'cat' and 'dog'.

The model performs well with balanced precision and recall for both classes, demonstrating the ability of SVM to classify cat and dog images effectively.
