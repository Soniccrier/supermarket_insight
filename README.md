📊 Supermarket Sales – Customer Segmentation (EDA + Clustering)

This project explores customer purchasing behavior using the Supermarket Sales dataset.
The goal is to uncover insights through Exploratory Data Analysis (EDA) and create simple customer segmentation using spending patterns.

🔍 Project Overview

Businesses need to understand their customers to improve marketing, promotions, and retention.
In this analysis, I:

Cleaned and prepared the dataset

Explored trends in sales, customer types, and spending patterns

Grouped customers into segments (High Spenders vs Low Spenders) based on total purchase amount

Visualized key patterns to support decision-making

This project demonstrates essential data analyst skills such as data cleaning, EDA, visualization, and basic segmentation.

🧹 Data Preparation

The notebook covers:

Checking for missing values

Handling inconsistent text

Converting data types

Cleaning columns (e.g., dates, numbers)

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

Although total spending is high for both groups, Members spend slightly more, indicating:

Loyalty programs or memberships may be effective

Members could be more consistent buyers

Targeting Members with exclusive offers may increase revenue

This is a simple segmentation approach, but it shows how businesses can categorize customers for better strategy development.

I also observed that:

Profit Margins were small so the supermarket should consider sourcing good from new a new Company or Companies


🛠️ Tools & Technologies

Python

Pandas

Matplotlib / Seaborn

Jupyter Notebook

📁 Project Structure
├─ supermarket_sales.ipynb   # Main analysis notebook
├─ README.md                 # Project documentation
└─ data/                     # Dataset (optional to add)

🚀 How to Run

Clone the repository

git clone https://github.com/soniccrier/supermarket_insight.git


Open Jupyter Notebook

jupyter notebook


Run the notebook: supermarket_sales.ipynb

📚 Future Improvements

Use k-means clustering for deeper segmentation

Add RFM (Recency, Frequency, Monetary) analysis

Build Tableau/Power BI dashboards

Train a predictive model for customer lifetime value

🙌 Author

Mohammed – Data Analyst (Excel | Python | SQL | Power BI)
Passionate about uncovering insights and building real-world data projects.
