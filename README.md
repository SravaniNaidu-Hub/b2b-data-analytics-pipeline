# B2B Data Analytics Pipeline  

## Project Overview  
This project was part of a data analytics assessment, focusing on cleaning, transforming, and analyzing supplier and buyer data for a B2B marketplace. The goal was to build a data pipeline that integrates supplier and buyer data, generate insights through dashboards, and implement a recommendation system to match supplier materials with buyer preferences.  

## Key Features  
- **Data Cleaning & Preparation**: Consolidated and cleaned raw supplier datasets to create a structured inventory dataset.  
- **Analysis & Insights**: Designed dashboards in Looker Studio to analyze account manager performance and revenue reporting.  
- **Recommendation System**: Developed a data pipeline to match supplier materials with buyer preferences based on attributes like grade, finish, thickness, and weight.  

## Technologies Used  
- **Python** (for data processing and cleaning)  
- **SQL** (for data transformation and querying)  
- **Looker Studio** (for data visualization)  
- **Pandas & NumPy** (for data manipulation)  

## Project Structure  
├── data/
│ ├── supplier_data_1.xlsx
│ ├── supplier_data_2.xlsx
│ ├── buyer_preferences.xlsx
│ ├── deals.csv
├── notebooks/
│ ├── data_cleaning.ipynb
│ ├── recommendation_system.ipynb
├── scripts/
│ ├── data_pipeline.py
│ ├── recommendation_engine.py
├── dashboard/
│ ├── looker_studio_link.txt
├── README.md


## How to Run  
1. Clone the repository  
2. pip install -r requirements.txt
3. python scripts/data_pipeline.py
4. python scripts/recommendation_engine.py

View the analysis in Looker Studio(https://lookerstudio.google.com/reporting/8e0fd083-5e34-4cca-bbf8-23fca182000e).

**Results**

The cleaned dataset is structured for easy analysis.
The Looker Studio dashboard provides insights on account manager performance and revenue reporting.
The recommendation system outputs matched materials for each buyer.
