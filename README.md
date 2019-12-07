# Citibike ridership analysis
Citibike (a bike sharing program in NYC) provides comprehensive dataset on their operation through their [homepage](https://www.citibikenyc.com/system-data). The code here is used to cluster daily trip history data to monthly level for better analysis.

In order to get this code run, you need to:
- Create a folder named 'raw_data' and store your Citibike data in it. Citibike data can be found [here](https://www.citibikenyc.com/system-data).
- Run 'data_reduction' module. This will output the data to 'output' folder. I have my results included in the folder already. This include: monthly ridership in different user types, genders, and age groups.
- Run 'data_analysis' for visualization.

You may edit 'data_reduction' module to cluster other types of characteristics, e.g. travel distance, origin-destination pair, and so on.
