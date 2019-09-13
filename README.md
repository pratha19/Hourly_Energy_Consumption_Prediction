# Springboard_capstone_project_1
As part of Springboard's Data Science career track this repo contains files and jupyter notebooks related to my first
capstone project. This project focuses on predicting energy consumption of the entire region in southern CA served by the SDGE (San Diego Gas and electric) utility (which comes under CAISO) based on the past 5 years of hourly energy consumption data. 

#### File descriptions:
###### [Initial_project_proposal.docx](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/Initial_project_proposal.docx)
Contains the initial project proposal 

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

###### [ca_elect_map.jpg](https://github.com/pratha19/Springboard_capstone_project_1/blob/master/ca_elect_map.jpg)
California map showing different electrical utility regions including the San Diego Gas and Electric (SDGE) which was the focus of this project.
