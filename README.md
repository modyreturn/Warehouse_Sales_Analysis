# 📊 Warehouse Sales Data Analysis

A data analysis project focused on exploring warehouse and retail sales trends using real-world beverage distribution data.

## 📌 Project Overview

This project analyzes a dataset containing monthly warehouse and retail sales records for various types of beverages (e.g., wine, beer, liquor). The goal is to extract meaningful insights about sales performance, supplier contributions, seasonal trends, and correlations between different sales channels.

The dataset includes the following fields:

- Year & Month
- Supplier name
- Item code and description
- Item type (Wine, Beer, Liquor, etc.)
- Retail sales, Retail transfers, and Warehouse sales values

## 🔍 Key Insights

From the exploratory data analysis, we uncovered several important findings:

- **Wine dominates** sales by volume and revenue.
- **Warehouse sales** significantly outperform retail sales in most months.
- Strong **seasonality** with peak sales occurring in **July**.
- High correlation (**0.98**) between **retail transfers** and **retail sales**, suggesting that optimizing transfers can boost direct consumer sales.
- Top suppliers like **CROWN IMPORTS** and products like **CORONA EXTRA** drive the majority of sales.

> See the [notebooks](notebooks/) folder for detailed EDA and visualizations.

## 📈 Visualizations Included

- Time series plots of monthly sales trends
- Bar charts of top suppliers and products
- Correlation matrix between sales metrics
- Pie chart showing item type distribution
- Seasonal decomposition of sales data
- Scatter plots and heatmaps for deeper insights

## 🛠️ Technologies Used

- **Python**: Core language
- **Pandas**: For data manipulation and cleaning
- **NumPy**: For numerical operations
- **Matplotlib & Seaborn**: For visualization
- **Statsmodels**: For time-series decomposition
- **Scikit-learn / Scipy**: For statistical tests and clustering

## 📁 Project Structure

```
warehouse-sales-analysis/
│
├── data/               # Raw and cleaned datasets
├── notebooks/            # Jupyter Notebooks with EDA and visualizations
├── README.md             # This file
└── requirements.txt      # Python package dependencies
```

## 📦 Installation

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/warehouse-sales-analysis.git
   ```

2. Navigate into the directory:
   ```bash
   cd warehouse-sales-analysis
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open the notebooks from the `notebooks/` folder and start exploring!

## 📎 Requirements

Make sure you have the following installed:

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
statsmodels
jupyter
```

You can install all via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter
```

## ✅ Contributing

Contributions are welcome! If you'd like to improve the analysis, add new visualizations, or enhance the documentation, feel free to open an issue or submit a pull request.

-----
