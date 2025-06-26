
# 🧠 Employee Attrition Prediction (IBM HR Analytics)

## 📌 Objective

Build a classification model to predict whether an employee will leave a company based on HR data, and derive actionable insights to help HR teams reduce attrition.

---

## 📊 Dataset

**Source:** IBM HR Analytics Employee Attrition & Performance  
**Rows:** 1470  
**Features:** 35 (including Age, MonthlyIncome, OverTime, JobSatisfaction, etc.)  
**Target Variable:** `Attrition` (Yes/No)

---

## 🧪 Steps Performed

### 1. Exploratory Data Analysis (EDA)
- Loaded and inspected the dataset structure
- Cleaned data and understood variables
- Identified key drivers of attrition

### 2. Model Training
- Used `RandomForestClassifier`
- One-hot encoded categorical variables
- Split data into training/testing sets
- Evaluated with classification report and confusion matrix

**Accuracy:** ~88%

### 3. Explainability
- Attempted SHAP, faced environment issues in Colab
- Used feature importance from model instead

### 4. Actionable Insights
- 💰 **MonthlyIncome**: Low salary is linked to attrition  
- ⏱️ **OverTime**: Overtime increases chance of leaving  
- ⚖️ **DailyRate**: Compensation fairness matters

---

## 🛠️ Tools Used

- Google Colab
- Python
- pandas, scikit-learn
- matplotlib
- SHAP (attempted)

---

## ✅ Outcome

A classification model that predicts attrition and provides explainable insights to support HR in building better retention strategies.
