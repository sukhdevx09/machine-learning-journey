# Day 04 – Classification Models (Titanic Dataset)

Today I implemented multiple classification algorithms on the Titanic dataset and compared their performance.

---

## 📊 Concepts Learned

### 🔹 Logistic Regression
- Used for binary classification  
- Outputs probability between 0 and 1  

---

### 🔹 K-Nearest Neighbors (KNN)
- Classifies based on nearest data points  
- Sensitive to scaling  

---

### 🔹 Decision Tree
- Splits data based on conditions  
- Easy to interpret  

---

### 🔹 Naive Bayes
- Based on probability and Bayes theorem  
- Assumes feature independence  

---

### 🔹 Support Vector Machine (SVM)
- Finds optimal boundary (hyperplane)  
- Works well in high-dimensional space  

---

## 🧪 What I Implemented

- Loaded Titanic dataset  
- Performed data preprocessing:
  - Handled missing values  
  - Encoded categorical variables  
  - Feature scaling (where required)  

- Applied models:
  - Logistic Regression  
  - KNN  
  - Decision Tree  
  - Naive Bayes  
  - SVM  

- Compared model performance  

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

## 📊 Key Observations

- Different models perform differently on same dataset  
- Scaling improves KNN and SVM performance  
- Decision Tree is easy to interpret but may overfit  
- Logistic Regression gives stable baseline  

---

## 🔄 Workflow

Dataset → Preprocessing → Feature Engineering → Model Training → Evaluation → Comparison

---

## 🔑 Key Takeaways

- No single model is always best  
- Model selection depends on data  
- Preprocessing is crucial for performance  

---

## 📁 Dataset

Titanic Dataset (Kaggle)

---

## 🚀 Next Step

- Hyperparameter tuning  
- Cross-validation  
- Try ensemble models (Random Forest, XGBoost)