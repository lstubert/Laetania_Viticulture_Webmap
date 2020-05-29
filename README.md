# Laetanian Viticulture Webmap

See the web map here:

https://lstubert.github.io/#10/41.5363/2.3364

This web map shows the results of an archaeological study about viticulture in ancient Spain: [Viticulture in the Laetanian Region (Spain) during the Roman Period: Predictive Modelling and Geomatic Analysis](https://www.mdpi.com/2076-3263/10/6/206/htm) The approach was to take a data set (point locations) of existing archeological sites and to determine the underlying factors of their distribution. Therefore the script predicts zones of high suitability that were associated with Roman viticulture, based on the location characteristics of the sites. As predictor variables different rasters (for example a digital elevation model and cost distances to ancient settlements) of the study area were used.
Different variable and parameter combinations were tried and the resulting models were compared. The best, here shown, prediction performance was obtained by an expert knowledge model utilizing a combination of predictor variables that is based on specific recommendations on viticulture by Lucius Junius Moderatus Columella, the prominent ancient writer on agriculture in the Roman Empire.

The results indicate that the accessibility of a location and its connectivity to the distribution and trade routes, determined by terrain steepness, was decisive for the development of wine pressing facilities. With the knowledge gained, the ancient cultivated area and number of wine pressing facilities were extrapolated for the entire study region. The results of the best performing model
were visualized in a web map for interactive evaluation. 

The developed Python algorithm, that was used to calculate the model has been designed in a way it can easily be used for other datasets, study regions and even different scientific fields. It is published here:
https://github.com/lstubert/PreMo
