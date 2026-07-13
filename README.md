# Rainfall Variability in Bangladesh (1970–2016)

## Project Overview
This project provides a comprehensive historical analysis of rainfall patterns in Bangladesh across 47 years[cite: 1]. Using a dataset of daily observations from the Bangladesh Meteorological Department, the analysis investigates rainfall trends, variability, and extreme weather events to support agricultural planning and flood risk management[cite: 1].

## Key Objectives
The analysis focuses on five core data-driven questions:
* Identifying regions with the highest average rainfall[cite: 1].
* Determining the most reliable months for planting based on rainfall volume and stability[cite: 1].
* Tracking how rainfall variability (Coefficient of Variation) has shifted across decades at the station level[cite: 1].
* Assessing flood risk by identifying the seasons with the highest frequency of extreme-rainfall months[cite: 1].
* Investigating the correlation between total rainfall amount and rainfall stability[cite: 1].

## Technical Approach
* **Data Source:** Daily rainfall records (1970–2016) from the Bangladesh Meteorological Department[cite: 1].
* **Data Processing:** The analysis was performed using **Python** to process and clean 542,376 daily observations[cite: 1].
* **Methodology:** For consistency, the study focused on the nine weather stations with complete 47-year datasets[cite: 1]. Variability was measured using the Coefficient of Variation (CV) to identify stable versus volatile patterns[cite: 1].

## Main Insights
* **Planting Strategy:** July serves as the most dependable month for planting, offering the highest average rainfall combined with relatively low variability[cite: 1].
* **Flood Risks:** 93% of all extreme-rainfall events occurred during the monsoon season (June–September), highlighting this as the primary period for flood monitoring[cite: 1].
* **Geographical Trends:** Rainfall variability is not uniform; coastal stations have shown rising variability in recent decades, while other areas have stabilized[cite: 1].
* **Independence of Data:** There is a weak correlation (-0.13) between rainfall volume and variability, indicating that each station requires an individual, adaptive strategy rather than generalized regional assumptions[cite: 1].

## Built With
* **Python**
* **Pandas & NumPy** (Data processing)
* **Matplotlib/Seaborn** (Visualization)
