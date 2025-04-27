# Phoenix-Crime-Data
- This project analyzes and visualizes crime data geographically using Python.
- The primary goal is to plot crime incidents on a map based on their latitude and longitude.
## Overview
- Load and clean crime data.
- Visualize crime locations on a geographical map.
- Interactive map for better insights into crime distribution.
## How to Run
- Clone or download this repository.
- Open the Crime_Data.ipynb notebook.
- Run all cells sequentially.

*Important:*
- Re-run the notebook cells after initial execution if the geographical map does not appear.
- Some visualizations (especially maps) require a second run due to rendering issues in Jupyter environments.
## Requirements
- Python 3.8+
- Libraries:
   - pandas
   - folium
   - geopandas (optional for advanced features)
   - matplotlib (for supporting visualizations)

*You can install the requirements via:*
- pip install pandas folium geopandas matplotlib
## Files
- Crime_Data.ipynb — Main notebook containing the full data workflow and map generation.
## Output
- An interactive crime map plotted with location markers.
- Cleaned crime data ready for further analysis.
## Notes
- Make sure your environment supports rendering folium maps (works best on JupyterLab or VS Code with Jupyter extension).
- After loading and processing, you might need to re-run the final map rendering cells to display the map properly.