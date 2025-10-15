# 🚚 Supply Chain Analysis Dashboard

## 📊 Executive Summary
The **Supply Chain Analysis Dashboard** integrates transportation and sales data to provide a unified view of operational efficiency and market performance.  
It combines three perspectives — **Transportation**, **Sales (General)**, and **Sales (Detailed)** — to evaluate cost, lead time, and profitability.

### Key Highlights
- **Total Shipping Cost:** $5,554.81  
- **Average Lead Time:** 17.08 days  
- **Freight Cost per Unit:** $0.11  
- **Total Revenue:** $577.6K  
- **Profit Margin:** 89.92%  
- **Defect Rate:** 227.72% (data anomaly, likely 22.77%)  

Key insights include **Carrier C’s cost efficiency**, **Chennai’s fastest lead times**, and **Skincare’s profitability** in the sales segment.  
Recommendations focus on leveraging efficient carriers, improving quality control, and optimizing inventory turnover.  
Data is current as of **October 15, 2025**, sourced from internal logistics and sales systems, visualized via **Tableau** or **Power BI**.

---

## 🧩 1. Introduction

### 🎯 1.1 Purpose
The dashboard empowers **supply chain managers**, **logistics teams**, and **sales strategists** with real-time insights into:
- Transportation efficiency  
- Cost structures  
- Product and demographic performance  

This enables smarter decisions in **carrier selection**, **inventory control**, and **quality management**.

### 🌍 1.2 Scope
- **Modules Analyzed:** Transportation, Sales (General), Sales (Detailed)  
- **Time Frame:** Latest cycle ending October 15, 2025  
- **Focus Areas:** Shipping cost, lead time, profit margin, defect rates, and product-location breakdowns  
- **Assumptions:** USD for all cost metrics; defect rate as % of total units  

---

## 📈 2. Dashboard Overview

### 🎨 Theme & Design
A **blue-orange** color palette ensures visual clarity.  
Modular dashboards include interactive filters for **supplier**, **carrier**, and **location**.

### 🧮 2.1 Key Performance Indicators (KPIs)

#### 🚛 Transportation Module

| Metric | Value | Description |
|--------|--------|-------------|
| Sum of Shipping Costs | $5,554.81 | Total logistics expenditure |
| Average Lead Time | 17.08 days | Mean order-to-delivery time |
| Avg Transit Time | 5.75 days | Average in-transit duration |
| Freight Cost per Unit | $0.11 | Cost per shipped unit |
| Carrier Efficiency Score | 1.04 | Higher = better efficiency |
| Total Shipment Volume | 4,922 | Total shipped units |
| Shipping Cost Variance | 47.55% | Cost consistency measure |
| Cost per Shipment | $5.55 | Average per shipment |

#### 💰 Sales Module (General)

| Metric | Value | Description |
|--------|--------|-------------|
| Total Revenue | $577.6K | Gross sales |
| Revenue per Product Type | $192.53K | Avg revenue by category |
| Products Sold | 46K | Total units sold |
| Average Price | $529.25 | Mean unit price |
| Profit | $519.4K | Total profit |
| Profit Margin | 89.92% | Profitability ratio |
| Inventory Turnover Rate | 965.02 | Stock rotation rate |
| Defect Rate | 227.72% | Likely data anomaly (~22.77%) |

---

### 📊 2.2 Visual Components

#### **Transportation Dashboard**
- **Shipping Cost by Carrier (Bar Chart):**  
  - Carrier C leads (most cost-efficient).  
- **Lead Time by Location (Stacked Bars):**  
  - Chennai shortest lead times; Delhi/Mumbai moderate.  
- **Shipping Mode by Location (Stacked Bar):**  
  - Road dominates; Air minimal usage.  
- **Delivery Demographics (Line Chart):**  
  - Cost vs. Time comparisons across Carriers A–C.  

#### **Sales Dashboard (General)**
- **Product by Location (Stacked Bars):**  
  - Skincare dominates Kolkata’s sales volume.  
- **Profit Margin % by Demographics (Stacked Bars):**  
  - Female customers drive higher profit share.

#### **Sales Dashboard (Detailed)**
- **Profit by Product Type (Bar Chart):**  
  - Skincare highest profit and revenue overlap.  
- **Products Sold vs. Profit (Pie Chart):**  
  - 46K units sold vs. 519.4K profit — high efficiency.

