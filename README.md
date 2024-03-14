# MTA-NYCT-Safety-Data-Analysis

## Overview
This project provides a comprehensive analysis of the Metropolitan Transportation Authority (MTA) New York City Transit (NYCT) safety data starting from 2019. The analysis covers various metrics related to the safety and operational performance of the bus and subway systems in New York City. Prepared by Hrithik Shukla, this project aims to uncover insights into trends, performance, and areas for improvement in public transit safety.

## Dataset
The dataset, MTA_NYCT_Safety_Data__Beginning_2019.csv, includes monthly safety metrics for the MTA bus and subway systems. It contains columns for the month, department (Bus or Subway), metric name, and metric value. Sample metrics include Bus Collision Per Million Miles, Bus Collision Injuries Per Million Miles, Subway Customer Accidents, and Subway Fires.

## Analysis Notebook
The Jupyter Notebook, MTA_Safety_Data_Hrithik_Shukla.ipynb, contains the analysis and visualization of the safety data. The notebook is structured into several sections, with each focusing on a different aspect of the data:

## Analysis of MTA NYCT Safety Data: 
An introductory section that outlines the scope and objectives of the analysis.
Dataset Details: Provides information on the dataset's structure and content.
Analysis Per Month and Year: Examines trends in safety metrics over time.

## Metric-Specific Analyses: 
Detailed analysis for each safety metric, including:
1. Bus Collision Per Million Miles
2. Bus Collision Injuries Per Million Miles
3. Bus Customer Accidents per million customers
4. Subway Customer Accidents
5. Subway Fires
6. Audible Pedestrian Turn Warning System Installations,
7. Vision Zero Employee Training Records,
8. Joint Track Safety Audits - Actual Count,
9. Joint Track Safety Audits - Compliance Rate,
10. Continuous Welded Rail Initiative (# Track Feet),
11. Friction Pad Installation
    
## Key Findings
A summary of key insights and trends identified in the analysis. 

Here's a concise summary of the key findings for each metric based on your analysis:

### Collisions Per Million Miles
- **2020 Decline**: Significant reduction in collisions, likely due to the pandemic.
- **Post-2020 Trend**: General upward trend, with the highest rates observed in fall and early winter, suggesting seasonal impacts on collision rates.
- **2022 Peak**: Highest collision rate observed, indicating a need for safety measure reevaluation.

### Bus Collision Injuries Per Million Miles
- **Increasing Trend**: Notable upward trend in injury rates over time, with summer to early autumn months showing higher values.
- **2020 Lowest Rate**: The pandemic year showed the lowest injury rates, with subsequent years seeing steady increases.

### Bus Customer Accidents per Million Customers
- **Rising Accident Rates**: Consistent year-over-year increase, with 2020 marking the start of a significant uptrend.
- **Seasonal Peaks**: Higher rates in summer to autumn, indicating potential seasonal factors affecting safety.

### Subway Customer Accidents
- **Fluctuating Trend**: Overall fluctuating trend with a significant spike in April 2020, potentially linked to the COVID-19 pandemic.
- **Recent Years Increase**: Gradual increase in accidents from 2021 onwards, suggesting evolving factors impacting subway safety.

### Subway Fires
- **Early 2022 Peak**: A peak in February 2022 with a general trend of fluctuation but a notable decrease in late 2023 and early 2024.
- **Increasing Trend to 2022**: Rising trend in subway fire incidents from 2019 to a peak in 2022, followed by a decrease in 2023.

### Audible Pedestrian Turn Warning System
- **Initial Variability and Peaks**: Active installation phase with a notable increase in March 2022, followed by a sharp decline mid-2023.
- **Installation Trends**: Shows phases of implementation with higher activity in early spring, decreasing towards mid to late year.

### Vision Zero Employee Training
- **Increasing Engagement**: Significant uptick in training sessions, especially in late 2021 and September 2023, indicating a focus on the Vision Zero initiative.
- **Yearly Trends**: An initial strong effort in 2021, a slight decrease in 2022, followed by a significant increase in 2023.

### Joint Track Safety Audits - Actual Count
- **Consistent Effort**: Regular safety audits conducted with fluctuations, a peak in March 2022, and a focus on ensuring subway safety.
- **Annual Increases**: Slight yearly increase in the average number of audits, reflecting a commitment to enhancing subway safety.

### Continuous Welded Rail Initiative
- **Significant Fluctuations**: Variability in monthly installations, with a general ambitious effort to update the subway's rail infrastructure.
- **Yearly Trends**: A solid start in 2021, a slight decrease in 2022, followed by a significant increase in 2023, indicating project acceleration.

### Friction Pad Installation
- **Upward Trend**: General increase in installations from 2022 onwards, with significant variability and a peak in December 2023.
- **Project Expansion in 2023**: Indicates an intensified effort or expansion in scope, aiming to improve subway safety and operational efficiency.

## How to Use
Clone this repository to your local machine.
Ensure you have Jupyter Notebook or JupyterLab installed.
Open MTA_Safety_Data_Hrithik_Shukla.ipynb in Jupyter to view the analysis.
The CSV file must be in the same directory as the notebook for the analysis to run correctly.

## Dependencies
Python 3.x
Pandas
Matplotlib
Seaborn
