# 🎬 Movie Data Correlation Analysis Project

## 🧠 Overview
This project explores the relationships between various movie-related variables using Python and statistical analysis techniques. I used a dataset containing movie metadata to identify patterns in production, ratings, revenue, and popularity. The goal was to evaluate the strength of these relationships and avoid common statistical mistakes, like correlating non-numeric or categorical nominal data.

## 🔧 Tools & Libraries
- Python (Jupyter Notebook)
- pandas, matplotlib, seaborn
- numpy, scipy
- scikit-learn (for preprocessing)
- statsmodels

## 📈 Key Features
- **Correlation Analysis**: Computed Pearson correlation for numerical variables (e.g., budget, revenue, vote average).
- **Data Cleaning**: Removed or transformed invalid or non-numeric columns before analysis.
- **Visualizations**: Heatmaps, pair plots, and bar charts to support analysis.
- **Statistical Insight**: Avoided incorrect correlation assumptions by excluding nominal categorical data like genre names or production companies from numeric correlation calculations.

## 📊 Key Insights
- Strong positive correlation between **budget** and **revenue**.
- Moderate correlation between **vote count** and **popularity**.
- No significant correlation between genre or production company and numeric outcomes (properly excluded from analysis).

## 📁 Files
- `Movie Portfolio Project.ipynb`: Jupyter Notebook with full code and analysis
- `data/`: (Optional) Directory for any CSV files if included
- `README.md`: Project documentation
- `Dashboard.png`: (If applicable) Visual summary of findings
