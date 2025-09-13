# 🌍 Global CO₂ and Energy Data Analysis

This project explores CO₂ emissions and energy data across countries using **Python (Pandas, Matplotlib)** and **SQL (SQLite in Google Colab)**.  
It focuses on **data cleaning, SQL querying, and visualization.**

---

## 📊 Dataset
The datasets are obtained from [Our World in Data](https://ourworldindata.org/):
- **CO₂ dataset**: Global and country-level CO₂ emissions
- **Energy dataset**: Energy production and consumption data

For this project, the data was cleaned to include only **country-level records** (removing World, OECD, and regional aggregates) and restricted to **1950 onwards** for consistency.

---

## 🛠️ Tools & Libraries
- **Python**: Pandas, Matplotlib
- **SQL**: SQLite (via `ipython-sql` in Google Colab)
- **Google Colab**: for interactive analysis

---

## 🔎 Project Workflow
1. **Data Cleaning (Python + Pandas)**
   - Removed duplicates and missing values  
   - Filtered dataset to keep only rows with valid 3-letter ISO country codes  
   - Dropped all records before 1950  

2. **Database Setup (SQLite in Colab)**
   - Stored the cleaned datasets in a SQLite database  
   - Queried the data using SQL for country-specific and global insights  

3. **Data Analysis**
   - Top CO₂ emitting countries in recent years  
   - Long-term trend of India’s emissions  
   - Comparison of emissions and energy consumption across countries  

4. **Visualization (Python + Matplotlib)**
   - Line charts for country trends  
   - Bar charts for top emitters  
   - KPIs such as total emissions by year and per capita emissions  

---

## 📈 Example Insights
- India’s CO₂ emissions have grown steadily since 1950, with significant acceleration after 1990.  
- China and the United States remain the top two emitters globally.  
- CO₂ emissions correlate strongly with primary energy consumption.  

---

## 📂 Repository Structure
