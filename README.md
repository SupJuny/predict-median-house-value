# predict-median-house-value
build a multiple linear regression model to predict the median house value based on various features.

## Dataset Description
The dataset, housing.csv, contains the following columns: 
1. longitude: Longitude of the location of the house.
2. latitude: Latitude of the location of the house.
3. housing median age: Median age of the house.
4. total rooms: Total number of rooms in the house.
5. total bedrooms: Total number of bedrooms in the house.
6. population: Population in the area around the house.
7. households: Number of households in the area around the house. 8. median income: Median income of the households in the area.
9. median house value: Median value of the house.
10. ocean proximity: Proximity to the ocean (e.g., < 1H OCEAN, INLAND, etc.)

## Tasks
1. Load the dataset and perform initial exploratory data analysis, including visualizing the relationship between different variables and the median house value.
2. Handle any missing values, if present.
3. Convert categorical variables (like ocean proximity) to numerical format using ap- propriate encoding techniques.
4. Split the dataset into a training set and a testing set.
5. Build a multiple linear regression model using all the features to predict the median house value.
6. Estimate the coefficients of the model.
7. Evaluate the model using metrics like R-squared, RMSE, etc. on the testing set.
8. Conduct variable selection using a method of your choice (e.g., backward elimination, forward selection, or LASSO) to determine which variables significantly predict the median house value.
9. Build another model using the selected variables.
10. Compare the performance of the two models (with all features vs. selected features) on the testing set.
11. Use the better-performing model to predict the median house value for a location with the following details:
• longitude: −122.25
• latitude: 37.85
• housing median age: 40 years
• total rooms: 880
• total bedrooms: 129
• population: 322
• households: 126
• median income: 8.3
• ocean proximity: < 1H OCEAN
