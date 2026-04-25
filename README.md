# Cats vs Dogs Image Classification using CNN

An end-to-end deep learning project that classifies images of cats and dogs using a Convolutional Neural Network (CNN), including preprocessing, training, evaluation, and fine-tuning.

---

## Project Overview

This project builds a CNN model to classify images as cats or dogs. The model is trained on a labeled dataset and evaluated using performance metrics and visualizations.

---

## Objectives

- Build a CNN model from scratch  
- Understand image preprocessing and data augmentation  
- Improve model performance using tuning techniques  
- Evaluate the model using real-world metrics  

---

## Dataset

**Source:** Kaggle  
https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset  

### Dataset Description

- Two classes: Cats and Dogs  
- Organized into:
  - Training set  
  - Validation set  
  - Test set  

### Setup Instructions

1. Download the dataset from the link above  
2. Extract it into the project folder  
3. Ensure the folder structure is:
data/
│
├── train/
│ ├── cats/
│ └── dogs/
│
├── validation/
│ ├── cats/
│ └── dogs/
│
├── test/
├── cats/
└── dogs/

---

## Model Architecture

The CNN model consists of:

- Convolutional Layers (feature extraction)  
- MaxPooling Layers (downsampling)  
- Flatten Layer  
- Dense Layers  
- Dropout Layer (to reduce overfitting)  
- Output Layer (Sigmoid activation)  

---

## Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Seaborn  

---

## Training Details

- Loss Function: Binary Crossentropy  
- Optimizer: Adam  
- Learning Rate: 0.0001  
- Epochs: 10–15  
- Data Augmentation applied  

---

## Evaluation

The model is evaluated using:

- Accuracy  
- Predictions  
- Confusion Matrix  

Example:

|            | Predicted Cat | Predicted Dog |
| ---------- | ------------- | ------------- |
| Actual Cat | Correct       | Incorrect     |
| Actual Dog | Incorrect     | Correct       |

---

## Key Learnings

- Understanding how CNNs process image data  
- Importance of data augmentation  
- Handling model bias and misclassification  
- Impact of learning rate and dropout  

---

## Future Improvements

- Apply Transfer Learning (e.g., MobileNet, ResNet)  
- Improve accuracy with deeper architectures  
- Deploy the model as a web application  

---


