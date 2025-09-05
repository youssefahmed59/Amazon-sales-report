#  Amazon Sales Report Analysis

This project analyzes Amazon sales data to uncover trends, cancellation patterns, and product/category performance.  
The goal is to identify business insights that can help improve sales and reduce cancellations.  

---

##  Dataset
- Source: https://www.kaggle.com/datasets/mdsazzatsardar/amazonsalesreport/data
- Columns include:
  - **Order Date, City, State, Status, Fulfilled-By, Category, Product Name, ASIN, SKU, Amount, Ship Service Level**  
  - Data covers sales, cancellations, and shipping performance.

---

## Analysis & Insights
- **Sales Trends**: Sales were high initially but showed a noticeable drop toward the end.  
- **Categories**: Dupatta category had long periods of zero sales, only picking up in the last month.  
- **Cancellations**:  
  - 23 products showed a **100% cancellation rate**.  
  - Several cities had **zero sales** due to complete cancellations (e.g., Dharuhera, Calicut Medical College, TARBHA).  
- **Fulfillment & Shipping**: Merchant vs. Amazon fulfillment performance compared.  
- **Product & Place**: Identified cities and products with high cancellation rates.  

---

## Tools & Libraries
- Python  
- Pandas (data cleaning & transformation)  
- Matplotlib & Seaborn (visualization)  
- Jupyter Notebook (analysis workflow)  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/amazon-sales-analysis.git
