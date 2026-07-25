# 🧩 Customer Segmentation Analysis (RFM + K-Means Clustering)

**Track:** Data Analytics (Oasis Infobyte SIP)
**Level:** Level 1 — Task 2
**Author:** Udhayveer Singh Jamwal

## 🎯 Objective
Apply clustering algorithms to segment an e-commerce company's customer base into distinct groups based on purchasing behaviour, enabling targeted marketing strategies.

## 🛠️ Tech Stack
- Python
- Pandas
- Scikit-learn (KMeans, StandardScaler)
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Dataset
**Online Retail II (UCI Machine Learning Repository)** — 1,067,371 e-commerce transactions from a UK-based online retailer, spanning December 2009 to December 2011, covering 5,942 unique customers.

Columns: `Invoice`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `Price`, `Customer ID`, `Country`

## 🔍 What's Inside
- Data loading, structural inspection, and cleaning (missing Customer IDs, cancelled invoices, returns, invalid prices removed)
- Descriptive statistics — average purchase value, order frequency, and customer lifetime value
- **RFM Feature Engineering** — Recency, Frequency, Monetary calculated per customer
- Feature standardization using `StandardScaler`
- **K-Means clustering** with the **Elbow Method** to determine the optimal number of clusters (K=4)
- Cluster visualization via scatter plots (Recency vs Monetary, Frequency vs Monetary)
- Cluster profiling with mean RFM values and human-readable segment labels
- Customer count per cluster (bar chart)
- Marketing action recommendations for each customer segment

## 📈 Key Segments Identified
| Segment | Description |
|---|---|
| **Champions** | Recently active, high spenders — reward and retain |
| **Loyal High-Value** | Frequent buyers with high total spend — upsell/cross-sell |
| **At-Risk / Lost** | Long inactive, low spend — win-back campaigns |
| **Occasional / Low-Engagement** | Infrequent buyers — nurture campaigns |

## 🚀 How to Run
1. Open `Customer_Segmentation.ipynb` in Jupyter Notebook, VS Code, or Google Colab.
2. Ensure `online_retail.csv` is in the same directory (or uploaded alongside, if using Colab).
3. Run all cells sequentially. (Note: dataset is large — ~1M rows — so execution may take a minute.)

## ✅ Deliverables
- `Customer_Segmentation.ipynb` — full analysis notebook
- `online_retail.csv` — dataset used
- `README.md` — this file

---
*Submitted as part of the Oasis Infobyte Data Analytics SIP.*
