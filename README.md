
# 🛒 Retail Sales Data Analysis – Superstore Dataset

This project performs an in-depth analysis of a retail dataset (Superstore) to uncover insights about sales, profit, and regional performance. The objective is to identify trends, evaluate profitability, and suggest data-driven business strategies.

## 🔍 Project Objectives

- Analyze sales and profit patterns across regions, states, and categories
- Identify top and bottom performing locations and product types
- Visualize relationships between discount, sales, and profit
- Present findings using clear and insightful visualizations

## 📁 Dataset

- Source: [Superstore Dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- Fields include: Order Date, Region, State, Sales, Profit, Discount, Category, Sub-Category, etc.

## 🧰 Tools & Libraries

- Python, Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly (optional for interactivity)

## 📊 Key Analyses Performed

- 📌 Total Sales and Profit by Region and State
- 📌 Top 10 States by Sales and Bottom 10 by Profit
- 📌 Sales vs Profit Scatter Plot with Trend Lines (using `sns.regplot` and `sns.lmplot`)
- 📌 Monthly Sales vs Profit Line Chart
- 📌 Profitability Heatmap (Category vs Sub-Category)
- 📌 Impact of Discounts on Profit

## 📈 Sample Visualizations

- Total Sales by Region (Bar Plot)
- Sales vs Profit by Category (Scatter with Trend Lines)
- Sales and Profit Over Time (Line Chart)
- Bottom 10 States by Profit (Horizontal Bar Plot)

## 📌 Key Findings

- The **West region** contributes the highest sales and profit.
- **California** is the top-performing state, while **Texas** and **Illinois** often show high sales with lower profit margins.
- **Furniture** has relatively lower profitability even with decent sales — potentially due to discounts or high return rates.
- **Sales and profit are moderately correlated**, but some high-sale transactions still yield **negative profit**.
- Discounts beyond a certain threshold generally result in loss-making transactions.

## ▶️ How to Run

```bash
git clone https://github.com/yourusername/retail-sales-analysis.git
cd retail-sales-analysis
pip install -r requirements.txt
jupyter notebook
```

## 📜 License

This project is open-source and free to use under the MIT License.
