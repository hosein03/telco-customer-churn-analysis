# Customer Churn Prediction

This project analyzes customer churn in the **Telco Customer Churn** dataset. The goal is to identify key factors contributing to customer churn and build predictive models to classify whether a customer is likely to leave or stay.

---

## 📂 Dataset
- **Source**: Telco Customer Churn dataset  
- **Size**: ~7,000 customers  
- **Target Variable**: `Churn` (Yes/No)

The dataset includes demographic information, account details, and service usage patterns.

---

## 🔎 Steps Performed

### 1. Data Loading & Exploration
- Loaded dataset with Pandas.
- Checked shape, datatypes, and missing values.
- Performed descriptive statistics.

### 2. Data Cleaning
- Converted binary categorical variables (Yes/No) into numerical format.
- Encoded categorical features using label/one-hot encoding.
- Handled missing values.

### 3. Exploratory Data Analysis (EDA)
- Visualized churn distribution.
- Explored correlations between churn and:
  - Contract type  
  - Internet service  
  - Payment method  
  - Monthly charges  

### 4. Feature Engineering
- Selected important features based on correlation analysis.
- Scaled numerical variables where necessary.

### 5. Modeling
- Applied multiple classification models:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - (Any other you tried)  
- Compared performance based on accuracy, precision, recall, and F1-score.

### 6. Results & Evaluation
- Identified the most influential features for churn.  
- Best-performing model: **(write your best model here, e.g. Random Forest with 82% accuracy)**  
- Customers with **month-to-month contracts** and **higher monthly charges** were more likely to churn.

---

## ✅ Conclusion
- Churn prediction is possible with good accuracy using machine learning models.  
- The most important drivers of churn are **contract type, tenure, and monthly charges**.  
- Businesses can reduce churn by offering discounts or long-term contracts to at-risk customers.  

---

## 🚀 How to Run
1. Clone this repository or open the notebook in Kaggle.
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
