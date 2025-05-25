# Amazon Sales Analysis 🛒

This project presents a statistical analysis of Amazon product data to uncover insights about pricing, discounts, product categories, and customer ratings.
We applied five classical statistical tests to explore relationships between variables and understand customer behavior. The findings offer practical implications for e-commerce marketing and product strategy.
## 📊 Dataset Overview

1,465 Amazon products
Fields: Product Name, Actual Price, Discounted Price, Discount %, Rating, Rating Count, Product Category
Data cleaning steps:
Removed symbols (₹, %, commas)
Converted types (prices, ratings to numeric)
Removed missing/invalid rows
## 🧪 Statistical Methods Used

Purpose	Test Applied
Correlation between discount & rating	Spearman Rank Correlation
Category vs Rating independence	Chi-Square Test
High vs Low Discount Ratings comparison	Welch’s T-Test
Price group vs Rating comparison	ANOVA
Normality of Rating Count	Shapiro-Wilk Test
## 📈 Key Insights

⚠️ High discounts are associated with lower average ratings
💰 Higher price groups tend to receive better ratings
🎯 Product category significantly impacts rating distribution
🧪 Ratings data is not normally distributed
## 🛠 Tools & Technologies

Python
Pandas
Scipy
Seaborn
Jupyter Notebook
## 📂 Files

AmazonSales.ipynb: Full notebook with cleaning, analysis, and visualizations
AmazonSalesReport.pdf: PDF version of the analysis report
🚀 How to Run

Clone the repository
Open AmazonSales.ipynb in Jupyter Notebook
Run all cells to reproduce the analysis
