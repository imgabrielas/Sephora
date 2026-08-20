# Sephora Product Analytics & Machine Learning

**Status:** Ongoing Project

This repository is an ongoing data science project built using the **Sephora Products & Reviews Dataset**. Instead of combining multiple machine learning tasks into a single large notebook, the project is organized into **five independent Jupyter notebooks**, each focusing on a different business problem while using the same dataset.

The goal is to explore different areas of data science and machine learning, including:

- Exploratory Data Analysis (EDA)
- Classification
- Clustering
- Regression

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
├── 01 EDA report.pdf (Power BI report)
├── 01 EDA report.pbix
├── 05 Hidden Gems report.pdf (Power BI report)
├── 05 Hidden Gems report.pbix
├── requirements.txt
├── Project-Outline.md
└── README.md
```

---

# General Notebook Structure

Each notebook follows the same workflow to ensure consistency throughout the project.

1. Business Problem
2. Import Libraries
3. Load Dataset
4. Data Cleaning & Preprocessing
5. Exploratory Data Analysis
6. Machine Learning
7. Model Evaluation
8. Business Conclusions

---

# Reporting & Communicating Insights

Running the analysis is only half the job — insights only create value once they're communicated in a way stakeholders can act on. Notebooks are the right format for the analytical work itself, but they aren't built for sharing with a business audience.

| Notebook | PDF Report | Power BI File | Description |
|---|---|---|---|
| 01 - Exploratory Data Analysis | [01 EDA report.pdf](01%20EDA%20report.pdf) | [01 EDA report.pbix](01%20EDA%20report.pbix) | Dataset overview and key EDA insights across products and categories, packaged for stakeholders. |
| 02 - Product Success Prediction | Work in Progress | Work in Progress | Work in Progress |
| 03 - Product Clustering | Work in Progress | Work in Progress | Work in Progress |
| 04 - Price vs Rating Regression | Work in Progress | Work in Progress | Work in Progress |
| 05 - Hidden Gems Analysis | [05 Hidden Gems report.pdf](05%20Hidden%20Gems%20report.pdf) | [05 Hidden Gems report.pbix](05%20Hidden%20Gems%20report.pbix) | Highlights underrated, highly-rated products with low review volume as merchandising opportunities. |

---

Each notebook is developed independently while contributing to a cohesive portfolio project focused on real-world cosmetic product analytics.