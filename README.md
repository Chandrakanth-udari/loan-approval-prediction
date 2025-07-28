#  Loan Approval Prediction Project

This project predicts **loan approval** based on applicant details using **machine learning models**. 
It demonstrates data preprocessing, exploratory data analysis (EDA), and model evaluation.

---

## **Project Workflow**

1. **Problem Statement**  
   Predict whether a loan application will be approved based on applicant features.

2. **Dataset Overview**  
   The dataset contains details such as applicant income, loan amount, education, and credit history.  
   - **Target variable:** `Loan_Status` (Y = Approved, N = Not Approved).

3. **Exploratory Data Analysis (EDA)**  
   - Analyzed categorical variables (e.g., Gender, Married, Education).  
   - Visualized numerical variables (Applicant Income, Loan Amount).  
   - Key insight: **Credit history is the most important factor**.

4. **Model Training & Comparison**  
   Models trained:  
   - Decision Tree Classifier  
   - Random Forest Classifier  
   - Logistic Regression  

   We compare models using accuracy, confusion matrices, and classification reports.

5. **Model Evaluation**  
   - Accuracy score  
   - Precision, Recall, F1-score  
   - Feature importance (for tree-based models)

6. **Results**  
   - Logistic Regression achieved the highest accuracy.  
   - Credit history, loan amount, and income are top features influencing approval.

---

## **Technologies Used**
- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Joblib

---

## **How to Run**
1. Clone the repository:
   ```bash
   git clone <repo_url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook loan_prediction_portfolio.ipynb
   ```

---

## **Key Insights**
- Credit history significantly increases the probability of loan approval.
- Income and loan amount also play a vital role.
- Logistic Regression is effective for this dataset due to its simplicity and performance.

---

## **Future Work**
- Deploy the model with a web interface (Streamlit or Flask).
- Perform hyperparameter tuning for better performance.
- Handle imbalanced data using techniques like SMOTE.

---

## **Author**
**Chandrakant Yadav Udari**  
_Data Analyst with expertise in SQL, Python, Power BI, and machine learning._
