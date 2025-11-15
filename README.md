📊 Supermarket Sales – Customer Segmentation (EDA + Clustering)

This project explores customer purchasing behavior using the Supermarket Sales dataset.
The goal is to uncover insights through Exploratory Data Analysis (EDA) and create simple customer segmentation based on spending patterns.


🔍 Project Overview

Understanding customer behavior is crucial for improving marketing, promotions, and retention.
In this analysis, I:

Cleaned and prepared the dataset

Explored trends in sales, customer types, and spending patterns

Segmented customers into High Spenders vs Low Spenders

Visualized key buying patterns to support data-driven decisions

This project demonstrates essential data analyst skills such as data cleaning, EDA, visualization, and basic segmentation.


🧹 Data Preparation

The data preparation process includes:

Checking for missing values

Handling inconsistent text

Converting data types

Cleaning numeric and date fields


📈 Exploratory Data Analysis (EDA)

Key analysis performed:

Customer type distribution

Revenue contribution by customer type

Branch performance comparison

Sales trends over time

Correlation between unit price, quantity, and total value


🧩 Customer Segmentation

Segmentation was done using total spending by each customer type.

Customer Type	Total Spending	Segment
Member	164,223.44	High Spender
Normal	158,743.30	Low Spender



🧠 Insight

Although both groups generate high spending, Members spend slightly more, suggesting:

Loyalty programs may be effective

Members could be more consistent buyers

Targeted promotions for Members may increase revenue

Additional observation:

Profit margins are small, so the supermarket should consider sourcing products from new suppliers to improve profitability.


🛠️ Tools & Technologies

Python

Pandas

Matplotlib / Seaborn

Jupyter Notebook


📁 Project Structure
├── supermarket_sales.ipynb     # Main analysis notebook
├── README.md                   # Project documentation
└── data/                       # Dataset (optional to add)


🚀 How to Run

Clone the repository

git clone https://github.com/soniccrier/supermarket_insight.git


Open Jupyter Notebook

jupyter notebook


Run the notebook:
supermarket_sales.ipynb


📚 Future Improvements

Apply k-means clustering for deeper segmentation

Add RFM (Recency, Frequency, Monetary) analysis

Build Tableau/Power BI dashboards

Train a predictive model for customer lifetime value



🙌 Author

Mohammed – Data Analyst (Excel | Python | SQL | Power BI)
Passionate about uncovering insights and building real-world data projects.
