# Sephora Product Analytics & Machine Learning

**Status:** Ongoing Project

A data science portfolio project built on the **Sephora Products & Reviews Dataset**. Rather than one large notebook, the work is split into **seven independent Jupyter notebooks**, each tackling a different business problem on the same underlying data — covering EDA, classification, recommendation systems, NLP, clustering, regression, and business analytics.

## Repository Structure

```text
Sephora/
│
├── data/
│   ├── product_info.csv
│   └── reviews.csv
│
├── 01_exploratory_data_analysis.ipynb
├── 02_product_success_prediction.ipynb
├── 03_content_based_recommendation.ipynb
├── 04_review_sentiment_analysis.ipynb
├── 05_product_clustering.ipynb
├── 06_price_vs_rating_regression.ipynb
├── 07_hidden_gems_analysis.ipynb        (bonus)
│
├── Project-Outline.md
├── requirements.txt
└── README.md
```

> `data/` is git-ignored — download the dataset separately (see [Dataset](#dataset)) and place the CSVs there before running the notebooks.

## Notebooks

| # | Notebook | Task | Business Question |
|---|----------|------|--------------------|
| 01 | Exploratory Data Analysis | EDA | What does the products & reviews data actually look like? |
| 02 | Product Success Prediction | Classification | Can we predict whether a product will be highly rated? |
| 03 | Content-Based Recommendation | Recommender System | Which products are most similar to a given product? |
| 04 | Review Sentiment Analysis | NLP | Can ratings be predicted from review text? |
| 05 | Product Clustering | Unsupervised Learning | Can products be grouped into meaningful segments? |
| 06 | Price vs. Rating Regression | Regression | Does paying more lead to higher satisfaction? |
| 07 | Hidden Gems Analysis (bonus) | Business Analytics | Which underrated products deserve more visibility? |

Full details for each notebook — objectives, candidate features, models, and evaluation metrics — are in [Project-Outline.md](Project-Outline.md).

Each notebook follows the same workflow: business problem → imports → data loading → cleaning/preprocessing → EDA → modeling → evaluation → business conclusions.

## Dataset

This project uses the [Sephora Products and Skincare Reviews dataset](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews) (product info + customer reviews). Download `product_info.csv` and `reviews.csv` and place them in `data/`.

## Setup

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

## Technologies

Python, Pandas, NumPy, Matplotlib, Plotly, Scikit-learn, NLTK, Jupyter.

## Learning Objectives

This project is built to strengthen practical skills in data preprocessing, feature engineering, EDA, supervised and unsupervised learning, NLP, recommendation systems, regression, model evaluation, and business-oriented data storytelling — using a single, realistic dataset across a variety of real-world problem types.
