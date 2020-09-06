# Predicting hourly energy consumption of San Diego, CA, US
This repo contains files and jupyter notebooks related to the above project. This project focuses on predicting energy consumption of the entire region in southern CA served by the SDGE (San Diego Gas and electric) utility (which comes under CAISO) based on the past 5 years of hourly energy consumption data. 

#### File descriptions:
###### [Initial_project_proposal.docx](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/Initial_project_proposal.docx)
Contains the initial project proposal 

###### [Capstone1_Final_Report.docx](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/Capstone1_Final_Report.docx)
Contains the final project report from data import and EDA to ML

###### [SDGE_energy_EDA.ipynb](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/SDGE_energy_EDA.ipynb)
A single notebook file including data import of energy, weather and PV installation data files, statistical analysis, EDA, finding trends among energy, weather and PV installation capacity data. Preparing the data for ML.  
[NBviewer link for the EDA notebook](https://nbviewer.jupyter.org/github/pratha19/Springboard_capstone_project_1/blob/master/SDGE_energy_EDA.ipynb#4)

###### [hourly1418_energy_temp_PV.csv](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/hourly1418_energy_temp_PV.csv)
Contains the cleaned and merged data with energy time series, added time components, temperature and PV installations. This was used in the ML models.

###### [SDGE_energy_ML.ipynb](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/SDGE_energy_ML.ipynb)
A single notebook file including all the ML models that were tried on the dataset. Different models including elastic net, random forest, SARIMAX, FB Prophet, XGBoost, XGBoost+FB Prophet were tried with some feature engineering techniques. These models were compared to the baseline forecast which simply repeats the past values.   
[NBviewer link for the ML notebook](https://nbviewer.jupyter.org/github/pratha19/Springboard_capstone_project_1/blob/master/SDGE_energy_ML.ipynb#8)

###### [Capstone1_SDGE.pptx](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/Capstone1_SDGE.pptx)
Presentation slide deck for the entire project.
________________________________________________
###### [ca_elect_map.jpg](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/ca_elect_map.jpg)
California map showing different electrical utility regions including the San Diego Gas and Electric (SDGE) which was the focus of this project.

###### [LCD_weather_stations_NOAA.kmz](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/LCD_weather_stations_NOAA.kmz)
Google earth kmz file showing locations of weather stations in US

###### [NEM_CurrentlyInterconnectedDataKey.b29667e204f3.xlsx](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/NEM_CurrentlyInterconnectedDataKey.b29667e204f3.xlsx)
PV installation dataset key to understand all the columns. Actual PV installations data couldn't be uploaded because it is >50MB. But the link of the data is given in the SDGE_energy_EDA.ipynb in its PV section. 

###### [hourly1418CA.csv](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/hourly1418CA.csv)
Hourly energy consumption data in MWH for all the 4 utilities of CA. 

###### [hourly1418SDGE.csv](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/hourly1418SDGE.csv)
Hourly energy consumption data in MWH for only SDGE.

###### [houry_data_NOAA_2014_2018.csv](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/houry_data_NOAA_2014_2018.csv)
NOAA weather data from 2014-18 for SDGE region (data of two stations including the SDGE airport which was used in this project). 
