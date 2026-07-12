# Sephora Product Analytics & Machine Learning

**Status:** Ongoing Project

This repository is an ongoing data science project built using the **Sephora Products & Reviews Dataset**. Instead of combining multiple machine learning tasks into a single large notebook, the project is organized into **six independent Jupyter notebooks**, each focusing on a different business problem while using the same dataset.

The goal is to explore different areas of data science and machine learning, including:

- Exploratory Data Analysis (EDA)
- Classification
- Recommendation Systems
- Natural Language Processing (NLP)
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
│   ├── 03_content_based_recommendation.ipynb
│   ├── 04_review_sentiment_analysis.ipynb
│   ├── 05_product_clustering.ipynb
│   ├── 06_price_vs_rating_regression.ipynb
│   └── 07_hidden_gems_analysis.ipynb (Bonus)
│
├── figures/
│
├── requirements.txt
│
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

# Notebook 01 — Exploratory Data Analysis

## Objective

Develop a comprehensive understanding of the Sephora products and reviews dataset before applying machine learning techniques.

## Possible Analyses

- Rating distribution
- Price distribution
- Brand popularity
- Category analysis
- Most loved products
- Correlation analysis
- Missing values
- Product variation analysis

## Deliverables

- Data visualizations
- Business insights
- Cleaned dataset for later notebooks

---

# Notebook 02 — Product Success Prediction

## Business Question

Can we predict whether a product will become highly rated based on its characteristics?

## Machine Learning Task

Classification

## Possible Features

- Price
- Sale price
- Number of reviews
- Loves count
- Product category
- Brand
- Highlights
- Product availability
- Product variation count

## Possible Models

- Logistic Regression
- Decision Tree
- Random Forest

## Evaluation

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

---

# Notebook 03 — Content-Based Recommendation System

## Business Question

Which products are most similar to a selected product?

## Machine Learning Task

Recommendation System

## Features

- Ingredients
- Product highlights
- Categories
- Product descriptions
- Price
- Rating

## Techniques

- TF-IDF Vectorization
- Cosine Similarity

## Example Output

```text
If you like:

Rare Beauty Soft Pinch Liquid Blush

You may also like:

- Saie Dew Blush
- Dior Rosy Glow
- Tower 28 BeachPlease
```

---

# Notebook 04 — Review Sentiment Analysis

## Business Question

Can customer ratings be predicted from review text?

## Machine Learning Task

Natural Language Processing (NLP)

## Features

- Review title
- Review text

## Techniques

- Text preprocessing
- TF-IDF Vectorization

## Possible Models

- Logistic Regression
- Naive Bayes
- Linear Support Vector Machine (Linear SVM)

## Evaluation

- Confusion Matrix
- Classification Report
- Accuracy
- F1-score

---

# Notebook 05 — Product Clustering

## Business Question

Can products be grouped into meaningful market segments?

## Machine Learning Task

Unsupervised Learning

## Features

- Price
- Rating
- Number of reviews
- Loves count

## Techniques

- StandardScaler
- K-Means Clustering
- Principal Component Analysis (PCA)

## Possible Cluster Examples

- Luxury Favorites
- Budget Gems
- Popular Everyday Products
- Premium but Poorly Rated Products

---

# Notebook 06 — Price vs. Rating Analysis

## Business Question

Does paying more actually lead to higher customer satisfaction?

## Machine Learning Task

Regression

## Features

- Price
- Sale price
- Reviews
- Loves count
- Product characteristics

## Possible Models

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Evaluation

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# Bonus Notebook — Hidden Gems Analysis

## Business Question

Which products deserve greater visibility despite receiving relatively little attention?

Instead of training a traditional machine learning model, this notebook focuses on business analytics by identifying products that appear to be undervalued.

A custom **Hidden Gem Score** may combine factors such as:

- Product rating
- Recommendation rate
- Review helpfulness
- Number of reviews

## Possible Outputs

- Hidden Gems
- Most Overrated Products
- Best Value Products
- Best Affordable Products
- Premium Products Worth Their Price

---

# Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn
- Jupyter Notebook

---

# Learning Objectives

By completing this project, I aim to strengthen my understanding of:

- Data preprocessing
- Feature engineering
- Exploratory Data Analysis
- Supervised Learning
- Unsupervised Learning
- Natural Language Processing
- Recommendation Systems
- Regression
- Model evaluation
- Business-oriented data storytelling

Each notebook is developed independently while contributing to a cohesive portfolio project focused on real-world cosmetic product analytics.

lol