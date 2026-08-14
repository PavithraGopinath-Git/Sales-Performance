# ☕ Maven Roasters — Sales Performance & Customer Behavior Analysis

## 📌 Project Overview

This project analyzes transaction-level sales data from **Maven Roasters**, a fictitious coffee shop operating across three locations in New York City: **Astoria, Hell's Kitchen, and Lower Manhattan**.

The objective of this project is to explore sales performance, customer purchasing behavior, product performance, store-level performance, and sales trends using exploratory data analysis (EDA).

The analysis aims to generate actionable business insights that can support decisions related to **inventory management, staffing, marketing, product strategy, and store operations**.

---

## 🎯 Business Problem

Despite having a large volume of transaction data, coffee shop management needs meaningful insights to understand:

* When customers are most likely to make purchases
* Which stores perform best during peak periods
* Which products and categories generate the most revenue
* How purchasing behavior varies throughout the day
* Where staffing and inventory should be prioritized
* Which strategies could improve the performance of lower-performing locations

This project uses historical transaction data to answer these business questions and provide data-driven recommendations.

---

## 📊 Dataset

The dataset contains approximately **149,116 transaction records** covering coffee shop sales from **January to June 2023**.

### Key Variables

| Variable         | Description                            |
| ---------------- | -------------------------------------- |
| Transaction ID   | Unique identifier for each transaction |
| Transaction Date | Date of purchase                       |
| Transaction Time | Time of purchase                       |
| Store ID         | Identifier for the store               |
| Store Location   | Location of the coffee shop            |
| Product Category | Category of the purchased product      |
| Product Type     | Specific type of product sold          |
| Product Detail   | Detailed product information           |
| Quantity         | Number of units sold                   |
| Unit Price       | Price per unit                         |
| Total Sales      | Revenue generated from the transaction |

**Dataset Source:** [Coffee Shop Sales — Kaggle](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales)

---

## 🔍 Analysis Performed

The project focuses on several key areas of business performance.

### 1. Store Performance

Store-level sales and customer activity were analyzed to identify differences in performance between:

* Astoria
* Hell's Kitchen
* Lower Manhattan

### 2. Peak Hour Analysis

Customer purchasing patterns were examined throughout the day to identify periods of high demand.

The analysis identified **8 AM – 10 AM** as a particularly important peak period for customer activity.

### 3. Product Performance

Products and product categories were analyzed to determine which items contribute most significantly to revenue.

The analysis found that **Coffee and Tea categories** are major revenue contributors, while larger-sized drinks also demonstrate strong profitability.

### 4. Customer Purchasing Behavior

Transaction patterns were analyzed to understand when customers purchase products and how demand changes throughout the day.

### 5. Sales Trends

Sales patterns were examined across different time periods to identify demand trends and potential opportunities for operational improvements.

---

## 📈 Key Findings

### 🏪 Store Performance During Peak Hours

The **8 AM – 10 AM** period was analyzed as a major peak period.

| Store           |   Sales | Customers |
| --------------- | ------: | --------: |
| Hell's Kitchen  | $98,025 |    20,633 |
| Lower Manhattan | $88,103 |    17,990 |
| Astoria         | $70,416 |    15,340 |

### Key Insight

**Hell's Kitchen** was the strongest-performing location during peak hours, generating approximately **$98K in sales from more than 20K customer transactions**.

Lower Manhattan followed, while Astoria recorded the lowest sales and customer activity during the analyzed peak period.

---

## 💡 Business Insights

The analysis produced several important insights:

* Customer demand is highest during the **morning hours**, particularly around **8 AM – 10 AM**.
* **Hell's Kitchen** demonstrates the strongest performance during peak hours.
* **Coffee and Tea** are among the most important revenue-generating categories.
* Larger-sized drinks show strong revenue potential.
* Overall revenue distribution across the three locations is relatively balanced, although Hell's Kitchen performs slightly better.
* Peak-hour demand creates a strong need for appropriate staffing and inventory planning.

---

## 🚀 Business Recommendations

Based on the findings, the following recommendations were developed:

### 1. Optimize Peak-Hour Staffing

Increase staffing levels at stores during the busiest morning hours to reduce waiting times and maintain service quality.

### 2. Improve Inventory Planning

Increase stock availability for high-demand products before and during peak periods to reduce the risk of stockouts.

### 3. Learn From High-Performing Stores

Investigate the operational practices, product mix, and customer patterns at Hell's Kitchen and identify strategies that could be applied to other locations.

### 4. Improve Astoria's Performance

Develop targeted promotions and operational improvements to increase customer traffic and sales at Astoria during peak periods.

### 5. Focus on High-Performing Products

Prioritize popular products, particularly Coffee and Tea items and larger-sized beverages, when making inventory and marketing decisions.

### 6. Increase Off-Peak Demand

Use targeted promotions and marketing campaigns during slower periods to distribute customer demand more evenly throughout the day.

### 7. Continue Monitoring Sales Trends

Regular analysis of transaction data can help management improve demand forecasting, staffing decisions, inventory planning, and marketing strategies.

---

## 🛠️ Tools & Technologies

The project uses data analytics and visualization techniques to perform exploratory analysis.

**Tools / Technologies:**

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Exploratory Data Analysis (EDA)
* Data Cleaning
* Data Visualization
* Business Analytics

---

## 📁 Project Structure

```text
Maven-Roasters-Sales-Analysis/
│
├── data/
│   └── coffee_shop_sales.csv
│
├── notebooks/
│   └── Maven_Roasters_Sales_Analysis.ipynb
│
├── visualizations/
│   └── charts_and_figures/
│
├── README.md
│
└── requirements.txt
```

> The project structure may vary depending on the files included in the repository.

---

## 📌 Limitations

Although the analysis provides useful business insights, the dataset has some limitations.

* The dataset covers a relatively limited period of time.
* Customer demographic information is not available.
* Weather conditions are not included.
* Marketing campaign information is not available.
* Customer-level identifiers are not available, limiting deeper customer segmentation.
* External factors such as holidays, events, and competitor activity are not included.

Including these variables in future analyses could improve the accuracy of sales forecasting and customer behavior analysis.

---

## 🔮 Future Improvements

Future versions of this project could include:

* Sales forecasting using time-series models
* Customer segmentation
* Product recommendation analysis
* Store-level performance benchmarking
* Customer retention analysis
* Weather and holiday impact analysis
* Predictive inventory management
* Machine learning models for demand prediction
* Interactive dashboards using Power BI or Tableau

---

## 📚 Conclusion

This project demonstrates how transaction-level sales data can be transformed into actionable business insights.

The analysis identified important patterns in **customer purchasing behavior, store performance, product performance, and sales timing**. In particular, the strong demand during morning peak hours highlights the importance of effective staffing and inventory management.

The results also show that Coffee and Tea products are major contributors to revenue and that high-performing stores such as Hell's Kitchen can provide useful operational benchmarks for other locations.

Although the dataset has limitations, the analysis provides a strong foundation for improving operational efficiency, product planning, marketing strategies, and future sales forecasting.

---

## 🎓 Academic Project

This project was completed as part of my **University Semester Project**, where I applied concepts of **data analysis, exploratory data analysis, data visualization, and business intelligence** to a real-world-style sales dataset.

The project allowed me to practice transforming raw transactional data into meaningful business insights and actionable recommendations.

---

## 👤 Author

**[Your Name]**

Aspiring Data Analyst / Data Scientist

* GitHub: [Your GitHub Profile](https://github.com/your-username)
* LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/your-profile/)

---

⭐ If you find this project useful, feel free to explore the repository and connect with me!
