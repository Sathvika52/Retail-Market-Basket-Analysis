# Retail-Market-Basket-Analysis
 This project focuses on analyzing customer purchase patterns to identify frequently bought products together. This can help retailers optimize product placements, inventory management, and marketing strategies.
 

## Project Overview
This project performs **Market Basket Analysis** on retail transaction data to identify associations between products. The goal is to find patterns in customer purchases using the **Apriori algorithm** and generate **association rules** that can help retailers improve sales, product placement, and marketing strategies.

---

## Dataset
- The dataset contains transactional data of a retail store.
- Each row represents a **single transaction**, listing all items purchased.
- Format: CSV file (`Groceries_data.csv`).

---

## Tools and Technologies
- **Python 3.x**
- **Jupyter Notebook / JupyterLab**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **MLxtend** – Apriori algorithm & association rules
- **Matplotlib / Seaborn** – Visualizations
- **GitHub** – Version control and project sharing

---

## Methodology
1. **Data Preprocessing**
   - Load transactional data
   - Convert transactions into a list format suitable for analysis
2. **Transaction Encoding**
   - Use `TransactionEncoder` to transform data into a one-hot encoded DataFrame
3. **Frequent Itemset Mining**
   - Apply **Apriori algorithm** to identify frequent itemsets
4. **Generate Association Rules**
   - Extract rules based on **support**, **confidence**, and **lift**
5. **Visualization**
   - Visualize the most frequent itemsets and association rules using bar charts and scatter plots

---

## Results
- Frequent itemsets identified patterns such as commonly purchased items together.
- Association rules highlight strong correlations between products.
- Insights can guide marketing strategies and product placement in retail stores.

---


