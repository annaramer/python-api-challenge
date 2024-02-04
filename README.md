# python-api-challenge
- Module 6 Python API Challenge
- WeatherPy and VacationPy

## WeatherPy
- WeatherPy is a project that generates random geographic coordinates, identifies nearby cities using `citipy`, and retrieves weather data for these cities from the OpenWeatherMap API. The project also includes visualizations to showcase relationships between weather variables and latitude.

### Requirements
- Python community for support and resources.
- Requests
- Citipy
- OpenWeatherMap for providing weather data via their API.
- Matplotlib, Pandas, NumPy, and Citipy for data visualization and city identification.


### Usage
- Run the `WeatherPy.ipynb` notebook to generate random coordinates, identify cities, and fetch weather data.
- Visualize the relationships between latitude and weather variables using scatter plots.
- Linear regression analysis is performed to understand the correlations.


## VacationPy
- VacationPy builds on the WeatherPy project and focuses on creating visualizations using GeoViews and finding ideal vacation spots based on weather conditions.

### Requirements
- Python community for support and resources.
- Requests
- Geoapify for providing the API to find nearby hotels.
- GeoViews and HoloViews for interactive geographical visualizations.
- HoloViews

### Usage
- Run the `VacationPy.ipynb` notebook to visualize city data on a map, with the size of points representing humidity.
- Narrow down cities based on ideal weather conditions.
- Create a DataFrame (`hotel_df`) to store hotel information.
- Use the Geoapify API to find hotels within 10,000 meters of each city's coordinates.
- Visualize the final map with hotel names and country information.
