# Source Files – AdventureWorks Dataset

This folder contains raw CSV files from the **AdventureWorks** sample dataset.  
These files will be used for data engineering and analytics pipelines.

## Files Overview

- **AdventureWorks_Products.csv**  
  Contains product information such as product IDs, names, categories, and attributes.  
  Useful for joining with sales data to analyze product performance.

- **AdventureWorks_Returns.csv**  
  Captures records of returned items, including sales order numbers, return reasons, and dates.  
  Useful for studying return rates and product/customer issues.

- **AdventureWorks_Sales_2016.csv**  
  Sales transaction data for the year 2016.  
  Contains order details, customer IDs, product references, sales amounts, and dates.  
  Useful for yearly sales trend analysis.

- **AdventureWorks_Sales_2017.csv**  
  Sales transaction data for the year 2017 (same structure as 2016 file).  
  Can be combined with 2016 data for multi-year trend analysis.

- **AdventureWorks_Territories.csv**  
  Contains territory and region information such as territory IDs, names, and groups.  
  Useful for mapping sales and returns to geographic regions.

## Usage

- These CSV files can be ingested into **Azure Data Factory (ADF)**, **Databricks**, or other ETL/ELT tools.  
- Typically used for **data warehouse** or **analytics projects**.  
- Example use cases:
  - Joining **Sales** and **Products** → product performance analysis.  
  - Combining **Sales** and **Territories** → regional sales insights.  
  - Linking **Returns** with **Products** → product return rate analysis.

## Notes

- Data is raw and should be cleaned/validated before loading into a target system.  
- File structure is assumed to follow the AdventureWorks schema.
