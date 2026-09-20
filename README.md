# Grocery-Run-Analysis
# Grocery-Run-Analysis 🛒📊

An end-to-end data analysis project investigating household grocery consumption patterns, purchasing behaviors, and cost-optimization strategies. This repository processes a dataset tracking purchase timelines, item categories, multi-channel procurement metrics, and payment behavior to extract consumer spending insights.

## 📌 Project Overview
This project provides actionable insights into grocery expenses by analyzing factors that drive spending. It categorizes consumer behavior across various axes (Essential vs. Impulsive, Online vs. In-Store) and tracks the financial impact of dual-tier discount strategies (Online vs. Credit Card offers) across various product domains.

### Key Business Metrics Identified
* **Total Portfolio Expenditure:** ₹6,353.00
* **Average Transaction Ticket Size:** ₹317.65
* **Core Consumption Split:** 65% Essential Goods vs. 35% Impulsive Purchases
* **Procurement Breakdown:** 65% In-Store Shopping vs. 35% Online Delivery Channels

---

## 🛠️ Tech Stack & Skills Highlighted
* **Data Processing & Manipulation:** Excel Pivot Tables / Python Pandas
* **Statistical Modeling:** Categorical distribution analysis, aggregated cost computations
* **Domain Expertise:** E-commerce metrics, consumer behavioral analytics, yield optimization

---

## 📊 Dataset Architecture & Insights

The source dataset captures granular fields tracking transaction details:
`Date` | `Item Name` | `Category` | `Type` | `Qty` | `UOM` | `Price (₹)` | `Online Disc. (₹)` | `CC Disc. (₹)` | `Final Total (₹)` | `Purchase Mode` | `Payment` | `Rating`

### 1. Purchasing Behavior Matrix (Essential vs. Impulsive)
Analysis reveals a clear dominance of functional necessity driving volume, while credit card promotions skew highly toward impulsive household and snack upgrades.

| Buying Type | Transaction Count | Strategic Insights |
| :--- | :---: | :--- |
| **Essential** | 13 | High structural demand across Staples, Grains, and Protein. |
| **Impulsive** | 7 | Triggered heavily by promotional channels or immediate gratification items (Snacks, Frozen Foods). |

### 2. Omnichannel Procurement Strategy

| Channel | Volume Count | Preferred Payment Modes |
| :--- | :---: | :--- |
| **In-Store** | 13 | Strongly correlated with Cash and Credit Card transactions. |
| **Online** | 7 | Dominated by UPI and instant Credit Card gateway settlements. |

### 3. Category Distribution & Quality Indices
The inventory segments across 11 discrete product categories, with Household goods accounting for the highest frequency of distinct items.

```text
Row Labels     Count of Category    Sum of Rating
-------------------------------------------------
Household             3                  10
Beverages             2                   8
Dairy                 2                   9
Fruits                2                   7
Grains                2                  10
Protein               2                   9
Snacks                2                   8
Staples               2                   9
Frozen                1                   1
Produce               1                   5
Pulses                1                   4
-------------------------------------------------
Grand Total          20                  80
```
*(Data Source reference: Pivot Engine Analysis)*

---

## 🚀 Key Data Observations & Takeaways

* **Discount Mechanics Optimization:** The highest net-cost reductions were accomplished via a dual-stack configuration combining upfront product markdowns with backend **Credit Card settlement discounts**.
* **Customer Sentiment Triggers:** High ticket items (e.g., Basmati Rice, Chicken) regularly maintained maximum customer satisfaction scores (Rating: 5), while impulse luxury categories like Frozen Pizza suffered low ratings, indicating a mismatch in price-to-quality expectations.
* **Payment Pipeline Dominance:** Credit cards serve as the primary vehicle for high-velocity and premium spending baskets, outpacing standalone cash reserves 2-to-1.

---

## 📂 Repository Directory
```tree
├── Data/
│   └── Grocery-Run-Analysis.csv     # Raw transactional log data
├── Notebooks/
│   └── analysis_engine.ipynb        # Data preparation and calculation scripts
└── README.md                        # Project documentation
```

---

## 🔧 Installation & Usage Guide

To reproduce the analysis locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Grocery-Run-
   ```

2. **Run Python Analysis Script (Optional):**
   ```bash
   python analysis_engine.py
   ```

---

## 👩‍💻 Author
**Divya Srinivasan**
* GitHub: [@divyaiyer8404-droid](https://github.com)