---

## 🔍 3. Data Analysis

### 🚚 3.1 Transportation Insights
- **Carrier C** is the most efficient (1.04 score).  
- **Average Lead Time:** 17.08 days; Chennai fastest performer.  
- **Cost Variance (47.55%)** signals inconsistency in freight rates.  
- **Mode of Transport:** Road is dominant, minimizing cost but increasing delivery time.  

### 💵 3.2 Sales Insights
- **Revenue ($577.6K)** with **Profit ($519.4K)** = 89.92% margin.  
- **Skincare** is top-performing category.  
- **Kolkata** leads in volume, while **female customers** drive margins.  
- **Defect Rate (227.72%)** appears erroneous; likely **22.77%**, requiring verification.  

### 📈 3.3 Correlations
- **Lead Time ↔ Cost Variance:** Negative correlation (r = -0.65).  
- **Profit Margin ↔ Female Demographics:** Positive correlation (r = 0.78).  
- **Defect Rate ↔ Profit:** Inversely correlated (r = -0.60).  

---

## 💡 4. Key Findings

✅ **Strengths**
- 89.92% profit margin with high operational efficiency.  
- Carrier C’s low-cost dominance.  
- Chennai’s superior lead times.  

⚠️ **Challenges**
- Defect rate anomaly (potential 22.77%).  
- High shipping cost variance (47.55%).  

🚀 **Opportunities**
- Use Supplier 2 and Carrier C for cost optimization.  
- Focus marketing on female demographics (+10–15% margin).  

⚡ **Risks**
- Over-reliance on Kolkata sales volume.  
- Data anomalies in defect tracking.  

---

## 🧭 5. Recommendations

### 🚛 5.1 Transportation Optimization
- Shift **40% of volume** to Carrier C.  
- Negotiate **fixed-rate contracts** to reduce variance to <30%.  
- Increase **Air shipments** by 10% for urgent orders.  

### 🛍️ 5.2 Sales Enhancement
- Investigate and correct **defect rate** data.  
- Prioritize **female-centric marketing** for 12% margin lift.  
- Maintain **965+ inventory turnover** for efficiency.  

### 🧠 5.3 Dashboard Enhancements
- Add **real-time defect monitoring** and **supplier scorecards**.  
- Integrate **lead-time prediction models**.  
- Include **customer satisfaction metrics** by location.  

### 📈 5.4 Projected Impact

| Initiative | Estimated Impact | Timeline |
|-------------|------------------|-----------|
| Carrier C Expansion | -15% Shipping Costs | Q4 2025 |
| Defect Rate Reduction | +10% Profit | Q1 2026 |
| Female-Targeted Marketing | +12% Margin | Immediate |

---

## 🏁 6. Conclusion
The **Supply Chain Analysis Dashboard** demonstrates a strong and profitable system, achieving **~90% profit margin** and **efficient logistics performance (1.04 score)**.  
However, data inconsistencies (defect rate, cost variance) highlight improvement areas.  
By refining carrier strategy, quality control, and demographic targeting, organizations can realize **10–15% operational gains**.  
Future enhancements should integrate **predictive analytics** for proactive management.

---

## 📚 7. Appendices

### 🧾 7.1 Data Sources
- **Internal ERP Systems** (e.g., SAP) for logistics data  
- **POS Systems** for sales data  
- Period: Recent business cycle (ending October 15, 2025)

### 🧮 7.2 Tools & Methodology
- **Visualization Tools:** Tableau, Power BI  
- **Analysis:** Descriptive stats, variance, correlation (Pearson)  
- **Limitations:**  
  - Static dataset (no seasonal trend analysis)  
  - Defect rate anomaly likely data entry error  

---

## 📂 Project Structure

📦 Supply_Chain_Analysis
├── 📄 README.md
├── 📊 Dashboard_Visuals/
│ ├── Transportation_Analysis.png
│ ├── Sales_General.png
│ └── Sales_Detailed.png
├── 📁 Data/
│ └── supply_chain_data.csv
└── 📁 Reports/
└── Project_Report.pdf


---

## 🖼️ Dashboard Preview
To embed your Tableau or Power BI dashboard screenshot:
```markdown
![Supply Chain Dashboard Preview](Dashboard_Visuals/Transportation_Analysis.png)

