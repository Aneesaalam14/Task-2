
# 📝 README – Task 4: Loan Default Prediction

**Objective**  
To build a classification model that predicts whether a loan applicant will default, using historical financial data.

---

**Dataset**  
- **Source**: Lending Club Loan Dataset  
- **File Used**: `accepted_2007_to_2018q4.csv`  
- **Rows**: ~2.26 million | **Columns**: 151  
- A subset of relevant columns was selected to optimize performance.

---

**Steps Performed**  

1. **Data Preprocessing**  
   - Loaded and examined the dataset structure  
   - Removed unnecessary or sparse columns  
   - Dropped rows with missing values in selected fields  
   - Addressed class imbalance using **SMOTE** (Synthetic Minority Oversampling Technique)

2. **Feature Engineering**  
   - Identified numerical and categorical variables  
   - Applied `StandardScaler` to numerical features  
   - Performed one-hot encoding on categorical variables

3. **Model Training**  
   - Data split into training and testing sets (80/20)  
   - Trained a **LightGBM Classifier** for prediction  
   - Training completed successfully without overfitting

4. **Model Evaluation**  
   - Evaluated with **Precision, Recall, F1-Score**, and **AUC-ROC**  
   - Visualized using Confusion Matrix and ROC Curve

5. **Insights & Recommendations**  
   - Model demonstrates solid ability to distinguish risky borrowers  
   - Useful tool for lenders to flag high-risk applications  
   - Suggestions:
     - Fine-tune model hyperparameters  
     - Use more recent datasets  
     - Incorporate external credit scores for stronger predictive power

---

**Outcome**  
A scalable and interpretable loan risk prediction model that can support lenders in reducing financial losses due to loan defaults.
