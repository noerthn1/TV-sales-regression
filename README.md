# 📊 TV-sales-regression
Machine learning mini-project using simple linear regression to model the relationship between TV advertising spend and product sales.

This project applies simple linear regression to predict sales based on TV advertising spend using the classic [Advertising dataset] (https://www.kaggle.com/datasets/ashydv/advertising-dataset).

---

 ## 📁 Project Files
- `advertising.csv` — Dataset with TV, Radio, Newspaper advertising budgets and Sales.
- `Advertising.ipynb` — Jupyter Notebook containing:
  - Data loading & exploration
  - Scatter plot of TV spend vs Sales
  - Model training using scikit-learn
  - Interpretation of intercept & slope
  - Sales prediction examples

## Model Equation
Example result :
## Intercept (7.1623) → Baseline sales (in thousands of units) with $0 TV ads.
## Slope (0.05443) → Additional sales (in thousands) for every $1,000 spent on TV ads.

## 📌 How to Run
1. Clone the repo:
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

2. Install dependencies
pip install pandas numpy matplotlib scikit-learn jupyter

3. Open the notebook:
jupyter notebook / python Advertising.ipynb

## 🧠 Insights
1. Positive linear relationship between TV advertising spend and shaving cream sales.
2. Each $1,000 spent on TV ads increases sales by ~54 units.
3.TV ads have a significant impact, but other factors (Radio, Newspaper, seasonality) also matter.
