# Diabetes Dataset Analysis (SQL-based)

This project uses the [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) to explore factors related to diabetes using **SQL queries inside Databricks Community Edition**.

---

## Project Overview

- **Goal**: Analyze relationships between features like glucose, BMI, age, and diabetes outcomes.
- **Tools Used**: 
  - Databricks Community Edition
  - SQL (with `%sql` magic)
  - Data visualizations (bar and pie charts)

---

## Dataset Details

| Column                | Description                               |
|-----------------------|-------------------------------------------|
| Pregnancies           | Number of times pregnant                  |
| Glucose               | Plasma glucose concentration              |
| BloodPressure         | Diastolic blood pressure (mm Hg)          |
| SkinThickness         | Triceps skin fold thickness (mm)          |
| Insulin               | 2-Hour serum insulin (mu U/ml)            |
| BMI                   | Body mass index                           |
| DiabetesPedigreeFunction | Diabetes pedigree function            |
| Age                   | Age (in years)                            |
| Outcome               | Class variable (0 = Non-diabetic, 1 = Diabetic) |

---

## Key Insights

- Around **35%** of the patients in the dataset are diabetic.
- Diabetic patients tend to have **higher average glucose and BMI**.
- Age also appears to correlate with diabetes outcome.
- Visualizations provide a clear look at health patterns across patient groups.

---

## Visualizations Included

- Pie chart: Distribution of diabetic vs. non-diabetic patients
- Bar charts: 
  - Average glucose by outcome
  - Average BMI by outcome
  - Age distribution among diabetic patients

---

## How to Run

This project was developed in:
- **Databricks Community Edition**
- Notebook exported in `.ipynb` format
- SQL queries written using `%sql` magic commands

To view or run this notebook:
1. Clone the repo or download the `.ipynb` file
2. Open in [Jupyter Notebook](https://jupyter.org/) or import into Databricks
3. View SQL queries and outputs

---

## Next Steps

- Switch to full Databricks edition for machine learning (Python + Spark)
- Train a logistic regression model to predict diabetes outcomes
- Perform missing value imputation and data cleaning

---

## License

This project is for educational use only.  
Dataset provided by UCI Machine Learning Repository.
