# Bank Customer Churn Analysis & Prediction

This project focuses on analyzing and predicting **customer churn** using machine learning techniques. We used a cleaned dataset of over 9,900 bank customers and built a model to identify patterns and customers likely to leave.


## Objective

- Analyze key features contributing to customer churn
- Build a predictive model to classify churners vs. non-churners
- Provide actionable business insights to reduce churn


##  Dataset Summary

- **Rows:** 9,998 customers
- **Target Variable:** `Exited` (1 = churned, 0 = retained)
- **Key Features:**
  - Age
  - Credit Score
  - Balance
  - Number of Products
  - Geography (One-hot encoded)
  - Gender (One-hot encoded)
  - Account Activity & Credit Card Status


##  Tools & Technologies

- **Python**
  - Pandas, NumPy, Seaborn, Matplotlib
  - scikit-learn (Random Forest Classifier, train_test_split, metrics)
- **Jupyter Notebook**
- **Git & GitHub**


## Exploratory Data Analysis (EDA)

We explored how churn varies across

- Age groups
- Country/geography
- Account activity
- Number of products
- Account balance

### Key Visuals
- Box plots for `Age`, `Balance`, `EstimatedSalary`
- Churn distribution by region and activity
- Feature importance chart from Random Forest


## Machine Learning Model

We trained a **Random Forest Classifier**, achieving:

- **Accuracy:** 85.25%
- **Precision (Churn class):** 76%
- **Recall (Churn class):** 45%
- **F1 Score (Churn class):** 57%

Model trained on 80% of data, tested on 20%.


## Key Insights

- **Inactive members** (`IsActiveMember = 0`) are significantly more likely to churn.
- **Germany-based customers** show higher churn rates.
- **Senior customers** (aged 50+) are more likely to leave.
- Customers with **only one product** are at higher risk of leaving.

---

## Business Recommendations

1. Improve retention for inactive users with targeted engagement.
2. Launch region-specific campaigns for high-churn areas (e.g., Germany).
3. Offer bundled products or loyalty programs to single-product users.
4. Introduce senior-friendly services or loyalty bonuses for older customers.



