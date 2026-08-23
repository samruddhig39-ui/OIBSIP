# Customer Segmentation Analysis

##  Project Overview

This project performs customer segmentation on an Online Retail dataset using **RFM Analysis** and **K-Means Clustering**.

The goal is to identify different types of customers based on their purchasing behaviour and provide suitable marketing recommendations for each customer segment.

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

##  Dataset

The project uses the **Online Retail dataset**, containing retail transaction information such as:

- Invoice Number
- Product/Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

The original CSV dataset is not included in this repository because of its large file size.

##  Project Steps

1. Load and inspect the dataset
2. Handle missing values and duplicate records
3. Remove cancelled/invalid transactions
4. Calculate total transaction amount
5. Perform RFM Analysis
6. Standardize RFM features
7. Use the Elbow Method to determine the number of clusters
8. Apply K-Means Clustering
9. Profile the customer segments
10. Visualize the customer segments
11. Develop marketing recommendations
12. Summarize the findings and conclusions

## RFM Analysis

RFM stands for:

- **Recency** – How recently a customer made a purchase
- **Frequency** – How frequently a customer makes purchases
- **Monetary** – How much money a customer spends

##  Customer Segments

The analysis identified four customer segments:

- **Regular Customers**
- **Inactive Customers**
- **Loyal High-Value Customers**
- **VIP Customers**

Marketing recommendations are provided for each segment in the notebook.

##  Project Files

```text
DataAnalytics-L1-CustomerSegmentation/
│
├── Customer_Segmentation.ipynb
└── README.md


