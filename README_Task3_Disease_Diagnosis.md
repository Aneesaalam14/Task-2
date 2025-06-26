
# Task 3: Disease Diagnosis Prediction

## 🎯 Objective:
Build a predictive model to determine the likelihood of diseases such as **diabetes** or **heart disease** using medical data.

---

## 📊 Dataset Used:
- **PIMA Diabetes Dataset**
- Contains medical predictor variables and one target variable (Outcome: 1 = Diabetes, 0 = No Diabetes)

---

## 🧪 Steps Performed:

### 1. Exploratory Data Analysis (EDA)
- Checked data structure, missing values, and distributions.
- Identified key patterns, such as age and glucose level trends.

### 2. Data Preprocessing
- Applied **feature scaling** using `StandardScaler`.
- Performed **train-test split** for evaluation.

### 3. Model Training
- Trained a classification model using **Gradient Boosting Classifier**.
- Alternative models like SVM or Neural Networks can also be tested.

### 4. Model Evaluation
- Evaluated using:
  - **F1 Score**
  - **Classification Report**
  - **AUC-ROC Curve**
- Achieved approx. **76% accuracy** with an AUC-ROC score of **0.82**.

---

## 💡 Insights for Healthcare:
- The model helps in early detection of diabetes risk based on medical inputs like glucose, BMI, and insulin.
- Can assist healthcare professionals in **preventive diagnostics** and **targeted screenings**.

---

## ✅ Outcome:
A machine learning model capable of accurately predicting diabetes risk, enabling actionable insights for early intervention and healthcare planning.
