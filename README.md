# 📊 Sales Plant Dashboard

![PBIDesktop_O10q60VgCO](https://github.com/user-attachments/assets/2f82c9c5-84a2-4b72-80a4-e8ac5e0737f0)

## 📌 Overview
The **Sales Plant Dashboard** provides a comprehensive view of sales performance across multiple dimensions, including **country**, **product type**, **accounts**, and **time periods**.  
It helps business teams and management **monitor trends, track KPIs, and identify key growth opportunities** while managing potential risks.

---

## 🚀 Key Features

### **1. KPI Highlights**
| Metric          | Value    | Description |
|-----------------|---------|-------------|
| **GP%**        | 39.8%   | Gross Profit Percentage relative to total sales |
| **S_PYTD**     | 17.21M  | Total sales for the same period in the previous year |
| **S_YTD**      | 3.57M   | Total accumulated sales in the current year |
| **YTD vs PYTD** | -13.65M | Difference between current and previous year sales *(negative indicates decline)* |

---

### **2. Sales YTD by Country**
- Visualized using a **Treemap**.
- Highlights each country's contribution to total sales.
- **China** and **Brazil** contribute the most, while **Croatia** and **Hungary** contribute less.

---

### **3. YTD vs PYTD by Month**
- **Chart Type:** Waterfall
- **Purpose:** Tracks month-to-month sales performance vs last year.
- **Color Codes:**
  - 🟥 **Red:** Sales decrease  
  - 🟩 **Green:** Sales increase  
  - 🟦 **Blue:** Total cumulative variance
- Significant declines are observed in **March** and **April**.

---

### **4. Sales by Product Type & Month**
- **Chart Type:** Stacked Bar + Line Chart
- **Product Types:**
  - Indoor *(Blue)*
  - Landscape *(Yellow)*
  - Outdoor *(Orange)*
- Includes a **comparison line** for **S_PYTD**.
- Insights: Peak sales occurred in **Q1**, followed by a **sharp drop from May onwards**.

---

### **5. Sales vs GP% by Account**
- **Chart Type:** Scatter Plot
- Shows the relationship between **Sales YTD** and **Gross Profit Percentage** across accounts.
- **X-axis:** Total sales per account (S_YTD)  
- **Y-axis:** GP%  
- Most accounts maintain a **GP% between 50% and 65%**, with sales volumes concentrated in the **5K – 20K** range.

---

## 📈 Key Insights
- **Sales YTD = 3.57M** vs **Sales PYTD = 17.21M** → **significant year-over-year decline**.
- **China** and **Brazil** remain the strongest-performing markets.
- **Indoor products** dominate overall sales, while **Landscape** and **Outdoor** products underperform.
- **Q2 (April – June)** shows the **largest drop in sales**.
- Despite lower volumes, **most accounts maintain healthy profit margins (>55% GP%)**.

---

## 💡 Business Recommendations

Based on the insights from this dashboard, here are actionable recommendations to improve sales performance:

### **1. Focus on High-Performing Countries (China & Brazil)**
- Allocate more marketing budget and sales resources to these regions to **leverage strong market demand**.
- Introduce localized campaigns to **maintain competitive advantage**.

### **2. Improve Underperforming Regions**
- Countries like **Croatia, Hungary, and Portugal** contribute less to overall sales.
- Conduct market research to **identify customer needs** and **adapt pricing strategies** to drive growth.

### **3. Optimize Product Portfolio**
- **Indoor products** perform best → maintain inventory and expand offerings in this segment.
- For **Landscape** and **Outdoor** products, run **promotional campaigns** and **bundle strategies** to boost sales.

### **4. Address Q2 Sales Decline**
- The sharp drop between **April and June** requires investigation:
  - Evaluate **seasonal demand patterns**.
  - Review **distribution channels** for possible bottlenecks.
  - Launch targeted campaigns ahead of Q2 next year to **mitigate future dips**.

### **5. Leverage High-Margin Accounts**
- Since most accounts generate **>55% GP%**, offer **loyalty rewards** or **volume-based discounts** to **retain and grow these accounts**.
- Focus on accounts with **lower sales but high profitability potential** to increase revenue efficiently.

---

## 🛠️ Tools & Technologies
- **Power BI** — For interactive dashboard development  
- **Data Sources:** Sales datasets from multiple regions and product categories  
- **Techniques Used:** KPI tracking, variance analysis, product segmentation, account-level profitability analysis

---

## 🎯 Dashboard Objectives
- Monitor **real-time sales performance**.
- Identify **top-performing countries, products, and accounts**.
- Track **monthly and quarterly sales trends**.
- Provide **data-driven insights** to optimize business strategies.

---

## 📂 Repository Structure
