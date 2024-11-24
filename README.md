# Transit Planner

The Green Transit Solutions and Route Planner for Metro Commuters aims to visualize routes for transit planning. The project initializes the map and loads various layers such as transit lines (green and blue line), stops, and markers using ipyleaflet and geopandas. The map interactivity is facilitated through map clicks to add markers and a button to calculate the routes using Google Maps API for directions. Beyond the visualizations, users can choose between driving and transit mode, input origin and destination either via addresses or markers, select time preferences, preference for routes, and see options under the layers legend. This project dynamically updates the map to visualize selected routes, removes old layers, and adds new polyline layers to represent the new route. The project made this interface user friendly with widgets to enhance the overall user experience. 

### Run this application
Open the link below, wait a minute or two, and it will launch an interactive Jupyter Notebook containing my code. Input your Google Maps API Key in the file, and then run all the cells (click Run at the top--> Run All Cells) and an interactive map application will appear.

https://mybinder.org/v2/gh/briollaure/TransitPlanner/main?labpath=TransitPlanner.ipynb

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/briollaure/TransitPlanner/main?labpath=TransitPlanner.ipynb)
