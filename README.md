# UEFA European Championship2024 data analysis 

## Introduction

This project focuses on the analysis of the UEFA European Championship 2024  dataset using Excel, Power BI, and PostgreSQL. The UEFA European Championship 2024  dataset provides detailed information on players performance and characteristics. This project aims to explore the dataset to uncover trends and insights using various data analysis tools.

# Table of Contents

-	Introduction

-	Client

-	Dataset
  
- Data Processing
  
-	Tools used

-	Data analysis steps
     - Excel
     - PostgreSQL
     - Power BI
     
-	Key Insights

-	Conclusion

-	License

# Client

The ideal end user of the UEFA European Championship data analysis is the Chief Data Officer of a major sports company, specifically focusing on football coverage . This executive is tasked with optimizing the company’s content strategy to ensure both engagement and informational values across various platforms, including digital and social media.

## Dataset
This dataset contains 623 players with 7 attributes including 
Player Name, Country, Foot, Goals , Age Range, Club, Market Value and .

## Data Processing

The data processing involves cleaning the dataset to remove any inconsistencies, handling missing values, and ensuring the data is in a suitable format for analysis. The processing steps include:

1. Importing the dataset into Excel spreadsheet.
2. Checking for and handling missing values.
3. Normalizing data where necessary.
4. Extracting relevant indicators for analysis.

 ## Tools Used
 
•	Excel : Excel was used For the initial data cleaning and basic analysis.

•	PostgreSQL : This was used For data transformation, storage and to execute complex queries.

•	Power BI: This was used to create interactive visualizations and dashboards.

## Data Analysis Steps

### Excel	

1. Data import: Imported raw CSV file into excel  
2. Data Cleaning:
    - Removed Duplicates
    - Handled missing values
    - Standardized data formats
   
3. Basic Analysis:
      -	Calculated summary statistics (e.g., average goals per players, distribution of market value).
      -	Created pivot tables for initial insights (e.g., goals by country).
   
4. Export Clean Data: Exported the cleaned data as a CSV file for further processing in PostgreSQL.
   
### PostgreSQL

1. Database Setup: Created a PostgreSQL database and table to store the cleaned data.
2. Data Ingestion: Imported the cleaned CSV file into PostgreSQL tables.
3. Data Transformation: Used SQL queries to aggregate data, and create new calculated fields.
4. SQL queries performed: All SQL queries performed can be found [here](https://github.com/Ememjay/READ.ME/blob/main/SQL_Script)
5. Export Transformed Data: Exported the transformed data as CSV file for visualization in Power BI.
   
### Power BI

1. Data import: imported the transformed CSV file into Power BI.
2. Data Modeling: Created calculated measures
3. Visualization:
    - Designed interactive dashboards to visualize key metrics
    - Example of visualizations created: Total Caps and  total goals scored by players, Market value distribution by player position e.t.c.
4. Insights: Used Power BI features like filters, and slicers to explore the data. Insight can be found [here](https://github.com/Ememjay/READ.ME/blob/main/Power%20BI%20Dashboard)
   
## Key Insights

•	Country Performance: Identified the top performing countries based on total goals.

•	Players Characteristics: Analyzed player distribution by foot preference and age range. 

•	Market Value Analysis: Examined the correlation between players performance (position) and market value. Analyzed the top 5 players by market value.

•	Club Representation: Highlighted clubs with the highest number of players in the tournament.

##  Conclusion

The analysis of the UEFA European Championship  dataset provided valuable insights into player performance and characteristics. Using Excel for initial data cleaning, PostgreSQL for complex data transformation, and Power BI for visualization, I was able to uncover trends and present them in an interactive manner.

# License

This project is licensed under the MIT License. See the [LINCENSE](https://github.com/Ememjay/READ.ME/blob/main/LICENSE) file for details. 

