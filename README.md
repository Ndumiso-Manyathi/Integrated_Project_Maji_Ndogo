# Integrated_Project_Maji_Ndogo

![SQL](https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL-blue?logo=postgresql&logoColor=white) 
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter) 
![Data](https://img.shields.io/badge/Data-60k%20records-success?logo=databricks&logoColor=white) 
![SDGs](https://img.shields.io/badge/UN-SDGs-228B22?logo=unitednations&logoColor=white) 
![License](https://img.shields.io/badge/License-MIT-lightgrey)

Exploring **Maji Ndogo’s database** (60,000+ records) to produce data-driven insights on water access, quality, and pollution using SQL. This repository demonstrates workflows from fundamental queries to advanced analytics and prepares actionable outputs aligned with the **UN Sustainable Development Goals (SDGs)**.

---

## 🌍 A Journey Through Maji Ndogo’s Data  

Maji Ndogo is a fictional community, but its challenges echo those faced in many real regions where water is scarce, polluted or unevenly distributed. At the heart of this project lies a database of more than **60,000 records**, spread across multiple tables, each one carrying pieces of the puzzle: water sources, field visits, pollution records and the people responsible for ensuring access to safe water.  

This repository is not just about writing SQL queries; it is about telling a story through data. From our first steps exploring the schema to the final stage of preparing insights for decision-makers, every query uncovers a new chapter in the unfolding water crisis of Maji Ndogo.

## 📊 Database Schema
Key tables:
- `employee` — field staff and surveyors  
- `location` — towns, provinces, regions  
- `water_source` — wells, taps and source metadata  
- `water_quality` — chemical/biological quality assessments  
- `well_pollution` — contamination incidents and measurements  
- `visits` — site inspections and survey entries  
- `global_water_access` — international comparison metrics

---

## 📖 The Story Unfolds  

We begin by opening the database for the first time. Each is a fragment of the bigger picture. At first, we simply learn the landscape: running **basic SELECT queries**, filtering rows and cleaning anomalies. These early queries are the prologue, teaching us how the data is structured and where its weak points lie.  

As we progress, we zoom into the crisis itself. Using **aggregations and window functions**, we identify which provinces struggle most, which towns rely on unsafe wells, and where pollution is spreading fastest. Patterns begin to emerge, and the data slowly transforms into a narrative about scarcity, inequality and risk.  

The third stage of the journey connects the dots. By joining tables and cross-referencing audit samples, we expose inconsistencies and hidden connections. A polluted well in one town may affect neighbouring regions through shared sources. A single contaminated location can ripple outward, threatening thousands. The SQL here becomes more complex — **joins, subqueries, and common table expressions** but the goal remains the same: clarity.  

Finally, we look forward. Armed with classification techniques, views and optimised queries, we prepare insights that engineers and policymakers could use. Wells are categorised by safety, locations are prioritised for intervention and the tangled story of water in Maji Ndogo is distilled into actionable knowledge.  

---

## Overview
- Navigate relational databases with **basic to advanced SQL**  
- Explore water access challenges through **queries, joins, and aggregations**  
- Use **window functions, subqueries, and views** to extract deeper insights  
- Apply **data cleaning and normalisation** for accuracy and integrity

---

## Project Phases  
1. **Getting Started** – Basic queries & schema exploration  
2. **Water Crisis Analysis** – Aggregations, window functions, cleaning  
3. **Data Narrative** – Joining multiple tables, audit analysis  
4. **Future Outlook** – Subqueries, CTEs, and water source classification
   ---

## Skills Practiced  
- SQL fundamentals (**DDL, DML, Joins, Set Operations**)  
- **Window, numeric, string, and control flow functions**  
- **Normalisation & ERD design**  
- Views for **security & accessibility**  
- Query optimisation & best practices  
