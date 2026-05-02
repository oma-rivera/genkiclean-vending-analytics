## Sample Visualization
<img width="1321" height="622" alt="Captura de pantalla 2026-05-02 a la(s) 2 27 05 p m" src="https://github.com/user-attachments/assets/5117c230-1043-4d6f-9179-08f1cc54a061" />



# GenkiClean Vending Analytics

## Project Overview

This repository contains data analytics projects focused on GenkiClean's vending machine business model.

The objective is to use Python, Pandas, and data visualization to transform commercial and operational data into actionable business insights.

The projects analyze sales performance, product rotation, inventory behavior, refill planning, stockout exposure, and vending machine operations.

---

## Projects Included

### 1. Sales Distribution & Performance Analysis

This analysis explores vending machine sales performance across products, locations, and time periods.

It focuses on:

- Sales distribution
- Product performance
- Location-level performance
- Revenue behavior
- Commercial insights

[Open Sales Analysis Notebook](notebooks/01_sales_distribution_analysis.ipynb)

---

### 2. Inventory Operations Analysis

This analysis explores daily inventory behavior across GenkiClean vending machines.

It focuses on:

- Daily liters dispensed
- Product rotation
- Refill behavior
- Reorder risk
- Stockout exposure
- Machine-level performance
- City and location-type analysis

[Open Inventory Operations Notebook](notebooks/02_inventory_operations_analysis.ipynb)

---

## Inventory Operations Analysis — Key Results

The inventory operations analysis reviewed one full year of vending machine inventory data.

### Dataset Scope

- 183,960 daily inventory records
- 72 vending machines
- 7 products
- 8 cities
- 6 regions
- Full-year period: January 1, 2025 to December 31, 2025

### Key Findings

- The vending network dispensed 773,274.75 liters during the year.
- Average daily consumption reached 2,118.56 liters.
- Cloro was the highest-rotation product, with 147,862.16 liters dispensed.
- Detergente multiusos generated the highest stockout exposure, with 24,069 stockout minutes.
- Total stockout exposure reached 77,028 minutes, equivalent to approximately 1,283.8 hours.
- The operation recorded 18,721 reorder risk events.

---

## Business Recommendations

Based on the analysis, GenkiClean should:

1. Prioritize high-rotation and high-risk products such as Cloro and Detergente multiusos.
2. Use reorder risk as an early warning signal for refill planning.
3. Adjust refill frequency by product, machine, city, and location type.
4. Monitor stockout minutes as a weekly operations KPI.
5. Use location-level demand to support future vending machine expansion decisions.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Sheets

---

## Repository Structure

```text
genkiclean-vending-analytics/
│
├── README.md
│
├── notebooks/
│   ├── 01_sales_distribution_analysis.ipynb
│   └── 02_inventory_operations_analysis.ipynb
│
├── images/
│
└── data/
