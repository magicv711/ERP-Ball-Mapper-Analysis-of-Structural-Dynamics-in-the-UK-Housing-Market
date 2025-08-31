# ERP-Ball-Mapper-Analysis-of-Structural-Dynamics-in-the-UK-Housing-Market
# Topological Data Analysis of UK House Prices

This repository contains the code accompanying my MSc dissertation project **"Topological Data Analysis and House Prices"**.  
The project explores how the UK housing market structure changed during three key periods:  
- the **2008 Global Financial Crisis**,  
- the **2015–2016 stable period**,  
- the **2020 COVID-19 pandemic**.  

We use **Topological Data Analysis (Mapper and Ball Mapper)**, together with traditional statistical tools (heatmaps and OLS regression), to compare structural patterns across regions and time.

---

## Repository Structure

- **Preprocessing/**  
  Data cleaning and preparation scripts.  
  Includes: price aggregation, income processing, population density calculation, handling missing values and special symbols.

- **Eda/**  
  Exploratory data analysis:  
  - Monthly and yearly housing price trends  
  - YoY growth by property type  
  - Correlation heatmaps for different periods  

- **Model/**  
  Structural analysis and modelling:  
  - Heatmaps (correlation by period)  
  - Ball Mapper visualisations (regional clustering, affordability ratio, self-employment rate, price change, etc.)  
  - OLS regressions with VIF diagnostics  

---
## Data

- House price and transaction data: UK House Price Index (ONS).  
- Regional socio-economic indicators: ONS datasets (employment, income, education, population).  
- Period-difference variables: Crisis_0809_Diff, Stable_1516_Diff, Covid_2020_Diff.  
- Raw data are not included due to size and licensing; please download from ONS or replace with your own.


## How to Run

### Install dependencies
```bash
pip install -r requirements.txt



