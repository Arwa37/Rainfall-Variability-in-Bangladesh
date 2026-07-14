# Rainfall Variability in Bangladesh (1970–2016)

## Project Overview
This project provides a comprehensive historical analysis of rainfall patterns in Bangladesh across 47 years. Using a dataset of daily observations from the Bangladesh Meteorological Department, the analysis investigates rainfall trends, variability, and extreme weather events to support agricultural planning and flood risk management.

## Key Objectives
The analysis focuses on five core data-driven questions:
* Identifying regions with the highest average rainfall.
* Determining the most reliable months for planting based on rainfall volume and stability.
* Tracking how rainfall variability (Coefficient of Variation) has shifted across decades at the station level.
* Assessing flood risk by identifying the seasons with the highest frequency of extreme-rainfall months.
* Investigating the correlation between total rainfall amount and rainfall stability.

## Technical Approach
* **Data Source:** Daily rainfall records (1970–2016) from the Bangladesh Meteorological Department.
* **Data Processing:** The analysis was performed using **Python** to process and clean 542,376 daily observations.
* **Methodology:** For consistency, the study focused on the nine weather stations with complete 47-year datasets. Variability was measured using the Coefficient of Variation (CV) to identify stable versus volatile patterns.

## Main Insights
* **Planting Strategy:** July serves as the most dependable month for planting, offering the highest average rainfall combined with relatively low variability.
* **Flood Risks:** 93% of all extreme-rainfall events occurred during the monsoon season (June–September), highlighting this as the primary period for flood monitoring.
* **Geographical Trends:** Rainfall variability is not uniform; coastal stations have shown rising variability in recent decades, while other areas have stabilized.
* **Independence of Data:** There is a weak correlation (-0.13) between rainfall volume and variability, indicating that each station requires an individual, adaptive strategy rather than generalized regional assumptions.

## Built With
* **Python**
* **Pandas & NumPy** (Data processing)
* **Matplotlib/Seaborn** (Visualization)
