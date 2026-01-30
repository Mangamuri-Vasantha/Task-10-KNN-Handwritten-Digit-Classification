# Task-10-KNN-Handwritten-Digit-Classification
# 🧠 KNN – Handwritten Digit Classification

## 📌 Project Overview
In this project, I implemented a K-Nearest Neighbors (KNN) model to classify handwritten digits using the Scikit-learn Digits dataset. The objective was to understand how distance-based classification works and how different values of K affect model performance.

## 🎯 Objectives
- Load and explore the digits dataset
- Visualize sample handwritten digit images
- Split the dataset into training and testing sets
- Apply feature scaling
- Train a KNN classifier
- Evaluate accuracy for different K values
- Plot Accuracy vs K graph
- Generate a confusion matrix
- Display sample predictions

## 🛠 Tools & Libraries Used
- Python  
- NumPy  
- Matplotlib  
- Scikit-learn  

## 📂 Dataset
The dataset was loaded using Scikit-learn's built-in `load_digits()` function.
- Total samples: 1797
- Image size: 8×8 pixels
- Target classes: Digits from 0 to 9

## 🚀 Steps Performed
1. Loaded the dataset and checked the shape of features and labels
2. Visualized a few digit images using Matplotlib
3. Split the dataset into training and testing sets
4. Applied StandardScaler for feature scaling
5. Trained the KNN model with K=3
6. Tested multiple K values (3, 5, 7, 9) to compare accuracy
7. Plotted an Accuracy vs K graph
8. Generated a confusion matrix to evaluate performance
9. Displayed predictions on sample test images

## 📈 Model Performance
The model achieved good accuracy, and performance varied slightly with different K values. The confusion matrix helped identify misclassified digits.

## 🧩 Key Learnings
- Understanding of KNN algorithm
- Importance of feature scaling
- Impact of K value on model accuracy
- How to evaluate classification models using accuracy and confusion matrix

## ✅ Conclusion
This project demonstrates how KNN can be applied to handwritten digit classification and highlights the importance of choosing the right K value and scaling features for better performance.
