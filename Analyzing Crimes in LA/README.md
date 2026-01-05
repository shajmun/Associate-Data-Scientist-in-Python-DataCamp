# Los Angeles Crime Data Analysis 

## Project Overview
This project performs an exploratory data analysis (EDA) on Los Angeles crime data to identify temporal, spatial, and demographic patterns. Using Python and the pandas library, the analysis answers key questions regarding when and where crimes occur, as well as the age demographics of victims.

## Key Objectives
The analysis focuses on three primary questions:
1.  **Peak Crime Hours:** Determining which hour of the day has the highest frequency of reported crimes.
2.  **Night Crime Hotspots:** Identifying which area has the largest frequency of crimes committed between 10 PM and 3:59 AM.
3.  **Victim Demographics:** Categorizing and counting crimes committed against victims of various age groups.

## Data
The data can be found here: https://drive.google.com/drive/folders/1SrzH3-F5W_LFQSRIii62BnBNY9Kaa1tH?usp=sharing

## Technologies Used
* **Python**
* **Pandas:** Data manipulation and analysis (grouping, sorting, binning).
* **Seaborn & Matplotlib:** Data visualization (countplots).
* **NumPy:** Numerical operations.

## Analysis & Findings

### 1. Temporal Analysis
* **Methodology:** Extracted the hour from the `TIME OCC` column and plotted the frequency of crimes per hour.
* **Result:** The **12th hour (12:00 PM)** was identified as having the highest frequency of crimes.

### 2. Night Crimes by Area
* **Methodology:** Filtered the dataset for "night hours" (10 PM - 3:59 AM) and grouped the data by `AREA NAME` to find the highest occurrence.
* **Result:** The **Central** area has the largest frequency of night crimes.

### 3. Victim Age Demographics
* **Methodology:** Victims were categorized into specific age bins (`0-17`, `18-25`, `26-34`, `35-44`, `45-54`, `55-64`, `65+`) using `pd.cut`.
* **Result:** The **26-34** age group is the most frequently victimized demographic, followed closely by the **35-44** age group.
