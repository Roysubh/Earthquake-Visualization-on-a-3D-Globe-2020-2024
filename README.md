#Earthquake Visualization on a 3D Globe (2020–2024)

This project visualizes global earthquake data from 2020 to 2024 on a 3D interactive globe using Python. 
It provides an engaging way to explore the distribution of earthquakes around the globe based on their magnitude, depth, and location.

Overview:
  Earthquakes are natural phenomena that occur globally and are a vital part of geological processes. 
  This project uses data from the USGS Earthquake API to create a 3D globe visualization where:
    1. The size of the markers represents earthquake magnitude.
    2. The color of the markers depicts the earthquake intensity (higher magnitude = redder color).
    3. Interactive features allow users to explore detailed information about each earthquake.

  This project is ideal for educational purposes, geospatial data enthusiasts, and researchers interested in earthquake distribution.

Features:
  1. Interactive 3D Globe: Rotate, zoom, and explore earthquakes visually.
  2. Dynamic Marker Sizes and Colors: Earthquake magnitudes influence marker size and color.
  3. Colorbar Legend: Displays the range of earthquake magnitudes.
  4. High-Resolution Visualization: Customizable globe projection with coastlines, oceans, and landmasses.

Libraries Used:
  The project relies on the following Python libraries:
    1. pandas: For data manipulation and handling.
    2. plotly: For creating the interactive 3D globe and visualizations.
    3. imageio: For generating animations (if needed).
    4. imageio[ffmpeg]: For encoding video animations.
    5. kaleido: For exporting visualizations to static files (e.g., PNG or PDF)

Data Source:
  Earthquake data is fetched from the USGS Earthquake Catalog using the following API endpoint:
  Base URL: https://earthquake.usgs.gov/fdsnws/event/1/query
  Parameters:
    1. format=geojson: Data format.
    2. minmagnitude=5.0: Minimum earthquake magnitude.
    3. orderby=time: Sorts the earthquakes by time (most recent first).
    4. starttime and endtime: Defines the date range for earthquake data.

Conclusion:
  This project demonstrates:
    1. The global distribution of earthquakes based on magnitude.
    2. The effectiveness of geospatial visualization techniques for understanding natural phenomena.
    3. How Python and Plotly can be used to create visually appealing, interactive maps.
    
  Key Insights:
    1. Most earthquakes occur along tectonic plate boundaries.
    2. The Pacific Ring of Fire shows a dense distribution of high-magnitude earthquakes.
    3. Interactive visualizations allow for intuitive exploration of large datasets.
    
  This project can be extended further for:
    1. Animation of earthquake occurrences over time.
    2. Integration with additional datasets (e.g., tsunami warnings or population density).

License:  
  This project is licensed under the MIT License, allowing free use, modification, and distribution with attribution. See the LICENSE file for details.
