# 📦 FedEx Global Medical Supply Chain Analysis
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Aniket02102001/fedex-logistics-analysis/blob/main/Aniket_EDA_Submission.ipynb)

## 📊 Project Overview

A comprehensive **Exploratory Data Analysis (EDA)** of FedEx's global medical supply chain operations for delivering HIV/AIDS and antiretroviral (ARV) products to developing countries. This project analyzes shipments to identify operational inefficiencies, cost patterns, and delivery performance metrics.

## 🎯 Business Objectives

1. **Delivery Performance Analysis** - Identify bottlenecks and improve on-time delivery rates
2. **Cost Optimization** - Analyze freight, insurance, and operational costs
3. **Vendor Performance** - Evaluate supplier reliability and efficiency
4. **Route Optimization** - Identify most efficient shipping routes and modes
5. **Risk Assessment** - Analyze delivery delays and supply chain risks

## 📈 Key Insights

| Insight | Impact | Recommendation |
|---------|--------|----------------|
| **Air shipments** have lowest delays but highest costs | Cost vs Speed trade-off | Use air for urgent medical supplies only |
| **South Africa & Nigeria** are top destinations | Allocate more resources to these regions |
| **SCMS for RDC** is most reliable vendor  | Strengthen partnership |
| **August and March** peak season | Plan inventory and capacity accordingly |
| **N/A from RDC shipping terms** most cost-effective | Negotiate better terms with vendors |

## 📁 Dataset Description

- **File:** `SCMS_Delivery_History_Dataset.csv`
- **Records:** 10324 + shipment records
- **Products:** ARV medicines, HIV tests, ACTs, Malaria tests
- **Key Features:** 33 columns including costs, dates, weights, vendors

### Key Columns:
- `Country` - Destination country
- `Shipment Mode` - Air/Truck/Sea
- `Vendor` - Supplier information
- `Product Group` - Medical product category
- `Weight (Kilograms)` - Shipment weight
- `Freight Cost (USD)` - Shipping costs
- `Delivery_Delay` - Days delayed from schedule
- `Total_Cost` - Complete shipment cost

## 🛠️ Tech Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| **Python** | Programming Language | 3.10+ |
| **Pandas** | Data Manipulation | 1.5.3 |
| **NumPy** | Numerical Computing | 1.24.3 |
| **Matplotlib** | Basic Visualizations | 3.7.1 |
| **Seaborn** | Statistical Visualizations | 0.12.2 |
| **Google Colab** | Cloud Execution | - |
| **Git & GitHub** | Version Control | - |
