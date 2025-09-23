# Car_data_Analysis

## Overview
*_This project analyzes car sales data to uncover trends in customer demographics, brand performance, pricing, and regional preferences, providing insights into consumer buying behavior._*

---
## Content
Project Overview | Data Sources | Tools Used | Table Outlay | Query Language(SQL) | Visualization

---
## Project Overview:
This project explores a dataset of nearly 24,000 car sales records to analyze customer demographics, pricing patterns, brand performance, and regional dealership trends, with the aim of uncovering insights into consumer behavior and market opportunities.

## Data Source:
www.kaggle.com/dataset

---
## Tools Used
+ Pivot Table / Charts
+ Power BI
+ SQL

## Table Outlay
Car_id|	Date	|Customer Name	|Gender	|Annual Income	|Dealer_Name	|Company	|Model	|Engine	|Transmission	|Color	|Price ($)	|Dealer_No 	|Body Style	|Phone	|Dealer_Region	|Year
|-----|----|----|----|----|-----|-----|-----|----|----|----|----|-----|----|-----|----|----|
|C_CND_000001	|1/2/2022	|Geraldine	|Male	|13500	|Buddy Storbeck's Diesel Service Inc	|Ford	|Expedition	|DoubleÃ‚Â Overhead Camshaft|	Auto	|Black|	26000	|06457-3834	|SUV	|8264678|	Middletown	|2022|
|C_CND_000002|	1/2/2022	|Gia	|Male|	1480000	|C & M Motors Inc|	Dodge	|Durango	|DoubleÃ‚Â Overhead Camshaft	|Auto|	Black|	19000	|60504-7114|	SUV	|6848189	|Aurora	|2022|
|C_CND_000003	|1/2/2022|	Gianna	|Male	|1035000	|Capitol KIA	|Cadillac	|Eldorado	|Overhead Camshaft	|Manual	|Red	|31500	|38701-8047|	Passenger|	7298798|	Greenville|	2022|
|C_CND_000004	|1/2/2022|	Giselle|	Male|	13500	|Chrysler of Tri-Cities	|Toyota	Celica|	Overhead |Camshaft	|Manual	|Pale White|	14000|	99301-3882	|SUV|	6257557	|Pasco|	2022|
|C_CND_000005	|1/2/2022	|Grace	|Male|	1465000	|Chrysler Plymouth	|Acura	|TL	|DoubleÃ‚Â Overhead Camshaft	|Auto|	Red|	24500|	53546-9427	|Hatchback	|7081483	|Janesville	|2022|

## Query Language (SQL):
Some of the query languages to retrieve records are displayed here
```SQL
SELECT count (gender), transmittor FROM car_dataset
GROUP BY gender 
```


## Visualization
### Pivot Table
<img width="1324" height="589" alt="Car Folio" src="https://github.com/user-attachments/assets/bbcb188e-283b-4c87-8e9e-7ea0d7a1ab22" />

### Charts
<img width="1194" height="484" alt="chart car" src="https://github.com/user-attachments/assets/2dd67b88-0abf-493b-b423-e42beab5148e" />



