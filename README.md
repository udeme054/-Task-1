# DecodeLab Data Analytics Internship - Week 1 Project: Data Cleaning & Pre-Preparation

# Author 
Udeme Jackson Data analytics intern at DecodeLabs

## Project Overview 
This repository contains the Week 1 project completed during my Data Analytics internship at DecodeLab. 
The core objective of this project was to take a raw, unoptimized transactional sales dataset and transform it into a clean, structured, and analysis-ready format using **Excel Power Query.
By applying rigorous data cleaning and ETL (Extract, Transform, Load) principles, I enhanced data quality, established consistency, and engineered new features to facilitate seamless downstream reporting and visualization.

## Tools & Technologies Used 
Microsoft Excel (Data source inspection) 
Excel Power Query Editor** (ETL processing, data cleaning, and transformation)

## Data Cleaning & Pre-Preparation Process 
The transformation from raw data to a verified dataset involved a systematic, step-by-step pipeline inside Power Query: 

### Removing Duplicate Records 
Action: Scanned the dataset for redundant entries.
Objective: Ensured data integrity by removing duplicate rows based on unique transaction identifiers (`OrderID`), preventing the inflation of sales metrics. 
### Standardizing & Correcting Data Formats 
Action: Audited and changed data types across all columns.
Objective: Explicitly assigned proper data types (e.g., setting `Date` to Date format, `Total Price` and `Unit Price` to Currency/Decimal, and IDs/Addresses to Text). This ensures mathematical accuracy and seamless date filtering in future analyses. 
### Handling and Replacing Missing Values 
Action: Identified null values within the promotional/coupon tracking columns.
Objective: Replaced blank/null fields with the standard string "No Coupon" to clear up ambiguity, ensuring categorical fields are clean and ready for grouping. 
### Feature Engineering (Date Columns Creation) 
Action: Extracted time intelligence fields from the base "Date" column using Power Query's date tools. 
Objective: Engineered specialized "Month" and "Year" columns. This optimization enhances data preparation and allows for seamless time-series analysis and granular monthly/yearly performance sorting. 
### Enhancing Consistency & Quality 
Action: Reviewed text distributions, trimmed whitespace, and validated column profiles. 
Objective: Ensured all records conform to a reliable standard, establishing a solid foundation for robust descriptive statistics and exploratory data analysis (EDA). 

### Key Deliverables & Insights
Following the pre-preparation phase, the dataset is fully optimized to extract operational insights, including:
Descriptive Statistics: Baseline measurements across quantities, unit prices, and total order volumes.
Outlier Analysis: Detection of extreme values using Interquartile Range (IQR) boundaries to isolate unusual purchasing behaviors.
Performance Summaries: Aggregated sales performance tracking across diverse product categories (e.g., Chairs, Desks, Laptops, Printers) and specific marketing channels.

1. LinkedIn: [www.linkedin.com/in/udeme-jackson-0a0887144](https://www.linkedin.com/posts/udeme-jackson-0a0887144_dataanalytics-powerquery-excel-activity-7465136257761812480-5yuU?utm_source=share&utm_medium=member_desktop&rcm=ACoAACMDV7gBXE-tE0ZG2fYv2alSEQVhZV173Wc)
2. GitHub: https://github.com/udeme054/-Task-1.git

### Project gallery

### Uncleaned dataset for Project 1

![alt text](https://github.com/udeme054/-Task-1/blob/3e1a9829613afd6fa329cf2a3524f8641b2b0ac3/Uncleaned%20Dataset%20for%20Projet%201.jpg)

### Cleaned dataset for Project 1
![alt text](https://github.com/udeme054/-Task-1/blob/5c7780fb5774a8514ad76a326bbc5ff5ebd36eb5/Cleaned%20data%20from%20decode%20lab.jpg)
