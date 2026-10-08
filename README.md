# Airbnb Market Analysis — Chicago vs New Orleans

An end-to-end Business Intelligence project analyzing Airbnb market dynamics across Chicago and New Orleans using Python, Pandas, Power BI, and DAX.

The project transforms raw Airbnb listing data into an interactive decision-support dashboard focused on pricing, occupancy, demand, neighborhood performance, and host behavior.

---

## 📌 Business Problem

Airbnb hosts, investors, and analysts need to understand which markets, neighborhoods, pricing segments, and host strategies perform better.

Raw listing data can be difficult to interpret directly. This project uses data cleaning, exploratory analysis, data modeling, DAX, and interactive visualization to turn raw Airbnb data into actionable business insights.

### Key Questions

- How do Chicago and New Orleans compare in pricing and occupancy?
- Which neighborhoods have the highest listing concentration?
- Does higher pricing result in better occupancy?
- Which property types dominate the marketplace?
- How do budget, standard, and luxury listings perform?
- How does host portfolio size relate to occupancy?
- What role do professional hosts play in the market?

---

## 🎯 Project Objectives

- Compare Airbnb markets in Chicago and New Orleans
- Analyze pricing patterns and price segments
- Study occupancy and demand efficiency
- Identify high-concentration neighborhoods
- Analyze property and room-type composition
- Compare individual and professional hosts
- Build an interactive Power BI dashboard for business analysis

---

## 🛠️ Tech Stack

### Data Analysis
- Python
- Pandas
- Data Cleaning
- Exploratory Data Analysis
- Data Transformation
- ETL

### Business Intelligence
- Power BI
- DAX
- KPI Design
- Interactive Dashboards
- Data Visualization
- Geospatial Analysis
- Business Storytelling

---

## 📊 Dataset & Data Preparation

The project uses Airbnb listing datasets from:

- Chicago
- New Orleans

The datasets were cleaned and combined into a unified analytical dataset.

### Data Preparation Steps

1. Removed duplicate listings
2. Handled missing values
3. Standardized column names and formats
4. Converted prices into numeric values
5. Created pricing segments:
   - Budget
   - Standard
   - Luxury
6. Derived occupancy-related metrics
7. Created host categories
8. Exported the cleaned dataset for Power BI

The cleaned dataset was then modeled in Power BI using DAX measures, KPIs, slicers, and interactive visualizations.

---

# 📈 Dashboard

The project contains four interactive Power BI dashboard sections.

## 1. Market Overview

Provides a high-level comparison between Chicago and New Orleans.

### KPIs

- Total Listings
- Active Listings %
- Median Price
- Occupancy Rate

### Key Insight

Higher pricing does not necessarily result in higher occupancy.

---

## 2. Property & Neighborhood Analysis

Analyzes geographic distribution, property types, and neighborhood performance.

### Visualizations

- Geographic distribution of listings
- Room-type composition
- Top neighborhoods by listing count
- Median nightly price by neighborhood

### Key Insight

Near North Side has a high concentration of listings and premium pricing, making it a major Airbnb hotspot.

---

## 3. Pricing & Demand Analysis

Examines the relationship between pricing and booking performance.

### Visualizations

- Price distribution
- Price vs occupancy
- Occupancy by host type
- Average monthly reviews

### Key Insight

Budget listings generally attract more reviews and demonstrate stronger occupancy performance than luxury listings.

Pricing alone does not explain occupancy.

---

## 4. Host Structure Analysis

Examines host concentration and portfolio size.

### Visualizations

- Host share
- Host scale vs occupancy
- Host distribution
- Top professional hosts

### Key Insight

Professional hosts control a significant share of inventory, but increasing portfolio size does not guarantee higher occupancy.

---

# 💡 Key Business Insights

### 1. Pricing does not directly determine occupancy

Higher-priced listings do not automatically achieve higher occupancy. Pricing strategy needs to be considered alongside market demand and property characteristics.

### 2. Budget listings show strong booking performance

Budget listings generally demonstrate stronger occupancy and review activity than luxury listings.

### 3. Entire homes dominate the marketplace

Entire homes/apartments represent a major share of the Airbnb marketplace across the analyzed markets.

### 4. Listings are concentrated in specific neighborhoods

A relatively small number of neighborhoods account for a significant concentration of listings, with premium areas also showing higher pricing.

### 5. Professional hosts have significant market presence

Professional hosts control a substantial portion of the inventory, but simply increasing the number of properties does not guarantee better occupancy.

---

# 🎯 Business Recommendations

Based on the analysis:

- Hosts focused on occupancy should evaluate budget and standard pricing strategies.
- Investors should consider high-demand neighborhoods when evaluating new properties.
- Hosts should optimize pricing based on demand rather than assuming higher prices produce better performance.
- Portfolio expansion should be accompanied by demand analysis rather than relying solely on increasing listing count.
- Market comparisons should consider both pricing and occupancy rather than using price as the only performance indicator.

---

# 📁 Project Structure

```text
airbnb-market-analysis-powerbi/
│
├── 01_data_cleaning.ipynb
│
├── airbnb_clean_dataset.csv
├── Chicago_raw.csv
├── New_Orleans_raw.csv
│
├── Airbnb_Market_Analysis.pbix
│
├── page_1_market_overview.png
├── page_2_property_neighborhood.png
├── page_3_pricing_demand.png
├── page_4_host_structure.png
│
└── README.md



Raw Airbnb Data
       ↓
Data Cleaning & Validation
       ↓
Python / Pandas Transformation
       ↓
Feature & Metric Creation
       ↓
Clean Analytical Dataset
       ↓
Power BI Data Model
       ↓
DAX Measures & KPIs
       ↓
Interactive Dashboards
       ↓
Business Insights & Recommendations
