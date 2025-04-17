# LasVegas_Robbery_Analysis
A Jupyter Notebook analyzing point data of reported robberies in Las Vegas, Nevada. Uses GIS techniques and Python libraries for spatial analysis.

patial Autocorrelation in Las Vegas Robberies
By Calvin Hahn
This project explores the spatial autocorrelation of reported robberies in Las Vegas, Nevada, using GIS techniques and statistical analysis. With a dataset of 3,726 robbery incidents, the study examines whether these crimes cluster in specific areas or are randomly distributed across the city.

Key Techniques Used:
Data Processing: Used pandas and geopandas to clean and structure the robbery dataset.

Spatial Visualization: Created maps using folium, matplotlib, and seaborn to identify robbery patterns.

Statistical Analysis: Applied Moran's I and Local Moran's I to evaluate spatial clustering.

Spatial Aggregation: Calculated mean centers, Manhattan median, and Euclidean median to find robbery hotspots.

Spatial Join: Integrated census tract data to analyze crime in relation to population density.

LISA Clusters & Heat Maps: Used Local Indicators of Spatial Association (LISA) to identify areas with high crime concentrations.

Findings & Conclusions:
Robbery incidents appear evenly distributed across Las Vegas overall, meaning that at a broad scale, crimes do not cluster significantly.

Local analysis, however, reveals specific hotspots where robberies cluster due to neighborhood factors like shopping centers or urban hubs.

The transit system (few trains, mostly buses) may influence crime patterns, as train stations typically act as crime hotspots in other cities.

The casino-driven economy and sprawling urban design create a unique crime distribution compared to older cities with more concentrated urban centers.

Moran’s I analysis suggests limited spatial autocorrelation overall, but local analysis reveals distinct crime clusters that warrant further study.

Personal Takeaways:
Throughout the project, valuable insights were gained in spatial analysis, GIS techniques, and crime pattern interpretation. Working with spatial statistics like Moran’s I, centrography, and spatial joins helped refine analytical skills and reinforced the importance of understanding local crime trends beyond surface-level population density effects.
