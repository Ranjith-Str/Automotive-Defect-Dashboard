# Project 1 – Automotive Defect Dashboard  
*Phase 2 of 20-Day Analyst Transition Plan*

## 🧰 Tools Used
Python (pandas, numpy) · SQL · Excel · Power BI  

## 🗂️ Workflow Summary
1. **Data Cleaning (Python)**  
   - Removed duplicates, null values, and typo entries  
   - Standardized Defect Type, Supplier, Severity columns  
   - Created final dataset: defect_data_clean_v1.csv  

2. **Data Analysis (SQL)**  
   - Count of defects by type, supplier, and month  
   - Cost impact per defect and monthly trend  

3. **Excel Pivot Insights**  
   - Supplier × Defect Type frequency  
   - Monthly Cost Trend  
   - Severity vs Cost Impact  

4. **Power BI Dashboard**  
   - Defect Count by Type (bar)  
   - Supplier-wise Cost Impact (column)  
   - Monthly Cost Trend (line)  
   - Total Cost & Top Defect KPIs  

## 📊 Key Insights (Jul–Sep 2025)
- **Warp defects:** 160 cases (≈ 32%) → main rework driver  
- **Supplier D:** Highest cost impact ≈ ₹ 122 K  
- **Total defect cost:** ₹ 446 K across 3 months  
- **Trend:** Cost declined Aug → Sep → process improvement visible  

## 💡 Recommendations
- Focus audits on **Warp & Sink Mark** defects  
- Engage **Supplier D** for quality review & tool maintenance  
- Keep monitoring monthly cost trend for continued reduction  

## 📁 Repository Structure
Project1_AutomotiveDefectDashboard/
│
├── Data/
│ ├── defect_data_raw.csv  
│ └── defect_data_clean_v1.csv  
│
├── SQL/
│ └── defect_analysis.sql  
│
├── Excel/
│ └── Defect_Pivot_Insights.xlsx  
│
├── PowerBI/
│ └── Automotive_Defect_Dashboard.pbix  
│
├── Reports/
│ ├── Automotive_Defect_Dashboard.pdf  
│ └── Profiling_Cleaning_Report_v3.pptx  
│
└── README.md  
