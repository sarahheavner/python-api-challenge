# python-api-challenge

    WeatherPy
        Objective was to select 500+ random cities and analyze weather data to determine if specified weather trends correlate to latitude
        
            - Created a list to store cities based on random lat/long coordinates using citipy
            - Created count of cities to verify that the result captured at least 500 cities
            - Using Open Weather Map API, loop through city list and capture certain weather conditions, print list of cities that are 
              processed, skipping over any city without weather data
            - Output CSV with all cities with weather data to use for VacationPy
            - Create dataframe with weather data
            - Create multiple scatter plots that compare latitude to weather conditions to determine if there is a relationship between the 
              two variables
            - Create 2 new dataframes, separating into Northern and Southern Hemispheres
            - Using separated dataframes, recreate above scatterplots for each weather condition
            
    VacationPy
        Objective was to use weather data from WeatherPy to determine optimal vacation locations
            
            - Imported CSV from WeatherPy activity
            - Using Google Maps API, create heatmap that shows humidity levels of each city
            - Create new DF that has "perfect weather conditions" 
            - Locate nearest hotel to cities with ideal weather conditions
            - Add hotel name to DF
            - Using Google Maps API again, add hotel marker to previosuly created heatmap
            
            