# Amazon Sales Analysis 🛒

This project presents a statistical analysis of Amazon product data to uncover insights about pricing, discounts, product categories, and customer ratings.

We applied five classical statistical tests to explore relationships between variables and understand customer behavior. The findings offer practical implications for e-commerce marketing and product strategy.

---

## 📊 Dataset Overview

- 1,465 Amazon products
- Fields: Product Name, Actual Price, Discounted Price, Discount %, Rating, Rating Count, Product Category
- Data cleaning steps:
  - Removed symbols (₹, %, commas)
  - Converted types (prices, ratings to numeric)
  - Removed missing/invalid rows

---

## 🧪 Statistical Methods Used

- Spearman Rank Correlation – to check relationship between discounted price and rating  
- Chi-Square Test – to test independence between product category and rating group  
- Welch’s T-Test – to compare ratings of high vs. low-discount products  
- One-Way ANOVA – to compare ratings across price groups  
- Shapiro-Wilk Test – to check if rating counts follow a normal distribution

---

## 📈 Key Insights

- High-discount products tend to receive lower ratings  
- Higher-priced items are generally rated better  
- Product category significantly impacts average rating  
- Rating counts are not normally distributed

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- Scipy  
- Seaborn  
- Jupyter Notebook  

---

## 📂 Files in This Repo

- `AmazonSales.ipynb` – Jupyter Notebook with full analysis  
- `AmazonSalesReport.pdf` – Formal report summarizing the results

---

## 🚀 How to Run

1. Clone the repository  
2. Open `AmazonSales.ipynb` in Jupyter Notebook  
3. Run all cells to reproduce the analysis

---

📌 Feel free to fork or star ⭐ the repo if you found it useful!
