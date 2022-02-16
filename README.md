# Deangu_Disease_Prediction


DengAI: Predicting Disease Spread

Project Description
Dengue fever is a mosquito-borne disease that occurs in tropical and sub-tropical parts of the world. In mild cases, symptoms are similar to the flu: fever, rash, and muscle and joint pain. In severe cases, dengue fever can cause severe bleeding, low blood pressure, and even death.
Because it is carried by mosquitoes, the transmission dynamics of dengue are related to climate variables such as temperature and precipitation. Although the relationship to climate is complex, a growing number of scientists argue that climate change is likely to produce distributional shifts that will have significant public health implications worldwide.
An understanding of the relationship between climate and dengue dynamics can improve research initiatives and resource allocation to help fight life-threatening pandemics.
NB: Please ensure performance is evaluated primarily according to the mean absolute error.
Objective: Using environmental data collected by various U.S. Federal Government agencies, Predict the number of dengue fever cases reported each week in San Juan, Puerto Rico and Iquitos, Peru.
Dataset Source
Link: DengAI: Predicting Disease Spread
Dataset Description
Link: DengAI: Data Description






Problem Description
Your goal is to predict the total_cases label for each (city, year, weekofyear) in the test set. There are two cities, San Juan and Iquitos, with test data for each city spanning 5 and 3 years respectively. You will make one submission that contains predictions for both cities. The data for each city have been concatenated along with a city column indicating the source: sj for San Juan and iq for Iquitos. The test set is a pure future hold-out, meaning the test data are sequential and non-overlapping with any of the training data. Throughout, missing values have been filled as NaNs.
 
Dataset Description

City and date indicators


precipitation_amt_mm – Total precipitation


city – City abbreviations: sj for San Juan and iq for Iquitos


week_start_date – Date given in yyyy-mm-dd format


NOAA's GHCN daily climate data weather station measurements



station_max_temp_c – Maximum temperature


station_min_temp_c – Minimum temperature


station_avg_temp_c – Average temperature


station_precip_mm – Total precipitation


station_diur_temp_rng_c – Diurnal temperature range


PERSIANN satellite precipitation measurements (0.25x0.25 degree scale)


NOAA's NCEP Climate Forecast System Reanalysis measurements (0.5x0.5 degree scale)


reanalysis_sat_precip_amt_mm – Total precipitation


reanalysis_dew_point_temp_k – Mean dew point temperature


reanalysis_air_temp_k – Mean air temperature


reanalysis_relative_humidity_percent – Mean relative humidity


reanalysis_specific_humidity_g_per_kg – Mean specific humidity


reanalysis_precip_amt_kg_per_m2 – Total precipitation


reanalysis_max_air_temp_k – Maximum air temperature


reanalysis_min_air_temp_k – Minimum air temperature


reanalysis_avg_temp_k – Average air temperature


reanalysis_tdtr_k – Diurnal temperature range


Satellite vegetation - Normalized difference vegetation index (NDVI) - NOAA's CDR Normalized Difference Vegetation Index (0.5x0.5 degree scale) measurements



ndvi_se – Pixel southeast of city centroid


ndvi_sw – Pixel southwest of city centroid


ndvi_ne – Pixel northeast of city centroid


ndvi_nw – Pixel northwest of city centroid
