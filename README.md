# About Portfolio Projects
## [Global market analysis project(link)](Global_market_analysis.ipynb)

### 📘 Project Description

This project analyzes the sales data of a global company that operates both **offline (regular stores)** and **online**.  
The dataset consists of three files:

- **`events.csv`** — contains sales data over several years  
- **`products.csv`** — includes product categories and their codes  
- **`countries.csv`** — includes information about countries, regions, and their codes  

The main goal of the project is to **clean, analyze, and visualize** the data to uncover **valuable business insights** about the company’s performance and market behavior.

---

### 🧹 Data Quality and Structure

- The data is **clean and consistent**, with no anomalies or extreme outliers.  
- The distribution of the **Units Sold** variable is **balanced** (mean ≈ median), indicating the absence of skewness.  
- Price-related indicators show a **shift toward higher-value goods**, which is expected in global markets.

---

### 💰 General Business Indicators

| Metric | Value |
|--------|--------|
| Number of Orders | **1,328** |
| Total Units Sold | **6.58 million** |
| Countries | **45** |
| Product Categories | **12** |
| Total Revenue | **1.70 billion** |
| Total Expenses | **1.20 billion** |
| Total Profit | **0.50 billion** |
| Average Order Value | **≈ 1.28 million** |

---

### 📦 Sales by Product Category

- The **most profitable** categories are **Cosmetics** and **Office Supplies**.  
- **Household** and **Fruits** also demonstrate strong performance.  
- **Beverages** and **Snacks** show the **lowest revenue**, suggesting the need to review pricing or marketing strategies.  
- Profitability does not always correlate directly with revenue — some categories gain more profit through **higher margins rather than volume**.

---

### 🌍 Geographical Analysis

- **Europe** is the company’s **most profitable region** — a key market focus.  
- **Portugal** leads in total revenue.  
- The **Top 10 countries** by revenue also include **Andorra, Bulgaria, Belgium, and Austria**, indicating stable market positions across Europe.

---

### 🛒 Sales by Channel

- Revenue is **evenly distributed** between sales channels (online/offline).  
- The profit structure is **balanced**, showing that no channel is overly dominant or unprofitable.

---

### 🚚 Logistics and Shipping Speed

- Average shipping time by category: **20–27 days**, considered acceptable.  
- **Personal Care** and **Household** products are delivered **fastest**.  
- **Cereal** and **Office Supplies** have **longer delivery times**.  
- **Hungary** shows the **longest shipping duration (~32 days)**, while most countries average **27–28 days**.  
- Across regions, shipping times remain **relatively stable**.

#### 📉 Profit vs. Shipping Time

No clear correlation was found between **profit** and **delivery speed**, suggesting that logistics speed is **not a major profitability driver**.

---

### 🧭 Conclusions & Next Steps

-  **Focus** marketing and sales efforts on **Europe**, especially **Portugal**.  
-  **Expand and promote** high-profit categories — *Cosmetics* and *Office Supplies*.  
-  **Optimize logistics** in countries with longer delivery times (e.g., *Hungary*).  
-  **Reassess low-performing categories** (*Beverages*, *Snacks*) — consider reducing their share or replacing them with more profitable products.

---

### 📊 Tools & Technologies Used

- **Python** (pandas, matplotlib, seaborn)


---
---
## [Online Store Sales Analytics Project(link)](Online_store_sales_analytics.ipynb)

### 📘 Project Overview


**Goal:**  
To showcase data analytics skills through real-world tasks — from loading and cleaning data to finding insights and visualizing them.

---

### 🧩 Dataset Description

The dataset contains information about:
- Online store **sales** (daily revenue data);
- **Customers** and registration details;
- **Products** and categories;
- **Traffic sources** and user sessions.

The period under review is **from January 27, 2021, to November 1, 2020** (reverse order in source data).

---

### 🔍 Exploratory Data Analysis (EDA)

### General Findings:
- The distribution of daily sales is **slightly right-skewed** — the mean is slightly higher than the median.
- **Mode < Median < Mean**, indicating that most typical sales days are around **200–250K**.
- Standard deviation ≈ **100K** — the data is **quite variable**, with unstable daily sales dynamics.

---

### 📈 Seasonality & Trends

- Clear **sales peaks before winter holidays**, followed by a drop during the holidays.  
- Indicates typical **holiday shopping behavior** and suggests planning promotions before holidays.

---

### ⚠️ Outliers

Two days — **December 8, 2020**, and **December 10, 2020** — showed **abnormally high sales**.  
Possible causes:
- Large marketing campaigns or discount events;
- Launch of a popular product;
- Seasonal rush effect.

---

### 🏷️ Product Analysis

- A **small group of product categories** generates the majority of revenue.
- Recommended focus:  
  - Strengthen **top 5 categories** through targeted marketing and stock optimization.  
  - Reassess or replace low-performing products.

---

### 🌍 Regional Analysis

- **Sales concentration:** USA, India, and Canada dominate.  
- Potential growth markets: countries with lower coverage or engagement — consider expansion or localized promotions.

---

### 📲 Traffic Channels

| Channel | Observation |
|----------|--------------|
| **Organic Search** | High traffic and conversion — strong SEO performance |
| **Paid Search** | Effective ads, strong contribution to total sales |
| **Direct** | Good loyalty and repeat customers |
| **Social Search** | Lower correlation with others — requires deeper analysis |

---

### 💻 Devices

- Majority of sessions occur on **mobile devices**.  
- **Desktop users** still form a significant share.  
- Recommendation: ensure **full site adaptability** across all device types.

---

### 👥 Accounts and User Behavior

- Only a **small share of sessions are from registered users**.  
- Encouraging registration could:
  - Increase customer retention;
  - Enable personalized recommendations;
  - Boost long-term revenue.

---

### 📊 Statistical Insights

- **Sales correlation between continents:**  
  ρ ≈ 0.61–0.67 → global trends (e.g., seasonality, campaigns) influence all regions.
- **Traffic channel correlations:**  
  Organic, Paid, and Direct — ρ ≈ 0.76 → common patterns.  
  Social — ρ ≈ 0.38–0.42 → acts independently.
- **Normality test (D’Agostino-Pearson):**  
  Sales **do not follow a normal distribution**, important for further statistical modeling.

---

### 🧭 Conclusions & Recommendations

- Focus campaigns **before holidays** to leverage demand growth.  
- **Analyze Social Search** channel — potential for optimization.  
- **Encourage user registrations** — improve loyalty and personalization.  
- **Expand presence** beyond top-performing countries.  
- Maintain **cross-device optimization** to support mobile and desktop users.  
- Leverage **SQL + Python + Tableau** integration for continuous monitoring and data-driven decisions.

---

### 📊 Tools & Technologies Used

-  **SQL** — for data extraction from a relational database.  
-  **Python** — for exploratory, statistical, and correlation analysis.  
-  **Tableau** — for creating interactive dashboards and visualizations.
