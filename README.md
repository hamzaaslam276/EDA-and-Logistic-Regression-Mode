# Employee Retention Analysis

This project aims to explore employee retention by analyzing the factors influencing whether employees leave a company or continue to work. The project uses exploratory data analysis (EDA) and logistic regression to gain insights and build predictive models.

---

## Dataset

The dataset used for this project is `HR_comma_sep.csv`, containing the following columns:

- `satisfaction_level`: Employee satisfaction level.
- `last_evaluation`: Last performance evaluation score.
- `number_project`: Number of projects handled by the employee.
- `average_montly_hours`: Average monthly hours worked.
- `time_spend_company`: Number of years spent at the company.
- `Work_accident`: Whether the employee had a work accident (0 or 1).
- `left`: Whether the employee left the company (0 or 1).
- `promotion_last_5years`: Whether the employee was promoted in the last 5 years (0 or 1).
- `Department`: Employee's department.
- `salary`: Employee salary level (low, medium, high).

---

## Objectives

1. **Perform Exploratory Data Analysis (EDA):**
   - Identify variables with a clear impact on employee retention.
   - Visualize the relationship between salary levels and retention.
   - Visualize the relationship between departments and retention.

2. **Build and Evaluate a Logistic Regression Model:**
   - Use the narrowed-down variables to predict employee retention.
   - Measure model accuracy and interpret the results.

---

## Steps

### 1. Data Preprocessing
- Loaded the dataset and checked for missing values.
- Verified data integrity and prepared it for analysis.

### 2. Exploratory Data Analysis

#### Impact of Salary on Retention
- Plotted a bar chart showing the retention rate for different salary levels.

#### Impact of Department on Retention
- Plotted a bar chart showing the retention rate for each department.

### 3. Logistic Regression Model

#### Steps:
1. Converted categorical variables (e.g., salary) to numerical using one-hot encoding.
2. Split the data into training and testing sets.
3. Built a logistic regression model to predict employee retention.
4. Evaluated the model’s accuracy and performance using a confusion matrix.

---

## Results

1. **EDA Insights:**
   - Retention rates are higher for employees with higher salaries.
   - Some departments have significantly lower retention rates.

2. **Model Performance:**
   - **Accuracy:** 78.5%
   - **Confusion Matrix:**
---

## Conclusion

This project demonstrates the use of exploratory data analysis and logistic regression to analyze and predict employee retention. It highlights the importance of salary and department in influencing employee decisions to stay or leave the company.

---

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Author
[Hamza Aslam](https://github.com/HamzaAslam)

