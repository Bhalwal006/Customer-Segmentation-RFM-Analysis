# 📊 Customer Segmentation using RFM Analysis

## 📌 Project Overview

Customer Segmentation is a powerful marketing strategy that helps businesses understand customer purchasing behavior and improve customer retention.

This project uses **RFM (Recency, Frequency, Monetary) Analysis** to segment customers based on their transaction history. The analysis identifies high-value customers, loyal customers, new customers, and customers at risk of churning, enabling businesses to make data-driven marketing decisions.

---

## 🎯 Project Objectives

- Clean and preprocess retail transaction data
- Calculate RFM (Recency, Frequency, Monetary) metrics
- Segment customers based on purchasing behavior
- Analyze customer spending patterns
- Build an interactive Power BI dashboard
- Provide actionable business recommendations

---

## 🗂️ Dataset Information

The project uses a retail transaction dataset containing customer purchase records.

### Dataset Features

| Column | Description |
|---------|-------------|
| CustomerID | Unique customer identifier |
| ProductID | Unique product identifier |
| Quantity | Number of items purchased |
| Price | Price per item |
| TransactionDate | Date of transaction |
| PaymentMethod | Payment mode used |
| StoreLocation | Store where purchase was made |
| ProductCategory | Category of purchased product |
| DiscountApplied(%) | Discount applied on purchase |
| TotalAmount | Final transaction amount |

---

# 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Power BI
- GitHub

---

# 📊 Project Workflow

```
Retail Transaction Dataset
          │
          ▼
Data Cleaning & Preprocessing
          │
          ▼
Exploratory Data Analysis (EDA)
          │
          ▼
RFM Calculation
          │
          ▼
Customer Segmentation
          │
          ▼
Business Insights
          │
          ▼
Power BI Dashboard
          │
          ▼
Marketing Recommendations
```

---

# 📈 RFM Analysis

## Recency (R)

Measures how recently a customer made a purchase.

- Lower Recency = Better Customer

---

## Frequency (F)

Measures how often a customer purchases.

- Higher Frequency = Better Customer

---

## Monetary (M)

Measures how much money a customer spends.

- Higher Monetary Value = Higher Customer Value

---

# 👥 Customer Segments

The customers were divided into the following segments:

- 🏆 Champions
- 💚 Loyal Customers
- 🌱 Potential Loyalists
- 🆕 New Customers
- ⚠️ At Risk Customers
- ❌ Lost Customers

---

# 📊 Power BI Dashboard

The dashboard includes:

- KPI Cards
  - Total Customers
  - Total Revenue
  - Total Transactions
  - Average Order Value

- Customer Segment Distribution

- Revenue by Customer Segment

- Product Category Analysis

- Payment Method Analysis

- Store Location Analysis

- Frequency vs Monetary Scatter Plot

- Interactive Slicers

- Marketing Recommendation Table

---

# 💡 Key Business Insights

- Champions generate the highest revenue and should be retained with premium offers.
- Loyal customers contribute consistent revenue and should be rewarded through loyalty programs.
- New customers show strong growth potential with proper onboarding campaigns.
- At-risk customers require targeted retention strategies before they become inactive.
- Lost customers can be re-engaged through personalized win-back campaigns.

---

# 📢 Marketing Recommendations

| Customer Segment | Recommendation |
|------------------|----------------|
| Champions | VIP membership and exclusive offers |
| Loyal Customers | Loyalty rewards and personalized discounts |
| Potential Loyalists | Cross-selling and product recommendations |
| New Customers | Welcome offers and onboarding campaigns |
| At Risk Customers | Email campaigns and special discounts |
| Lost Customers | Win-back campaigns with promotional offers |

---

# 📁 Project Structure

```
Customer-Segmentation
│
├── data.ipynb
├── Customer_Segmentation_Dashboard.pbix
├── Retail_Transaction_Dataset.csv
├── RFM_Output.csv
├── Images
│   ├── Dashboard.png
│   ├── Customer_Segments.png
│   ├── Revenue_By_Segment.png
│   ├── Product_Category.png
│   ├── Payment_Method.png
│   ├── Scatter_Plot.png
│ 
│
└── README.md
```

---

# 🚀 Future Improvements

- Implement machine learning-based customer segmentation.
- Predict customer churn using classification models.
- Automate dashboard refresh with scheduled data updates.
- Deploy an interactive dashboard using Power BI Service.

---

# 👨‍💻 Author

**Harshit Bhalwal**

Data Analyst | Python | SQL | Power BI | Data Visualization

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
