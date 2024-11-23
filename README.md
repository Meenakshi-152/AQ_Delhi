# AQ_Delhi
## Pollution Data Visualization
This repository contains the code and resources to visualize air pollution data for all stations in Delhi over a period of one month, specifically focusing on PM 2.5 levels. The data is sourced from the Central Pollution Control Board (CPCB) and covers the period from 19th October 2024 to 19th November 2024.

Air pollution is a critical environmental issue, and this project aims to analyze and visualize the PM 2.5 levels across multiple stations in Delhi. We use matplotlib for animations and seaborn for heatmaps, presenting pollution levels dynamically over time.

### The key tasks in this project include:
1) Daily Pollution Animation: A bar chart animation showing daily pollution levels at different stations.
2) Heatmap Visualization: A heatmap displaying the pollution levels across different stations and days.

### Key Features
1) Data Animation: An animated bar chart that updates daily pollution levels for each station.
2) Heatmap Visualization: A heatmap showing pollution levels across multiple stations over the month.
3) Date Filtering: The data for the specific period (19th October 2024 to 19th November 2024) is processed, ensuring accurate time-series visualization.
4) Station-Specific Analysis: The dataset excludes stations that lack valid data (e.g., Chandni Chowk).

### Data
The data used in this project is sourced from the [Central Pollution Control Board (CPCB)](https://cpcb.nic.in/). It contains hourly PM 2.5 values for various stations in Delhi over the month of October-November 2024. The colours used are taken from [geeks for geeks](https://www.geeksforgeeks.org/html-color-codes/).

The original data is converted in a CSV format, and the analysis focuses specifically on the PM 2.5 parameter.

### Files
1) AQnew.csv: The main CSV file containing the pollution data for various stations.
2) pollution_daily_animation_fixed.gif: The generated animation of daily pollution levels (as a GIF).
3) Pollution_Level_Heatmap.png: Heatmap visualization showing pollution levels across stations and days.

### Outputs
1) Pollution Daily Animation: The animation shows how pollution levels at each station change daily.
2) Heatmap: A heatmap providing a clear view of pollution levels over time for all stations.
