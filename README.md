#  Vendor Performance Analysis – Retail Inventory & Sales

###  Summary  
Analyzed vendor performance, profitability, and inventory efficiency to support **data-driven purchasing, pricing, and inventory management**. Built using **SQL, Python, and Power BI**, the project provides actionable insights into vendor dependency, bulk purchasing impact, and slow-moving stock challenges.

---

##  Project Overview  
Retail companies often face challenges such as **vendor over-dependency, unsold inventory, and inefficient pricing strategies**. This project applies **data analytics and visualization** to identify inefficiencies and recommend strategies for improved profitability and operational efficiency.

---

##  Problem Statement  
- Over-dependence on a small set of vendors increases risk.  
- Unsold inventory ties up working capital and storage costs.  
- Profit margins and bulk purchasing impact need validation.  
- Management lacks a clear dashboard to monitor vendor performance.  

---

##  Dataset  
- **Vendor Sales & Purchases Data** (simulated for analysis)  
- Tables included: `vendor_sales_summary`, `product_info`, `inventory_stock`  
- Size: ~100k+ records  

---

## 🛠️ Tools & Technologies  
- **SQL** – Data extraction, ETL pipeline, query optimization (CTEs, filtering)  
- **Python** – EDA, statistical tests (pandas, matplotlib, scipy)  
- **Power BI / Plotly Dash** – Interactive dashboards & visual storytelling  
- **Excel** – Initial data validation and cleaning  

---

##  Methods  
1. **Data Cleaning & ETL**: Built SQL pipeline, reduced processing time by ~40% using CTEs.  
2. **EDA & Visualization**: Identified negative profit entries, outliers, vendor dependencies.  
3. **Hypothesis Testing**: Compared profit margins between high- and low-performing vendors (t-test).  
4. **Segmentation**: Classified brands/vendors into high-margin low-sales vs high-sales low-margin.  
5. **Dashboard Development**: Created KPIs, scatter plots, and comparative visuals for decision-makers.  

---

##  Key Insights  
- **65.7% of purchases** depend on top 10 vendors → high supply chain risk.  
- **$2.71M in unsold inventory** tied up, lowering cash flow and profitability.  
- **Bulk purchasing** reduced unit cost by **72%**, but requires efficient inventory management.  
- **198 brands** showed low sales but high margins → growth opportunity via promotions/marketing.  
- **Low-performing vendors** (CI: 40.44–42.62%) had higher margins than top vendors (CI: 30.74–31.61%), suggesting premium pricing but low sales volumes.  

---

##  Dashboard  
- **Vendor Overview**: Purchase contribution, dependency risk.  
- **Brand Performance**: High-margin vs low-margin classification.  
- **Inventory Turnover**: Unsold stock & slow-moving items.  
- **Bulk Purchase Impact**: Cost reduction vs profit analysis.  
- **Profitability Comparison**: CI analysis of high vs low performers.  

<img width="1024" height="592" alt="Dashboard" src="https://github.com/user-attachments/assets/a623969b-cf40-44b6-b4ac-c4b96e5ad9b2" />

---

##  Results & Conclusion
- **Built SQL ETL pipelines** handling 1M+ rows, reducing processing time by **~40%** using optimized CTEs and filters.  
- **Analyzed vendor data with Python**, uncovering **$2.71M in unsold stock**, **65.7% dependency on top vendors**, and **72%   unit cost savings** from bulk purchases.  
- **Developed Power BI dashboards** to visualize KPIs such as **profit margins (-∞ to 91.5%)** and **stock turnover (up to     274.5x)**, enabling data-driven strategic sourcing decisions.

---

##  Future Work
- **Automate ETL pipeline** with Airflow or dbt.  
- **Deploy dashboard** via Power BI Service or Streamlit/Plotly Dash app.  
- **Incorporate forecasting models** for demand and inventory turnover.  
- **Expand analysis** to include customer purchase behavior for holistic insights. 
