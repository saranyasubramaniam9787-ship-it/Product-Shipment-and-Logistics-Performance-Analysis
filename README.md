# Product-Shipment-and-Logistics-Performance-Analysis
Product logistics analytics project focused on shipment performance, delivery delays, sales trends, and supply chain insights using Python and Power BI.

---

## 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Data Source](#-data-source)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [How to Use](#️-how-to-use)

---
## 📊 Project Overview

- Analyze shipment performance by comparing scheduled and actual delivery times across regions and shipping modes.
- Identify high-risk regions and key factors contributing to delivery delays.
Discover top-performing apparel categories, high-demand markets, and seasonal shipping trends.
- Evaluate the impact of delivery performance on sales, profit, customer segments, and payment behavior.
- Provide data-driven recommendations to improve logistics efficiency, reduce delays, and enhance business performance.



## 🗂️ Data Source

- **Source:** https://data.mendeley.com/datasets/kfzvv8bfgr/1
- **Domain:** E-Commerce
- **Timeline:** 2015–2018
- **Dataset Features:** Shipment-related attributes, delivery status, shipping mode, customer information, sales, profit, market, and order-related attributes.


  
## 🛠️ Tools & Technologies

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Visualization:** Matplotlib,Seaborn/Power BI
- **Documentation:** Google Colab Notebook



## 🧹 Data Cleaning & Preparation

The following preprocessing steps were performed:
- Selected only the relevant columns required for shipment and logistics analysis.
- Removed unnecessary and duplicate columns to improve data quality and analysis efficiency.
- Checked and handled missing values where applicable.
- Standardized data formats and ensured consistency across categorical and numerical fields.
- Detected and analyzed outliers to identify unusual shipment and sales patterns.
- Verified data types and converted columns to appropriate formats for analysis.
- Created derived metrics and features required for logistics performance evaluation.


## 🔍 Exploratory Data Analysis (EDA)

The analysis focused on answering the following business questions:

- How efficient are shipments across different regions and shipping modes?
- What is the difference between scheduled and actual delivery times?
- Which regions have the highest late delivery risk?
- How do logistics operations impact sales and profitability?
- Which product categories and markets generate the highest demand?
- What are the patterns in delivery status and shipment delays?
- How do customer segments contribute to overall sales?
- What are the monthly and seasonal shipment trends?

<img width="1046" height="593" alt="image" src="https://github.com/user-attachments/assets/482bb54c-a0c0-4eb6-b276-8de4cfa04f2d" />


## 💡 Key Insights

- Late deliveries represent 54.8% of total orders (98,976 orders), making delivery delays the most significant logistics challenge affecting operational performance.
- The company operates a large-scale logistics network, successfully processing 180,516 orders and shipping 384,076 units across 562 cities.
- Central America and Western Europe contribute the highest shipment volumes but also experience the highest late-delivery risk, indicating regional logistics bottlenecks.
- Standard Class is the most profitable shipping mode, generating approximately $2.51M in profit while handling a significant share of shipments.
- Most delayed shipments were only delayed by one day, suggesting that minor process improvements could substantially enhance delivery performance.
- Higher shipment volumes are strongly associated with increased delivery delays, highlighting the need for better logistics capacity planning, route optimization, and demand forecasting.

## 🚀 Recommendations

- Optimize transportation routes and delivery scheduling to reduce late deliveries and improve overall shipment efficiency.
- Increase logistics capacity and infrastructure in high-demand regions, particularly Central America and Western Europe, to address operational bottlenecks and delivery risks.
- Implement real-time shipment tracking and proactive customer communication to improve delivery visibility, customer satisfaction, and trust.
- Leverage demand forecasting and seasonal planning to allocate inventory, workforce, and logistics resources more effectively during peak demand periods.
- Promote and prioritize Standard Class shipping, as it delivers the highest profitability while maintaining cost-efficient operations.
- Establish continuous logistics performance monitoring using key KPIs such as on-time delivery rate, average delay time, and order cancellation rate to drive ongoing operational improvements.

 
## ⚙️ How to Use

### Requirements

```bash
pip install pandas numpy matplotlib seaborn
```

### Run the Project

1. Download the dataset from the source.
2. Open the Jupyter Notebook.
3. Run all analysis cells sequentially.
4. Explore the Power BI dashboard for interactive insights.
5. Review recommendations and business findings.
