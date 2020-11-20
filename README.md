# OPEN THE IPYNB FILE TO CHECK THE DETAILED REPORT
# RESTAURANT-REVENUE-PREDICTION
TFI has provided a dataset with 137 restaurants in the training set, and a test set of 100000 restaurants. The data columns include the open date, location, city type, and three categories of obfuscated data: Demographic data, Real estate data, and Commercial data. The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis.
# PYTHON LIBRARIES USED:
1. PANDAS
2. NUMPY
3. SEABORN
4. SKLEARN.PREPROCESSING
5. SKLEARN.METRICS
6. SKLEARN.MODEL_SELECTION
7. SKLEARN.LINEAR_MODEL
8. XGBOOST
9. LIGHTGBM
10. MATH
11. eli5

# This notebook contains the following:
1. FEATURE ENGINEERING
2. PREDICTIVE ANALYSIS
3. MACHINE LEARNING-MODEL IMPLEMENTATION
   * XGBREGRESSOR
   * LGBMREGRESSOR
# Data fields:
1. Id : Restaurant id. 
2. Open Date : opening date for a restaurant
3. City : City that the restaurant is in. Note that there are unicode in the names. 
4. City Group: Type of the city. Big cities, or Other. 
5. Type: Type of the restaurant. FC: Food Court, IL: Inline, DT: Drive Thru, MB: Mobile
6. P1, P2 - P37: There are three categories of these obfuscated data. Demographic data are gathered from third party providers with GIS systems. These include     population in any given area, age and gender distribution, development scales. Real estate data mainly relate to the m2 of the location, front facade                of the location, car park availability. Commercial data mainly include the existence of points of interest including schools, banks, other QSR operators.
7. Revenue: The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis. Please note that the values are transformed so they don't mean real dollar values. 
# THE END
