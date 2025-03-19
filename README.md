# Data Cleaning
Cleans a very messy IMDB dataset using Power Query

## Table of Contents  
1. [Overview](#overview)  
2. [Tools Used](#tools-used)  
3. [Output](#visuals)  

---

## Overview  
This project cleans IMDB raw data to a clean, usable one.

## Tools Used  
- Power Query

## Steps
1) Ensure file consistency	(Since the raw file is from CSV, ensure it is saved in UTF-8 in text file before load into Power Query)
2) Fix headers (Correct column names by removing extra spaces, fixing encoding issues, and ensuring consistency)
3) Remove unnecessary special characters (Clean punctuation and unwanted symbols in all text-based columns)
4) Ensure correct data types (Convert numbers, years, and categorical values to the proper format)
5) Split data using delimiters (Separate multiple values into individual columns)
6) Handle missing values (Remove or replace null values with appropriate defaults)
7) Standardize text formatting (Capitalize titles properly, fix spacing issues, and ensure uniform formatting)
8) Validate numerical fields (Fix corrupted numeric values)
9) Ensure currency in the right format (Fix corrupted currency values)
10) Normalize date formats (Convert all dates to a standard year format)
11) Spelling Error (Check if any spelling error or any punctuations error)
12) Remove duplicates (Identify and drop duplicate rows if necessary)
13) Final review (Ensure everything is cleaned)

## Output  
- ![Before Cleaning](https://github.com/AnalystXSol/-Data-Cleaning-IMDB-Datasets/blob/main/Before%20Cleaning%20(RAW).png)
- ![After Cleaning](https://github.com/AnalystXSol/-Data-Cleaning-IMDB-Datasets/blob/main/After%20Cleaning%20(FINAL).png)

## Project File  
[Download the Data Cleaning Project](https://github.com/AnalystXSol/-Data-Cleaning-IMDB-Datasets/blob/main/FINAL%20DELIVERY%20IMDB%20DATASET.xlsx) 
   


