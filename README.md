# Supermarket Sales – Customer Segmentation (EDA + Clustering)

## 📌 Project Overview
This project performs **exploratory data analysis (EDA)** on a supermarket sales dataset to uncover customer purchasing patterns, trends, and insights. Additionally, it demonstrates **basic customer segmentation** using spending behavior to support business decision-making.

## 📂 Dataset Description
The dataset (`supermarket_sales.csv`) contains supermarket transaction records with columns like:  
- Invoice_ID  
- Branch  
- Customer_Type  
- Gender  
- Product_Category  
- Unit_Price  
- Quantity  
- Total  
- Date  
- Payment_Method  

## 🛠 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 📑 Project Workflow
1. **Data Loading & Inspection**  
2. **Data Cleaning & Preparation**  
   - Handling missing values  
   - Fixing inconsistent text  
   - Converting data types  
3. **Descriptive Statistics & EDA**  
   - Customer type distribution  
   - Revenue contribution by customer type  
   - Branch performance comparison  
   - Sales trends over time  
   - Correlation analysis (unit price, quantity, total)  
4. **Customer Segmentation**  
   - Grouping customers into High Spenders vs Low Spenders based on total purchase amount  
5. **Visualization & Insights**  

## 📊 Example Insights
- Members spend slightly more than normal customers, indicating effective loyalty programs  
- Targeting Members with exclusive offers may increase revenue  
- Profit margins are small; consider sourcing products from alternative suppliers  
- Branch performance and sales trends provide actionable operational insights  

**Customer Segmentation Example**:

| Customer Type | Total Spending | Segment       |
|---------------|----------------|---------------|
| Member        | 164,223.44     | High Spender  |
| Normal        | 158,743.30     | Low Spender   |

## ▶️ How to Run the Project
1. Clone the repository:  
   ```bash
   git clone https://github.com/soniccrier/supermarket_insight.git
jupyter notebook

Run the notebook: supermarket_sales.ipynb

## 📌 Future Improvements
- Implement **k-means clustering** for more advanced customer segmentation  
- Include **RFM (Recency, Frequency, Monetary) analysis** to identify valuable customers  
- Build **interactive dashboards** using Power BI or Tableau for better visualization  
- Train **predictive models** to estimate customer lifetime value and forecast sales  

## 🙌 Author
**Mohammed – Data Analyst (Excel | Python | SQL | Power BI)**  
Driven and analytical problem solver. Passionate about uncovering patterns in data and building real-world projects that support business decision-making.
