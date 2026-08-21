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
├── Report 01 EDA.pdf (Power BI report)
├── Report 01 EDA.pbix
├── Report 04 Product categories.pdf (Power BI report)
├── Report 04 Product categories.pbix
├── Report 05 Hidden Gems.pdf (Power BI report)
├── Report 05 Hidden Gems.pbix
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
| 01 - Exploratory Data Analysis | [Report 01 EDA.pdf](Report%2001%20EDA.pdf) | [Report 01 EDA.pbix](Report%2001%20EDA.pbix) | Dataset overview and key EDA insights across products and categories, packaged for stakeholders. |
| 04 - Price vs Rating Regression | [Report 04 Product categories.pdf](Report%2004%20Product%20categories.pdf) | [Report 04 Product categories.pbix](Report%2004%20Product%20categories.pbix) | Category-level breakdown of pricing, ratings, and review volume across the product catalog. |
| 05 - Hidden Gems Analysis | [Report 05 Hidden Gems.pdf](Report%2005%20Hidden%20Gems.pdf) | [Report 05 Hidden Gems.pbix](Report%2005%20Hidden%20Gems.pbix) | Highlights underrated, highly-rated products with low review volume as merchandising opportunities. |

---

Each notebook is developed independently while contributing to a cohesive portfolio project focused on real-world cosmetic product analytics.