# Cat vs Dog Image Classification using Support Vector Machine (SVM)

A computer vision and machine learning project that implements a **Support Vector Machine (SVM)** classifier to distinguish between images of cats and dogs. The project demonstrates the complete image classification pipeline, including image preprocessing, feature extraction, model training, evaluation, and prediction using Python and Scikit-learn.

---

# Project Overview

Image classification is one of the most fundamental applications of Computer Vision and Machine Learning.

This project develops an image classification model capable of distinguishing between **cats** and **dogs** using the **Support Vector Machine (SVM)** algorithm.

The workflow includes image preprocessing, feature extraction, model training, prediction, and performance evaluation on the Microsoft Cats vs Dogs dataset.

---

# Problem Statement

Image recognition plays a significant role in modern AI applications, including animal recognition, healthcare, autonomous systems, and surveillance.

The objective of this project is to build a binary image classifier capable of accurately identifying whether an input image belongs to a **cat** or a **dog** using Support Vector Machine (SVM).

---

# Dataset

The project uses the **Microsoft Cats vs Dogs Dataset** provided on Kaggle.

> **Note:** The dataset is **not included** in this repository due to GitHub's file size limitations.

### Download Dataset

https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset

After downloading, extract the dataset and update the dataset path in the notebook before running the project.

---

# Dataset Structure

```
PetImages/

├── Cat/
│   ├── 0.jpg
│   ├── 1.jpg
│   └── ...
│
└── Dog/
    ├── 0.jpg
    ├── 1.jpg
    └── ...
```

---

# Project Objectives

- Load image dataset
- Preprocess images
- Convert images into numerical feature vectors
- Train an SVM classifier
- Predict image classes
- Evaluate classification performance
- Test the model on unseen images

---

# Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# Repository Structure

```
SCT_ML_3/

│
├── cat_vs_dog_classification.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── images/
```

---

# Machine Learning Workflow

### 1. Import Libraries

Load all required libraries.

### 2. Load Dataset

Read cat and dog images.

### 3. Image Preprocessing

- Resize images
- Convert to grayscale
- Flatten image pixels
- Normalize data

### 4. Train-Test Split

Split dataset into training and testing sets.

### 5. Model Development

Train a **Support Vector Machine (SVM)** classifier.

### 6. Model Prediction

Predict whether an image belongs to a cat or a dog.

### 7. Model Evaluation

Evaluate the classifier using standard classification metrics.

---

# Support Vector Machine (SVM)

Support Vector Machine is a supervised machine learning algorithm used for classification tasks.

The algorithm identifies the optimal decision boundary (hyperplane) that maximizes the separation between different classes.

For image classification problems, SVM is particularly effective when combined with appropriate image preprocessing and feature extraction techniques.

---

# Model Evaluation

The model is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

These metrics provide insight into the classifier's overall performance and prediction quality.

---

# Installation

Clone the repository

```bash
git clone https://github.com/dipanshushende/SCT_ML_3.git
```

Navigate to the project directory

```bash
cd SCT_ML_3
```

Install required libraries

```bash
pip install opencv-python numpy matplotlib scikit-learn jupyter
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
cat_vs_dog_classification.ipynb
```

Download the dataset from Kaggle and update the dataset path inside the notebook before executing all cells.

---

# Results

The trained SVM model successfully classifies images into **Cat** and **Dog** categories after image preprocessing and feature extraction.

The notebook demonstrates prediction on unseen images along with model evaluation metrics.

---

# Future Improvements

- Data Augmentation
- Hyperparameter Tuning
- Feature Extraction using HOG
- Deep Learning using CNN
- Transfer Learning with ResNet or MobileNet
- Deploy the model using Streamlit

---

# Skills Demonstrated

- Computer Vision
- Image Processing
- Feature Extraction
- Binary Image Classification
- Support Vector Machine (SVM)
- OpenCV
- NumPy
- Scikit-learn
- Python Programming

---

# Repository

**GitHub Repository**

https://github.com/dipanshushende/SCT_ML_3

---

# Author

**Dipanshu Shende**

Machine Learning Enthusiast | Python Developer | Data Science Learner

GitHub: https://github.com/dipanshushende


---

⭐ If you found this project helpful, consider giving it a Star!
