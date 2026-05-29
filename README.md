# Olist Logistics Audit

## Project Overview

This project analyzes delivery performance in the Olist Brazilian E-commerce dataset.

The goal is to identify:

1. Delivery delay patterns
2. Customer satisfaction impact
3. Geographic logistics issues
4. Business insights from shipping performance

The analysis was performed using Python, Pandas, Matplotlib, Seaborn, and Jupyter Notebook.



## Executive Summary

This project investigates how delivery performance affects customer satisfaction across Olist's e-commerce operations in Brazil.

After cleaning and merging order, review, and customer datasets, delivery delays were calculated and categorized into On Time, Late, and Super Late deliveries. The analysis found that 93.23% of delivered orders arrived on or before the estimated delivery date, while delayed deliveries received significantly lower customer review scores.

Regional analysis also revealed that some states experienced much higher delay rates than others, suggesting that logistics challenges are concentrated in specific regions rather than being a nationwide issue.



## Key Findings

* 93.23% of delivered orders arrived on time.
* 6.77% of delivered orders arrived late.
* Customer satisfaction decreased as delivery delays increased.
* On-time deliveries averaged a review score of 4.29/5.
* Late deliveries averaged a review score of 2.99/5.
* Super-late deliveries averaged a review score of 1.75/5.
* States such as AL, MA, and SE recorded the highest percentages of delayed deliveries.



## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Git
* GitHub
* Google Looker Studio



## Project Links

**Dashboard:**
https://datastudio.google.com/s/in9ZWpWtomk

**Notebook (.ipynb):**
https://github.com/mawuenabenjamin/olist-logistics-audit/blob/main/notebooks/olist_logistics_audit.ipynb

**Notebook HTML Export:**
https://github.com/mawuenabenjamin/olist-logistics-audit/blob/main/notebooks/olist_logistics_audit.html

## Presentation:
https://github.com/mawuenabenjamin/olist-logistics-audit/blob/main/presentation/Olist_Logistics_Audit_Presentation.pptx



## Project Structure


olist-logistics-audit/
├── data/
├── notebooks/
│   ├── olist_logistics_audit.ipynb
│   └── olist_logistics_audit.html
├── outputs/
├── presentations/
├── README.md
└── .gitignore
