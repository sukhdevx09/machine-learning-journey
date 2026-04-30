# Day 02 – Exploratory Data Analysis (EDA) & Data Preprocessing

Today I learned about EDA and data preprocessing, which are essential steps before building any machine learning model.

---

## 🔍 What is EDA?

EDA (Exploratory Data Analysis) is the process of analyzing and understanding the dataset.

It helps in:
- Understanding data distribution  
- Identifying patterns  
- Detecting outliers  
- Finding relationships between variables  

---

## 📊 Common EDA Techniques

- Checking dataset shape (`df.shape`)  
- Viewing first rows (`df.head()`)  
- Summary statistics (`df.describe()`)  
- Checking missing values (`df.isnull().sum()`)  
- Visualizations (histograms, boxplots, correlation heatmaps)  

---

## 🧹 What is Data Preprocessing?

Data preprocessing means cleaning and transforming raw data into a usable format.

---

## ⚙️ Steps in Data Preprocessing

### 1. Handling Missing Values
- Remove rows/columns  
- Fill with mean/median/mode  

---

### 2. Encoding Categorical Data
- Label Encoding  
- One-Hot Encoding  

---

### 3. Feature Scaling
- Standardization  
- Normalization  

---

### 4. Removing Outliers
- Using boxplots or statistical methods  

---

## 🔄 Workflow

Raw Data → EDA → Data Cleaning → Feature Engineering → Model Training

---

## 🔑 Key Takeaways

- Good data preprocessing improves model performance  
- EDA helps in understanding the dataset before modeling  
- Data quality is more important than model complexity  

---

## 🚀 Next Step

- Apply preprocessing on real dataset  
- Start building first ML model