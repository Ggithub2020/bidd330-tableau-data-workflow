# 📊 A02_TableauWorkflow – Tableau Desktop  
**Course**: BIDD 330 A Sp 25  
**Author**: Girum  
**Date**: April 17, 2025  

---

## 📁 Repository Structure  

This repository includes:

- Tableau packaged workbook (`.twbx`)  
- README documentation  
- GitHub Wiki (linked)  

---

## 🔍 Assignment Description  

This project introduces Tableau Desktop fundamentals using a structured class dataset hosted on a Microsoft SQL Server. The assignment involves:

- Connecting to a live database  
  ![📸 Data Connection Screenshot](screenshots/data_connection.png)

- Building a proper data model  
  ![📸 Data Model Screenshot](screenshots/data_model.png)

- Creating simple calculated fields  
- Developing a dashboard layout  
- Exporting the final workbook as `.twbx`  
- Documenting work in a GitHub Wiki  

---

## 🧩 Data Model Overview  

Connected tables:

- `vw_Fact_Covid_2023`  
- `vw_Fact_Unemployment`  
- `Dim Country`  
- `Dim Date`  
- `Dim State`  

**Key Joins:**

- `FactCovid2023` to `Dim Country`, `Dim Date`, and `Dim State`  
- `FactUnemployment` to `Dim Date`  

These joins enable effective slicing of data by region, time, and location for meaningful analysis.

---

## 🧮 Calculated Fields  

- **COVID Records by State**  
- **Unemployment Records by State**  

Each fact table includes a COUNT measure to validate data presence and layout design.

---

## 📊 Dashboard Summary  

The Tableau dashboard includes two sheets:

- COVID record counts by state  
- Unemployment record counts by state  

This forms the foundation for future enhancements in visualization and interactivity.

---

## ❓ Prepared Questions for Tableau Expert  

1. How can we optimize Tableau dashboards for large datasets?  
2. Best practices for user experience and layout?  
3. Favorite storytelling techniques in Tableau?  

---

## ⚖️ Power BI vs Tableau (Quick Comparison)

| Feature           | Tableau         | Power BI             |
|------------------|------------------|-----------------------|
| Visual Freedom   | High             | Moderate              |
| Learning Curve   | Moderate–High    | Beginner–Friendly     |
| Ecosystem        | Focused          | Microsoft-integrated  |
| Modeling         | Moderate         | Advanced              |
| Pricing          | Premium          | Budget-friendly       |

---

## ✅ Deliverables  

- [x] Packaged Workbook `.twbx`  
- [x] Dashboard Layout  
- [x] Technical Write-up  
- [x] GitHub Wiki Updated  
- [x] Zipped folder uploaded to Canvas  
