# CityBikes x Census: Bike-Share Access in U.S. Cities
CIS 3120 Group 4 project. Combines the CityBikes API with Census ACS 5-year data.

## Setup
1. Get a free Census API key: https://api.census.gov/data/key_signup.html
2. Colab: add it in the Secrets panel (key icon) as CENSUS_API_KEY
   Local: copy .env.example to .env and paste your key
3. Run notebooks/01_acquisition_cleaning.ipynb, then 02_analysis_visuals.ipynb
   (01 writes census_places.csv and citybike_networks_us.csv to data/raw/ - teammates can use those without a key)
