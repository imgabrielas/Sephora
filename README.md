# Sephora Product Analytics & Machine Learning

**Status:** Ongoing Project

A data science portfolio project built on the **Sephora Products & Reviews Dataset**. Rather than one large notebook, the work is split into **five independent Jupyter notebooks**, each tackling a different business problem on the same underlying data — covering EDA, classification, clustering, regression, and business analytics.

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
├── 03_product_clustering.ipynb
├── 04_price_vs_rating_regression.ipynb
├── 05_hidden_gems_analysis.ipynb 
│
├── 01 EDA report.pdf
├── 01 EDA report.pbix
├── 05 Hidden Gems report.pdf
├── 05 Hidden Gems report.pbix
│
├── Project-Outline.md
├── requirements.txt
└── README.md
```

> `data/` is git-ignored — download the dataset separately and place the CSVs there before running the notebooks.

## Notebooks

| #  | Notebook | Task | Business Question |
|----|----------|------|--------------------|
| 01 | Exploratory Data Analysis | EDA | What does the products & reviews data actually look like? |
| 02 | Product Success Prediction | Classification | Can we predict whether a product will be highly rated? |
| 03 | Product Clustering | Unsupervised Learning | Can products be grouped into meaningful segments? |
| 04 | Price vs. Rating Regression | Regression | Does paying more lead to higher satisfaction? |
| 05 | Hidden Gems Analysis (bonus) | Business Analytics | Which underrated products deserve more visibility? |

Full details for each notebook — objectives, candidate features, models, and evaluation metrics — are in [Project-Outline.md](Project-Outline.md).
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
| 01 - Exploratory Data Analysis | [01 EDA report.pdf](01%20EDA%20report.pdf) | [01 EDA report.pbix](01%20EDA%20report.pbix) | Dataset overview and key EDA insights across products and categories, packaged for stakeholders. |
| 02 - Product Success Prediction | Work in Progress | Work in Progress | Work in Progress |
| 03 - Product Clustering | Work in Progress | Work in Progress | Work in Progress |
| 04 - Price vs Rating Regression | Work in Progress | Work in Progress | Work in Progress |
| 05 - Hidden Gems Analysis | [05 Hidden Gems report.pdf](05%20Hidden%20Gems%20report.pdf) | [05 Hidden Gems report.pbix](05%20Hidden%20Gems%20report.pbix) | Highlights underrated, highly-rated products with low review volume as merchandising opportunities. |

---

## Technologies

Python, Pandas, NumPy, Matplotlib, Plotly, Scikit-learn, Jupyter.
