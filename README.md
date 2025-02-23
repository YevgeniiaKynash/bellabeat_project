# bellabeat_project
## About the company 
Urška Sršen and Sando Mur founded Bellabeat, a high-tech company that manufactures health-focused smart products. Sršen used her background as an artist to develop beautifully designed technology that informs and inspires women around the world.
## Task
To analyze smart device usage data in order to gain insight into how consumers use non-Bellabeat smart devices
To select one Bellabeat product 
To apply insights in presentation. 

## Key stakeholders
UrškaSršen: Bellabeat’s cofounder and Chief Creative Officer 
SandoMur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team 
Bellabeat marketing analytics team: A team of data analysts responsible for collecting, analyzing, and repo ing data that helps guide Bellabeat’s marketing strategy.

## Qestions
1. What are some trends in smart device usage? 
2. How could these trends apply to Bellabeat customers? 
3. How could these trends help in influence Bellabeat marketing strategy?

## Data sources used
Public data that explores smart device users’ daily habits. 
● FitBit Fitness Tracker Data (CC0: Public Domain, dataset made available through Mobius)
This Kaggle data set contains personal fitness tracker from thirty Fitbit users. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes information about daily activity, steps, and heart rate that can be used to explore users’ habits.
The data downloaded and stored on PC in archive.zip folder. 
Exported data organized in 2 folders: 
mturkfitbit_export_3.12.16-4.11.16 included 11 csv files
 ![image](https://github.com/user-attachments/assets/4b327360-22df-42dd-8ed3-0c78d785f455)
mturkfitbit_export_4.12.16-5.12.16. included 18 csv files
 ![image](https://github.com/user-attachments/assets/e7cac289-5a2d-40d6-95e8-9b680cb45b78)

The data organized in wide format.

## ROCCC analysis for the FitBit Fitness Tracker data
**1. Reliability**
The data is obtained from the FitBit device, which is widely used for monitoring physical activity. However, there may be measurement errors due to sensor inaccuracies or incorrect device usage. It's also important to consider that the data may be incomplete due to missed days or lack of synchronization.  
**2. Originality**
The data is unique in the sense that it is collected individually for each user. It is primary data that has not undergone significant processing or transformation prior to publication. It is the primary data.  
**3. Comprehensiveness**
The data includes various aspects of physical activity, such as step count, heart rate, activity level, sleep, etc. However, it may lack important contextual information (e.g., users' health status or lifestyle), which could limit the depth of analysis.  
**4. Consistency**
The data is likely consistent in terms of time and format since it is automatically collected by the device. However, inconsistencies may arise due to missing data or changes in user behavior while wearing the device (e.g., if the user forgets to wear it).  
**5. Curation**
The data is available in its raw form, with minimal processing. This is good for maintaining originality but may require significant preprocessing and cleaning before analysis. It is important to account for possible data gaps and anomalies.  
**Conclusion:**
FitBit Fitness Tracker data represents a unique and reliable source of information on users' physical activity. However, to obtain accurate results, careful data cleaning is necessary, along with consideration of possible measurement errors and contextual limitations.  

 When working with FitBit Fitness Tracker Data, it is crucial to address several key aspects, including licensing, privacy, security, accessibility, and data integrity.

### Actions:
**Addressing Licensing:** attributed the source of the data appropriately in documentation.
**Addressing Privacy:** implemented anonymization techniques, such as removing user IDs or aggregating data, to ensure that individual users cannot be identified from the dataset.
**Addressing Security:** stored the data in secure, encrypted environments with access controls in place. Used secure methods for transferring data and ensured that any sharing of data is done in compliance with security protocols.
**Addressing Accessibility:**  offered the data in multiple formats (e.g., CSV, Excel) and ensured that tools used for analysis are compliant with accessibility standards, such as WCAG (Web Content Accessibility Guidelines).
**Verifying Data Integrity:** implemented data validation procedures, such as checking for missing values, duplicates, and outliers. Used checksum or hash functions to ensure that data has not been altered during transfer. Cross-validate with other data sources or documentation to confirm accuracy.

## Tehnology used
**R:** "tidyverse", "here", "janitor", "lubridate", "skimr", "readr", "dplyr"
**Tableau:** visualisations

## Project stracture
bash
bellabeat_project/

├── README.md            # project description  
├── data/                # data fils (CSV)  
├── reports/             # RMarkdown and HTML reports  
├── visualizations/      # visaulisations  

bellabeat_project/
├── README.md           # Описание проекта
├── data/               # Данные (CSV)
├── reports/            # RMarkdown и HTML отчёты
├── visualizations/     # Графики и дашборды




### 1. The correlation between the number of steps and the calories burned by the users. 

Analysis reveals a positive correlation between the number of steps taken and calories burned. The more active the user, the higher the calorie expenditure.

[View on Tableau Public](https://public.tableau.com/views/Bellabeat_viz_17327147322200/STEPSvsCOLORIES_1)
