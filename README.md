## ACPML---EDA-Assignment---EDA-on-NYC-Taxi-Records---Submission---Suraj-Bhadra

### NYC Yellow Taxi Trip Data Analysis
This project involves a comprehensive analysis of New York City Yellow Taxi trip data with a focus on data cleaning, feature engineering, exploratory data analysis (EDA), and spatial visualization.

#### Key Highlights:

1. Data Cleaning & Preprocessing:

- Handled missing values through imputation (using median or logical estimates).
- Corrected invalid entries (e.g., undefined rate codes, zero-distance trips with high fares).
- Removed outliers and logically inconsistent records (e.g., long trips >250 miles, mismatched pickup/dropoff zones with zero fare).
- Standardized numerical features for potential use in machine learning models.

2. Feature Engineering:

- Extracted temporal features like pickup hour and month.
- Estimated missing airport fees based on fare breakdown.
- Created a filtered dataset of valid trips for deeper analysis.

3. Exploratory Data Analysis (EDA):

- Analyzed hourly and monthly trends in taxi pickups.
- Identified peak hours (5–6 PM) and busiest months (May and October).
- Examined payment types, rate codes, and other categorical features.
- Visualized geographic distribution of pickups across NYC zones.

4. Geospatial Mapping:

- Mapped ride density by pickup location using NYC Taxi Zone shapefiles.
- Prepared data for interactive or static choropleth maps to highlight high-demand areas.

