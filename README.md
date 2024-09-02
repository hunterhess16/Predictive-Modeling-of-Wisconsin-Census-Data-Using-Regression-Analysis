# This project involves building regression models to predict population data based on various census and land-use data for Wisconsin. Using multiple data sources, such as geographic boundaries and housing unit details, the goal is to create predictive models that can estimate population and other metrics.

Data Sources:
counties.geojson: Contains population data and the boundaries of Wisconsin counties.
tracts.shp: Geographic boundaries of census tracts within counties.
counties_tracts.db: Database with detailed information on housing units per tract.
land.zip: Land use data, including details on farm, forest, and developed areas.
Objectives:
Extract and clean data to create suitable DataFrames for model training.
Perform regression analysis to predict population based on features like land area, housing units, and land use.
Split datasets into training and test sets to evaluate model performance.
Visualize relationships between population and various features.
Key Tasks:
Predict population using county land area and housing units.
Explore relationships between population and land use features.
Build and evaluate regression models using different features and cross-validation techniques.
Provide recommendations on the most effective model based on performance metrics.
