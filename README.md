<img width="1000" height="1000" alt="problem statment in image" src="https://github.com/user-attachments/assets/21501e9c-c2f0-4ea5-bc7a-1eee31bc7b01" />

# Python project: CDC's National Outbreak Reporting System
Between 1971 and 2023, the United States recorded approximately 66,000 outbreaks, with 49% attributed  to person-to-person spread and 38% to foodborne transmission. To gain deeper insights into these outbreaks, it is essential to analyze trends over time, examine the primary modes of transmission, and assess how outbreaks vary across different states.

The analysis focuses on three key areas to better understand these outbreaks:
1.	How have outbreak patterns changed over the years?
2.	Which states account for the highest percentage of reported outbreaks?
3.	Which pathogens are associated with the greatest number of outbreaks, illnesses, and deaths?

# Data Set
The dataset used in this project comes from the Centers for Disease Control and Prevention (CDC) — specifically the National Outbreak Reporting System (NORS).
It contains detailed reports of foodborne, waterborne, and related disease outbreaks that occurred in the United States.
Each record represents one outbreak and includes information such as the year, month, state, etiology (cause), illnesses, hospitalizations, and deaths.

**Source**: CDC NORS Dataset – Foodborne, Waterborne, and Related Diseases

**Link**: [NORS Data set](https://data.cdc.gov/Foodborne-Waterborne-and-Related-Diseases/NORS/5xkq-dg7x/about_data)

**Format**: CSV (Open Data)

**Period Covered**: 1998 – 2023

**Size**: Around 70,000 rows and 40 columns


# Analysis
The dataset was cleaned and analyzed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.
The analysis focused on identifying trends in foodborne and waterborne disease outbreaks across the United States.
Data were grouped and visualized by year, state, and etiology (cause) to find the most common diseases and understand their severity based on illnesses, hospitalizations, and deaths.

Key insights revealed that Norovirus and Salmonella are the most frequent causes of outbreaks, while Listeria and E. coli were less common but caused more severe outcomes.
Additionally, seasonal patterns were observed, with outbreaks peaking during summer months (June–August), and certain states (like California and Texas) showing higher outbreak frequencies.

## Key Findings:
- Norovirus is the leading cause of foodborne outbreaks.
- Listeria and E. coli have the highest hospitalization and death rates.
- Most outbreaks occur during the summer season.
- Larger states tend to report more outbreaks than smaller ones.
 
# How To Run
- Download the data from the link --> Export as .CSV file.
- Make sure that the jupyter notebook and the CSV file are in the same folder
- In the jupyter file, run the code:

      pd.read_csv('NORS.csv',low_memory=False)

# Dependencies
The project was developed using the following Python libraries:

## Core Libraries:
- pandas – for data cleaning, manipulation, and analysis
- numpy – for numerical operations and calculations
- matplotlib – for creating plots and charts
- seaborn – for advanced visualizations

## Supporting Libraries:
- datetime – for handling date and time values
- us – helps works with U.S. states and territories
- warnings – to suppress unnecessary warning messages

## Optional Libraries (if used):
- plotly – for interactive charts and dashboards
- geopandas – for mapping and spatial data analysis

## Installation Commands:
### To install all dependencies: 
- Run

      pip install {library}
- Or, if you have a requirements.txt file, use:

      pip install -r requirements.txt



