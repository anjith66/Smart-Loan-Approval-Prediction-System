# Loan Status Prediction Using Machine Learning

## 📌 Project Overview
This project predicts whether a loan application will be approved or not using Machine Learning algorithms. The model is trained using historical loan application data and predicts loan status based on applicant details such as income, education, employment status, credit history, and more.

The project demonstrates the complete Machine Learning pipeline including:
- Data preprocessing
- Handling missing values
- Feature encoding
- Model training
- Model evaluation
- Prediction system

---

## 🚀 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Features

The dataset contains the following features:

| Feature | Description |
|---------|-------------|
| Loan_ID | Unique Loan ID |
| Gender | Applicant Gender |
| Married | Marital Status |
| Dependents | Number of Dependents |
| Education | Education Status |
| Self_Employed | Self Employment Status |
| ApplicantIncome | Applicant Income |
| CoapplicantIncome | Coapplicant Income |
| LoanAmount | Loan Amount |
| Loan_Amount_Term | Loan Term |
| Credit_History | Credit History |
| Property_Area | Property Area |
| Loan_Status | Loan Approval Status |

---

## ⚙️ Machine Learning Workflow

### 1. Data Collection
- Loaded dataset using Pandas.

### 2. Data Preprocessing
- Checked missing values
- Handled null values
- Converted categorical values into numerical values

### 3. Data Analysis
- Performed exploratory data analysis
- Visualized important features

### 4. Train-Test Split
- Split dataset into training and testing datasets

### 5. Model Training
- Trained Machine Learning model using Scikit-learn

### 6. Model Evaluation
- Evaluated model accuracy on training and testing data

### 7. Prediction System
- Built a predictive system for new input data

---

## 📊 Model Used

- Support Vector Machine (SVM)

The model predicts whether:
- `1` → Loan Approved
- `0` → Loan Not Approved

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/anjith66/Smart-Loan-Approval-Prediction.git
