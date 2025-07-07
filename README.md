# 🏠 Ames Housing - Exploratory Data Analysis

This project performs an Exploratory Data Analysis (EDA) on the Ames Housing dataset, uncovering key patterns and relationships that affect house prices.

---

## 📦 Required Libraries

Make sure to install the following packages before running the notebook:

```bash
pip install pandas matplotlib seaborn jupyter
```

---

## 📁 Project Structure

```
LECTURE 4 - MINI PROJECT
├── data/
│   ├── dataset.csv
│   └── data_description.txt
│
├── images/
│   ├── correlation_heatmap.png
│   ├── price_trend.png
│   ├── grlivarea_vs_price.png
│   ├── boxplot_neighborhoods.png
│   ├── overallqual_vs_price.png
│
├── notebooks/
│   ├── PS.ipynb        # Starter notebook
│   └── PSsol.ipynb     # Final notebook with all analysis
│
├── Ames Housing Dataset.pdf
└── README.md
```

---

## 📊 Analysis Highlights

### 🔹 Correlation Matrix
- A heatmap was created to visualize the correlation between all numerical features.
- `OverallQual`, `GrLivArea`, and `GarageCars` have strong positive correlation with `SalePrice`.

### 🔹 Price Trend Over Time
- A line chart shows average sale prices by `YrSold`.
- Small fluctuations suggest a relatively stable market with a slight downward trend.

### 🔹 Living Area vs Price
- A scatter plot of `GrLivArea` vs `SalePrice` reveals a strong positive relationship.
- Some outliers are present, especially in larger houses with unexpectedly low prices.

### 🔹 Neighborhood Influence
- A boxplot of `SalePrice` by `Neighborhood` shows wide variability.
- Certain neighborhoods consistently command higher prices.

### 🔹 Overall Quality vs Price
- A scatter plot confirms that higher `OverallQual` scores are associated with higher `SalePrice`.

### 🔹 Pivot Tables
- **OverallQual × SaleCondition** → average `SalePrice`
- **OverallCond × YearBuilt** → median `SalePrice`
- **Neighborhood × LotConfig** → average `LotArea`
- **YrSold** → average `SalePrice`

---

## 📌 Notes

- All analysis is conducted in Python using Pandas, Seaborn, and Matplotlib.
- The project is organized for clarity and reproducibility.
- Visualizations are stored in the `images/` directory.