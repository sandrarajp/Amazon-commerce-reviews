# 🛒 Amazon Commerce Reviews Classification  

## 📘 Project Overview  
This project implements **machine learning classification algorithms from scratch** — including **Perceptron**, **Logistic Regression**, and a **Simple Neural Network** — to classify **Amazon product reviews** by author.  

The aim is to understand and build the mathematical foundations of ML algorithms using only **NumPy**, without relying on high-level machine learning libraries such as scikit-learn for model training (only for feature selection and evaluation).  

---

## 🎯 Objectives  
- Understand the logic behind Perceptron, Logistic Regression, and Neural Networks.  
- Implement these algorithms from scratch using **NumPy**.  
- Train and test models on a **real-world dataset** (Amazon Commerce Reviews).  
- Evaluate model performance and compare accuracy across algorithms.  

---

## 📂 Dataset Description  
**Dataset:** `Amazon_dataset.csv`  
**Source:** Amazon Commerce Reviews dataset (prepared for academic use).  

**Details:**  
- Each row represents an Amazon product review and its associated **author**.  
- The column `class_1` contains the **author name** (target variable).  
- Other columns represent **numerical or vectorized text features**.  
- Task: Predict whether a review was written by a given author (e.g., `"Agresti"`) using **binary classification (One-vs-All)**.  

---

## 🧠 Algorithms Implemented (From Scratch)  

| Algorithm | Description | Learning Type |
|------------|--------------|----------------|
| **Perceptron** | Linear classifier using rule-based weight updates. | Online Learning |
| **Logistic Regression** | Probabilistic classifier using sigmoid activation and gradient descent. | Batch Learning |
| **Simple Neural Network (1 Hidden Layer)** | Nonlinear classifier using backpropagation. | Deep Learning |

---

## ⚙️ Project Workflow  

1. **Data Loading & Inspection**  
   - Read the dataset.  
   - Verify structure and presence of the `class_1` column.  

2. **Feature Preprocessing**  
   - Handle missing values (mean imputation).  
   - Remove low-variance features using `VarianceThreshold`.  
   - Select top features using `SelectKBest` (ANOVA F-test).  
   - Add bias term to the feature matrix.  

3. **Model Implementation**  
   - Implement each algorithm class from scratch (`Perceptron`, `ScratchLogisticRegression`, `SimpleNN`).  

4. **Model Training & Evaluation**  
   - Train models using the training data.  
   - Evaluate accuracy, precision, recall, and F1-score.  
   - Plot loss curves for Logistic Regression and Neural Network.  

---

## 📈 Results Summary  

| Model | Accuracy | Notes |
|--------|-----------|-------|
| **Perceptron** | ~60–70% | Works well for linearly separable data. |
| **Logistic Regression** | ~70–80% | Good generalization with gradient descent. |
| **Simple Neural Network** | ~80–90% | Captures nonlinear relationships effectively. |

*(Results depend on preprocessing and hyperparameters.)*

---

## 📊 Visualizations  
- **Loss Curves:**  
  - Logistic Regression – smooth exponential decay.  
  - Neural Network – converging binary cross-entropy loss.  

- **Confusion Matrix:**  
  - Shows correct vs. incorrect classifications for the target author.  

---

## 🧰 Technologies Used  
- **Python 3.x**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**  
- **Scikit-learn** (only for preprocessing & metrics)  
- **Google Colab / Jupyter Notebook**

---

## 🧾 How to Run  

###  Google Colab  
1. Upload the notebook and dataset (`Amazon_dataset.csv`).  
2. Run all cells sequentially.  
3. View printed outputs and plots inline.

---

## 🧪 Example Outputs
- Logistic Regression Loss Curve

- Neural Network Loss Curve

---

## 👩‍💻 Author

- Name:Sandra Raj P Data Analyst
- Institution: University of Europe
- Course: Machine Learning Fundamentals
- Instructor: Prof.Nor
- Year: 2025

