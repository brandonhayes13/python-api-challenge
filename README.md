# python-api-challenge
  
  This activity is broken down into two deliverables, WeatherPy and VacationPy. In this deliverable, I'll create a Python script to visualize the weather of over 500 cities of varying         distances from the equator. I'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities. In the VacationPy deliverable, I'll use your weather data skills to plan future vacations. Also, I'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API. My main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

      To fulfill the first requirement, I'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, I'll create a series of scatter plots to showcase the following relationships:

          Latitude vs. Temperature

          Latitude vs. Humidity

          Latitude vs. Cloudiness

          Latitude vs. Wind Speed
          
      Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r^2 values

          Create the following plots:

          Northern Hemisphere: Temperature vs. Latitude

          Southern Hemisphere: Temperature vs. Latitude

          Northern Hemisphere: Humidity vs. Latitude

          Southern Hemisphere: Humidity vs. Latitude

          Northern Hemisphere: Cloudiness vs. Latitude

          Southern Hemisphere: Cloudiness vs. Latitude

          Northern Hemisphere: Wind Speed vs. Latitude

          Southern Hemisphere: Wind Speed vs. Latitude

      After each pair of plots, explain what the linear regression is modeling.

      To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

          Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

          Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

              A max temperature lower than 27 degrees but higher than 21

              Wind speed less than 4.5 m/s

              Zero cloudiness

          Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

          For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

          Add the hotel name and the country as additional information in the hover message for each city on the map.

      Linear Regression conclusions

        The r^2 value for the relationship between northern hemisphere's latitude and max temperature indicates a low relationship between the two variables.
The r^2 value for the relationship between southern hemisphere's latitude and max temperature indicates a moderate relationship between the two variables.

        The r^2 value for the relationship between northern hemisphere's latitude and humidity indicates no relationship between the two variables.
The r^2 value for the relationship between southern hemisphere's latitude and humidity indicates no relationship between the two variables.

        The r^2 value for the relationship between northern hemisphere's latitude and cloudiness indicates no relationship between the two variables.
The r^2 value for the relationship between southern hemisphere's latitude and cloudiness indicates no relationship between the two variables.

        The r^2 value for the relationship between northern hemisphere's latitude and wind speed indicates no relationship between the two variables.
The r^2 value for the relationship between southern hemisphere's latitude and wind speed indicates no relationship between the two variables.

  References
  
      OpenWeatherMap and the API key = 019a7afc903582138139e6e26b7cc0d4

      Geoapify and the API key = 6a78b13499cf4dae99c4962e543aad2f
      










          
