# PySpark--Stock-Market-Price-Analysis-Project
This project focuses on analyzing stock market prices using PySpark. The project follows a structured approach, starting from data reading and cleaning, performing basic and advanced analysis, and finally saving the results in different formats.
## Project Steps
### 1. Data Reading and Cleaning
- Stock data was read from CSV files.
- Data types for columns (e.g., prices, volume) were converted from strings to numeric types for easier calculations.
### 2. Basic Stock Analysis
- Basic statistics such as average, minimum, and maximum stock prices were calculated.
- Data was grouped by year, month, and week to calculate high and low prices for each period.
 ### 3. Joins
 - Yearly, monthly, and weekly data were merged using joins to create a comprehensive dataset for analysis.
 ### 4. Advanced Analysis
 - A 50-day moving average was calculated for stock prices.
 - The top 5 highest closing prices for each stock per year were identified.
 ### 5. Saving Results
 - Results were saved in Parquet and CSV formats for future use.
 ## How to Run the Project
 - Ensure PySpark is installed on your system.
 -  Download the data from (PySpark---Stock-Market-Price-Analysis-Project) folder  and place it in the appropriate folder.
 -  Run the provided notebook.
   ## Requirements
 - Python 3.x
 - PySpark
 - Additional Python libraries: findspark, pyspark.sql
