
# 🏠 Ames Housing Data Analysis

This project presents an Exploratory Data Analysis (EDA) on the Ames Housing Dataset.  
It explores patterns, correlations, and pricing trends across various housing features.

---

## 📊 Main Features

- Correlation matrix heatmap for numeric variables  
- Trend of average sale price by year  
- Scatter plot: Living Area vs. Sale Price  
- Boxplot: Neighborhoods and Sale Prices  
- Pivot tables:
  - Quality × Condition → Average Price
  - Condition × Year Built → Median Price
  - Lot Area by Neighborhood and Lot Config
  - Sale Price per Year

All analysis is in the notebook: `notebooks/ames_housing_analysis.ipynb`.

---

## 📦 Required Packages

Install the following packages before running the notebook:

```bash
pip install pandas matplotlib seaborn jupyter
```

---

## 🗂️ Project Structure

```
ames-housing-analysis/
│
├── notebooks/
│   └── ames_housing_analysis.ipynb     # Main notebook
│
├── data/
│   └── dataset.csv                     # Ames Housing dataset
│
├── images/
│   ├── correlation_heatmap.png
│   ├── avg_price_trend.png
│   ├── scatter_grlivarea_saleprice.png
│   ├── boxplot_neighborhood.png
│   ├── overallqual_saleprice.png
│   └── pivot_tables.png
│
└── README.md                           # This file
```

---

## 💡 Highlights

- Sale price is strongly correlated with overall quality and living area  
- Significant price variation across neighborhoods  
- Multi-dimensional insights revealed through pivot tables