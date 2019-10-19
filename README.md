COMP257 Data Science Portfolio 
===

Ariana Rozsnyoi

Repository of portfolio projects for semester 2 2019.

**Portfolio 1: Analysis of CSV data for cycling**

An analysis of cycling data derived from the apps Strava and GoldenCheetah. The two datasets were joined using the join method in Pandas to form one dataset for analysis. The portfolio explores the relationships between the different variables such as: Distance, Average Speed, Heart Rate, Training Stress Score, Avergage Power, Workout Type and Elevation Gain. Activity summary plots are also generated using the timeseries/datatime functionality in Pandas.

**Portfolio 2: Appliances energy prediction data**

An analysis of energy prediction data based on the paper: 

Data driven prediction models of energy use of appliances in a low-energy house. Luis M. Candanedo, Véronique Feldheim,    Dominique Deramaix. Energy and Buildings, Volume 140, 1 April 2017, Pages 81-97, ISSN 0378-7788, http://dx.doi.org/10.1016/j.enbuild.2017.01.083.

The data was retrieved from the authors [Github Page](https://github.com/LuisM78/Appliances-energy-prediction-data).
    
The portfolio reproduces some of the results in the paper predicting energy usage of a house based on IoT measurements of temperature, humidity and weather observations. 

The results that were reproduced in the portfolio include:
- Various plots to visualize the energy consumption over the period of the data and the distribution of the data
- Correlation Matrix to visualize the relationship between the energy consumption variables
- HeatMap plot
- Performance of linear regression model
- Recursvie Feature estimation (RFE)

**Portfolio 3: Clustering Visualisation**

This porfolio visulazies the unsupervised learning algorithm K-Means clustering.


The iterative process of the algorithm is implemented in a separate cell to visulaize the clustering process and to demonstrate how the centroids are updated. The process is repeated until the centroid estimate has not changed significantly.



