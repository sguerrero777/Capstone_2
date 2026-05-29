# Capstone 2: EmporiUm Sales Territory Analysis with Python

## Overview and Objectives
Marketing Managers Jeff "Howdy" Richards (Texas) and Miami Vue (New Jersey) 
assigned me to perform a cross-region sales analysis for EmporiUm, a student 
bookstore chain that sells technology, textbooks, art supplies, and other 
products across the U.S. This analysis compares the Texas (South Region) and 
New Jersey (Northeast Region) territories using Python to identify performance 
trends and deliver data-driven recommendations for Q1 2026.

## Sales Territory Details
- **Territory Managers:** Jeff "Howdy" Richards (TX) | Miami Vue (NJ)
- **Assigned Territories:** Texas (South Region) & New Jersey (Northeast Region)
- **Region Directors:** Cassie Chambers (South) | Michael Jarvis (Northeast)
- **Scope of Analysis:** In-Store Sales January 1, 2022 – December 31, 2025 (4 fiscal years)

## Executive Summary
- **Top Territory:** New Jersey leads in overall revenue driven by 5 additional store locations
- **Top Store:** Beaumont, TX (`$637,819`) is a top performer across both territories
- **Top Category:** Technology & Accessories dominates across both territories with over `$6M` combined revenue
- **Top Rewards Customer:** Nate Jacobs (Texas) at `$5,241` total spend
- **Revenue Trend:** Both territories trending upward across the 48-month period

## Repository Structure

**Root**
- `Guerrero_Sales_Analysis.ipynb` — Full core marketing analysis notebook with Python visualizations
- `README.md` — Project overview and documentation

**dataset_imports/** — Source data files
- `StoreSales.csv` — 335,000+ transaction records (date, store, product, sale amount, rewards ID)
- `StoreDetail.csv` — Store location details (city, state, store ID, territory manager, region)
- `Products.csv` — Product catalog (product number, name, category ID, subcategory ID)
- `ProductCategories.csv` — Category and subcategory reference table (ID to name mapping)
- `customer_list.csv` — Rewards member list (customer ID, name, email, phone, contact preferences)

**matplotlib_visualizations/** — Exported chart images
- `revenue_trend_chart.png` — Monthly revenue trend across both territories
- `category_revenue_chart.png` — Revenue comparison by product category
- `store_rankings_chart.png` — Store performance rankings
- `top_customers_chart.png` — Top rewards customers by territory

**presentations/** — PowerPoint slide decks
- `Guerrero_SlideDeck.pptx` — for 10-minute recorded presentation
- `Guerrero_5min_SlideDeck.pptx` — for 5-minute live presentation

## Tools Used
- **Python** — data analysis and visualization
- **Jupyter Notebook** — interactive environment for analysis and presentation
- **Pandas** — data manipulation and DataFrame operations
- **NumPy** — numerical computing and regression analysis
- **Matplotlib** — data visualization and charting
- **Git & GitHub** — version control and project management
- **PowerPoint** — presentation and recording

## Video Demo

## Author
Sharleen Guerrero | Year Up United Data Analyst Training Academy
