# python-api-challenge
Module 6 Challenge (Python w/ API) - Wassim Deen

# Summary of Challenge
- 'WeatherPy' Challenge:
    1. Create Scatter Plots to Showcase the Relationship Between Weather Variables and Latitude
        - Generate List of Cities Using the `Citipy` Library
        - [OpenWeatherMap API] Retrieve Weather Data For All Cities in the List
        - Create Scatter Plots
            - Latitude vs. Temperature
            - Latitude vs. Humidity
            - Latitude vs. Cloudiness
            - Latitude vs. Wind Speed


    2. Compute Linear Regression for Each Relationship
        - Split `cwd_df` into two Pandas DataFrame
            - Northern Hemisphere DataFrame (`north_df`)
            - Southern Hemisphere DataFrame (`south_df`)

        - Create Linear Regression Plots Using `north_df` DataFrame
            - Northern Hemisphere: Temperature (C) vs. Latitude
            - Northern Hemisphere: Humidity (%) vs. Latitude
            - Northern Hemisphere: Cloudiness (%) vs. Latitude
            - Northern Hemisphere: Wind Speed (m/s) vs. Latitude

        - Create Linear Regression Plots Using `south_df` DataFrame
            - Southern Hemisphere: Temperature (C) vs. Latitude
            - Southern Hemisphere: Humidity (%) vs. Latitude
            - Southern Hemisphere: Cloudiness (%) vs. Latitude
            - Southern Hemisphere: Wind Speed (m/s) vs. Latitude            


- 'VacationPy' Challenge:
    1. [GeoViews] Create Map Displaying Every City in `city_data_df` DataFrame


    2. Narrow Down the `city_data_df` DataFrame to Find My Ideal Weather Condition


    3. Create `hotel_df` DataFrame


    4. [Geoapify API] For Every City, Find First Hotel Located within 10,000 Metres of My Coordinates
       
       
    5. [GeoViews] Use `hotel_df` DataFrame to Create Map; Hotel Name & Country as Additional Information in Hover Message
    

# Final Repository Structure
```
├── README.md
├── .gitignore
├── WeatherPy
    └── WeatherPy.ipynb
├── VacationPy
    └── VacationPy.ipynb
└── output_data
    ├── city_weather_data.csv
    └── Fig1.png
    └── Fig2.png
    └── Fig3.png
    └── Fig4.png
```
