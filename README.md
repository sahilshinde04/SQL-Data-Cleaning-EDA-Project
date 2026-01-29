# SQL-Data-Cleaning-EDA-Project
SQL project performing Data Cleaning and Exploratory Data Analysis (EDA) on real-world layoffs dataset using MySQL.
#  SQL Data Cleaning & Exploratory Data Analysis Project
 
 Project Overview:
This project demonstrates an end-to-end **SQL-based Data Analytics workflow** using a real-world layoffs dataset.  
The objective was to clean raw data, handle inconsistencies, and perform **Exploratory Data Analysis (EDA)** to extract meaningful insights.


 Dataset
- Source:  Kaggle – Global Layoffs Dataset  
- Format: CSV  
- Includes: 
  - Company  
  - Industry  
  - Location  
  - Total Laid Off  
  - Percentage Laid Off  
  - Funding Raised  
  - Date  


 Tools & Technologies
- Database: MySQL  
- Language: SQL  
- Concepts Used:
  - CTEs  
  - Window Functions (`ROW_NUMBER`, `DENSE_RANK`)  
  - Joins  
  - Aggregations  
  - Date Functions  


1. Data Cleaning Process
The following steps were performed:
- Created staging tables to preserve raw data  
- Identified and removed duplicate records using `ROW_NUMBER()`  
- Standardized inconsistent values (industry names, country formats)  
- Handled NULL and empty values appropriately  
- Converted date fields from text to `DATE` format  
- Removed records with insufficient information  


2.Exploratory Data Analysis (EDA)
Key analyses performed:
- Companies with the highest layoffs  
- Industry-wise and country-wise layoffs  
- Year-wise and monthly layoffs trends  
- Rolling total of layoffs over time  
- Top 3 companies with maximum layoffs per year using window functions  


 📈 Key Insights
- Layoffs were highly concentrated in industries like **Tech** and **Crypto**  
- The **United States** recorded the highest number of layoffs  
- Significant spikes in layoffs were observed in specific years  
- Startups with high funding were not immune to layoffs  


 ✅ Conclusion
This project reflects real-world data analytics practices and demonstrates strong **SQL fundamentals**, analytical thinking, and structured problem-solving.

---

