# Sephora Product Analytics & Machine Learning

**Status:** Ongoing Project

This repository is an ongoing data science project built using the **Sephora Products & Reviews Dataset**. Instead of combining multiple machine learning tasks into a single large notebook, the project is organized into **six independent Jupyter notebooks**, each focusing on a different business problem while using the same dataset.

The goal is to explore different areas of data science and machine learning, including:

- Exploratory Data Analysis (EDA)
- Classification
- Clustering
- Regression
- Business Analytics

Each notebook is designed to be self-contained while following a consistent workflow and coding style.

---

# Repository Structure

```text
sephora-analysis/
│
├── data/
│   ├── products.csv
│   └── reviews.csv
│
├── notebooks/
│   ├── 01_exploratory_data_analysis.ipynb
│   ├── 02_product_success_prediction.ipynb
│   ├── 03_product_clustering.ipynb
│   ├── 04_price_vs_rating_regression.ipynb
│   └── 05_hidden_gems_analysis.ipynb (Bonus)
│
├── Hidden_gems_report.pdf (Power BI report)
├── requirements.txt
├── Project-Outline.md
└── README.md
```

---

# General Notebook Structure

Each notebook follows the same workflow to ensure consistency throughout the project.

## 1. Business Problem

- Define the business objective.
- Explain why solving the problem is valuable.

## 2. Import Libraries

- Import required Python libraries.
- Configure plotting style and random seeds if necessary.

## 3. Load Dataset

- Load the required data.
- Inspect the dataset.

## 4. Data Cleaning & Preprocessing

- Handle missing values.
- Remove duplicates.
- Convert data types.
- Perform feature engineering where needed.

## 5. Exploratory Data Analysis

- Explore variables relevant to the notebook.
- Create visualizations.
- Summarize key insights.

## 6. Machine Learning

- Prepare features.
- Train one or more machine learning models.
- Tune model parameters when appropriate.

## 7. Model Evaluation

- Evaluate performance using appropriate metrics.
- Interpret the results.

## 8. Business Conclusions

- Summarize findings.
- Discuss business implications.
- Suggest future improvements.

---

# Reporting & Communicating Insights

Running the analysis is only half the job — insights only create value once they're communicated in a way stakeholders can act on. Notebooks are the right format for the analytical work itself, but they aren't built for sharing with a business audience.

For the Hidden Gems analysis, the findings were rebuilt as a report in **Power BI** and exported to **[Hidden_gems_report.pdf](Hidden_gems_report.pdf)**, so the results are stakeholder-friendly and easy to distribute.

---

Each notebook is developed independently while contributing to a cohesive portfolio project focused on real-world cosmetic product analytics.