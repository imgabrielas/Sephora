# Sephora Product Analytics & Machine Learning

**Status:** Ongoing Project

A data science portfolio project built on the **Sephora Products & Reviews Dataset**. Rather than one large notebook, the work is split into **multiple Jupyter notebooks**, each tackling a different business problem on the same underlying data — covering EDA, classification, clustering, regression, business analytics, and an ongoing NLP/sentiment-analysis track.

## Repository Structure

```text
Sephora/
│
├── .git/
├── .idea/
├── .venv/
├── data/
│   └── (local dataset files; typically product and review CSVs)
│
├── 01_exploratory_data_analysis.ipynb
├── 02_product_success_prediction.ipynb
├── 03_product_clustering.ipynb
├── 04_price_vs_rating.ipynb
├── 05_hidden_gems_analysis.ipynb
├── 06_sentiment_analysis.ipynb
│
├── Reports pdf/
│   ├── Report 01 EDA.pdf
│   ├── Report 04 Product categories.pdf
│   └── Report 05 Hidden Gems.pdf
│
├── Reports PowerBI/
│   ├── Report 01 EDA.pbix
│   ├── Report 04 Product categories.pbix
│   └── Report 05 Hidden Gems.pbix
│
├── Project-Outline.md
├── README.md
├── requirements.txt
└── .gitignore
```

> `data/` is intended to hold the raw CSV files used by the notebooks. If the dataset is not already present locally, download it first and place the relevant files in this folder before executing the analysis.

## Notebooks

| #  | Notebook | Task | Business Question |
|----|----------|------|--------------------|
| 01 | Exploratory Data Analysis | EDA | What does the products & reviews data actually look like? |
| 02 | Product Success Prediction | Classification | Can we predict whether a product will be highly rated? |
| 03 | Product Clustering | Unsupervised Learning | Can products be grouped into meaningful segments? |
| 04 | Price vs. Rating Regression | Regression | Does paying more lead to higher satisfaction? |
| 05 | Hidden Gems Analysis (bonus) | Business Analytics | Which underrated products deserve more visibility? |
| 06 | Sentiment Analysis (ongoing) | NLP / Text Mining | How do customer reviews express sentiment, and what themes drive positive or negative feedback? |

Full details for each notebook — objectives, candidate features, models, and evaluation metrics — are in [Project-Outline.md](Project-Outline.md).

## NLP & Sentiment Analysis (Ongoing)

This project also includes an active text-analysis track focused on customer reviews. The goal is to move beyond numerical ratings and interpret the actual language used by shoppers when describing products. I plan to analyze review text using a combination of traditional and modern NLP techniques, with a focus on extracting sentiment, key themes, and actionable product insights.

The intended workflow includes:

- review text preprocessing with NLTK and spaCy
- topic and phrase analysis using Gensim for unsupervised text modeling
- sentiment classification using Hugging Face transformer models and classical NLP baselines
- feature extraction and comparison across brands, categories, and product lines
- business-oriented interpretation of positive and negative review themes

This part of the project is intended to answer questions such as: Which products receive the strongest praise? What complaints recur most often? How do sentiment patterns differ across product categories and skincare concerns? These insights are expected to complement the structured product analytics by turning raw customer reviews into useful business intelligence.

## Setup

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

# Reporting & Communicating Insights

Running the analysis is only half the job — insights only create value once they're communicated in a way stakeholders can act on. Notebooks are the right format for the analytical work itself, but they aren't built for sharing with a business audience.

| Notebook | PDF Report | Power BI File | Description |
|---|---|---|---|
| 01 - Exploratory Data Analysis | [Report 01 EDA.pdf](Reports%20pdf/Report%2001%20EDA.pdf) | [Report 01 EDA.pbix](Reports%20PowerBI/Report%2001%20EDA.pbix) | Dataset overview and key EDA insights across products and categories, packaged for stakeholders. |
| 04 - Price vs Rating Regression | [Report 04 Product categories.pdf](Reports%20pdf/Report%2004%20Product%20categories.pdf) | [Report 04 Product categories.pbix](Reports%20PowerBI/Report%2004%20Product%20categories.pbix) | Category-level breakdown of pricing, ratings, and review volume across the product catalog. |
| 05 - Hidden Gems Analysis | [Report 05 Hidden Gems.pdf](Reports%20pdf/Report%2005%20Hidden%20Gems.pdf) | [Report 05 Hidden Gems.pbix](Reports%20PowerBI/Report%2005%20Hidden%20Gems.pbix) | Highlights underrated, highly-rated products with low review volume as merchandising opportunities. |

---

## Technologies

Python, Pandas, NumPy, Matplotlib, Plotly, Scikit-learn, Jupyter, spaCy, Gensim, NLTK, and Hugging Face Transformers.
