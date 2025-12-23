# 🌈 Slum vs Sanitation in Bangladesh (Bivariate Map)

![Slum vs Sanitation Map](https://github.com/karmok3r/Slum-vs-Sanitation-BD/raw/main/Slum%20vs%20Sanitation.png)

> Bivariate choropleth of **Urban Slum Population (%)** vs **Basic Sanitation Service (%)** for districts of Bangladesh, using official 2022 census indicators. [file:1]

---

## 🧊 Project Overview

This repository explores the spatial relationship between **housing vulnerability** and **sanitation access** in Bangladesh using a **bivariate map**:

- **Field 1 (X‑axis):** Urban_Slum_Percentage  
- **Field 2 (Y‑axis):** Basic_Sanitation_Percentage  

Districts are classified into a 3×3 color grid to highlight where **high slum prevalence overlaps with low sanitation coverage**, helping to pinpoint **critical intervention zones** for WASH and urban upgrading projects. [file:1]

---

## 🧮 Data & Source

- **Dataset:** Bangladesh Population & Housing Census **2022**  
- **Provider:** Bangladesh Bureau of Statistics (BBS)  
- **Indicators used:**
  - SDG 11.1.1 – Urban slum population (%) by district  
  - SDG 6.2.1a – Basic sanitation service (%) by district

All indicators were extracted and pre‑processed from the official national report tables for district‑level analysis. 

---

## 🗺️ Tech Stack

[![ArcGIS Pro](https://img.shields.io/badge/ArcGIS%20Pro-2.x-2e7ae5?logo=arcgis&logoColor=white)](https://pro.arcgis.com/)  

- **GIS Software:** ArcGIS Pro – Bivariate Colors symbology for quantitative mapping 
- **Data Handling:** CSV/Excel (SDG indicators by district)  
- **Version Control:** Git + GitHub for reproducible cartography workflows 

---

## 📁 Repository Structure
Slum-vs-Sanitation-BD/
├─ Bivariant Map 1.gdb
├─ Bivariant Map 1.atrx
├─ GpMessages
├─ ImportLog
├─ Index
├─ SDG Indicator BBS.pdf
├─ SDG Indicators.xlsx
├─ Slum Sanitation.csv
├─ Slum Sanitation.xlsx 
├─ Slum Vs Sanitation.aprx
├─ Slum vs Sanitation.png 
└─ README.md


---

## 🔍 Map Interpretation

- **Upper‑left colors:**  
  High **Urban_Slum_Percentage** + Low **Basic_Sanitation_Percentage**  
  → Highest priority districts for integrated slum upgrading and sanitation projects.

- **Lower‑right colors:**  
  Low slum share + High sanitation coverage  
  → Relatively resilient urban conditions.

- **Middle classes:**  
  Transitional contexts where either slum reduction or sanitation expansion is in progress.

This visualization supports **evidence‑based targeting** of WASH, housing, and urban resilience interventions aligned with **SDG 6** and **SDG 11**. 

---

## 💬 Citation

If you use this map or workflow, please cite:

> Bangladesh Bureau of Statistics (BBS). *Population and Housing Census 2022: National Report, Volume I.* Dhaka, Bangladesh. 

