# 🍄 Mushroom Classification with Neural Networks and PCA

## 📘 Course Assignment
**DTSC-680: Applied Machine Learning**  

---

## 📌 Overview
This project predicts whether a mushroom is **edible or poisonous** based on its characteristics. The assignment required building two neural network models — one with raw one-hot encoded data and another after dimensionality reduction using **PCA** (preserving 95% of variance). All steps were performed in a well-documented Jupyter notebook.

---

## 🧪 Methodology

### 1. 📥 Data Preparation
- Loaded mushroom dataset from Brightspace.
- Used `agaricus-lepiota.names` to assign proper column headers.
- Split data: 80% training, 20% testing.
- Applied One-Hot Encoding to features.
- Label Encoded the target variable.

### 2. 🤖 Neural Network #1 (One-Hot Encoded Features)
- Used a sequential model with:
  - Input layer (Dense)
  - Output layer (Dense, sigmoid)
- Trained using binary crossentropy
- Evaluated with confusion matrix
- Timed with `%%time`

### 3. 📉 PCA + Neural Network #2
- Applied PCA to retain 95% variance
- Built new neural network using PCA features
- Compared training time, model performance
- Analyzed impact of dimensionality reduction

---

## 📈 Key Results

- High accuracy achieved on both models
- PCA model reduced input features significantly and trained faster
- Confusion matrices show strong classification performance

---

## 🧠 Concept Questions Answered
Included in the notebook:
- Feature count before vs. after encoding
- Output layer units rationale
- Network connection count
- PCA-reduced dimensionality analysis
- Explanation of `input_dim` change
- Training time comparison and expectations

---

## 📁 Project Files
- `Mushroom-Classification-with-Neural-Networks.ipynb`: Main notebook for training and evaluation  
- `pca_mushroom_model_.h5`: Trained neural network model using PCA  
- `agaricus-lepiota_.csv` 
- `README.md`

### 1. 🍄 Mushroom Classification with Neural Networks and PCA
- **Repo**: [mushroom-classification](https://github.com/lozanogangelicads/mushroom-classification)
- Built two neural networks to classify mushrooms as edible or poisonous. Applied PCA to improve performance and reduce dimensionality.
- Tools: Python, TensorFlow, Keras, PCA, Scikit-learn

