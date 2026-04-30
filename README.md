# Dublin Residential Property Bidding Prediction

This repository contains the code and data for "The Creation and Assessment of Machine Learning Models for Predicting Bidding in Dublin Residential Properties".

The project develops and evaluates machine learning models (XGBoost, LightGBM, CatBoost, Random Forest, and Multiple Linear Regression) to predict the amount of bidding experienced by dublin properties.

## Repository Structure

| File/Folder | Description |
|---|---|
| `geocoding_dissfyp.ipynb` | Initial data collection and processing - scrapes and parses raw property listings from a `.txt` file sourced from a real estate agent, merges with the Property Price Register, and uses the Google Maps API to enrich each record with coordinates and distances to key locations. |
| `Mainfyp_diss.ipynb` | Core analysis notebook - merges all collected datasets, performs preprocessing (cleaning, imputation, feature engineering), and trains/evaluates all machine learning models |
| `Dublin_Properties_2025_2.txt` | Raw property data as sourced from the real estate agent |
| `Merged_dataset.csv` | Final dataset used for modelling |
| `collected_datasets/` | Intermediate datasets generated throughout the geocoding and merging pipeline |
