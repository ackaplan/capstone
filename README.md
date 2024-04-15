**CONTENTS**

This repository contains code for exploratory data analysis & visualizations as well as modeling of PredictIT (PredictIT.org) user data that has been matched with voter registration 
and consumer attributes to append party, age, income, gender, ethnicity, occupation and many other data points. The analysis focuses on examining how PredictIT users differ from the general population  
of registered voters, as well as examining how those who have won money on PredictIT differ from those who have lost money. Modeling likely users and modeling likely winners was attemped. 

**INCLUDED FILES:**

- predictit_generate_data_for_analysis.sql - .sql script used to generate the user data and voter data for the analysis work.
- PredictIT_EDA.zip - contains Jupyter notebook for exploratory data analysis and visualizations. 
- PredictIT_Modeling_Likely_Users.jpynb - modeling likely users 
- PredictIT_Modeling_Winners.jpynb - modeling likely winners 
- counties.geojson - geojson file for use with county maps in EDA notebook 
- us_zip_to_lat_long - tab delimited file of 5 digit zip codes with associated latitude / longitude, used for Folium mapping in EDA notebook. 


**A NOTE ABOUT DATA ACCESS:**

PredictIT data used for this project and the voter / consumer data to which it was matched is proprietary / owned by Aristotle, International Inc. and is not available to the public.


**LIBRARIES USED:**

- pandas 
- numpy 
- sklearn 
- pyodbc 
- matplotlib 
- seaborn 
- geopandas 
- plotly 
- json 
- scipy 
- statsmodels
- folium 
- xgboost 
- catboost


