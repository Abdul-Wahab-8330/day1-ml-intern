# Day 1 AI/ML Internship Task - Iris Dataset Classifier

## 📌 Objective
Set up a clean Python machine learning environment, understand the core ML workflow (Data $\rightarrow$ Split $\rightarrow$ Train $\rightarrow$ Evaluate), and train a supervised classification model.

## 🛠️ Tech Stack & Environment
* **Language:** Python 3.14.0
* **Environment:** Python Virtual Environment (`.venv`)
* **Editor:** VS Code with Jupyter & Python extensions
* **Libraries Used:** `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `ipykernel`

## 🚀 Step-by-Step Implementation
1. **Environment Setup:** Created an isolated `.venv` and initialized Git version control.
2. **Data Loading:** Loaded the built-in Iris dataset from `scikit-learn` containing 150 samples across 4 feature dimensions (sepal/petal measurements) and 3 target flower species (`setosa`, `versicolor`, `virginica`).
3. **Train/Test Split:** Split the dataset into an **80% training set** and a **20% testing set** (`random_state=42`) to ensure unbiased evaluation.
4. **Model Selection:** Implemented a **K-Nearest Neighbors (KNN)** classifier with $K=3$.
5. **Training & Prediction:** Trained the model using `model.fit()` and generated predictions on unseen test data.

## 📊 Results & Output
* **Model Accuracy:** **100.00%**
* **Dataset Shape:** Features: `(150, 4)`, Targets: `(150,)`