# SI671 Final Project - Investigating Recent Changes in Influenza Seasons

Final project for SI671 - Data Mining: Methods and Applications at the University of Michigan School of Information.

### Bella Karduck and Theodora Vorias

## Objective
Over time the flu season in the US has been quite stable in its severity, duration, and rate of incidence, more recent years have seen great variation. In the wake of COVID-19 pandemic, annual flu season trends have been particularly distinct from earlier years in that the peak is noticeably earlier in the season by over a month. 

Our goal is to see if there is concept drift; or the idea that the older data might not be effective at predicting current data. 

To do this, we performed time series analysis to investigate seasonal patterns in recent years. We also used machine learning models like XGBoost to discover which time splits of data best model current and future data. 

## Data
The data used in this study is sourced from the Centers for Disease Control and Prevention (CDC)’s U.S. Outpatient Influenza-like Illness Surveillance Network (ILINet). ILINet aggregates data on outpatient visits for respiratory illnesses provided by healthcare providers across the United States, the District of Columbia, Puerto Rico, and the U.S. Virgin Islands and reports on occurrences of influenza-like illness (ILI), which is defined as visits “due to any respiratory pathogen that presents with symptoms of fever plus cough or sore throat”.

Our initial dataset included all available data provided by ILINet since its inception in 1997 at the national and state level through week 45 of 2023. The data is aggregated in weekly intervals. Prior to 2002, data is not available for non-flu season weeks (week 21-39), so we dropped those flu seasons from our analysis as the missing data doesn’t accurately reflect ILI cases for those years. 

## Time Series Analysis
* Anomaly Detection contains the scratch code for the time series analysis

* Part 1 Time Series contains the cleaned time series analysis

## Predictive Modeling
* Part 2 Predictive Modeling and Part 2 Predictive Modeling TV contain messy scratch notebooks for developing models.

* Part 3 Final Modeling contains our implementations for our cleaned, final models 
 



