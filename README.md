# California Houses Regression Project

This project aims to predict the median house value in different districts of California based on various features. We use machine learning techniques to build a model that can help better understand the real estate market in the region and make accurate predictions about house prices.

## About the Project

The dataset used contains information such as latitude, longitude, housing median age, total number of rooms, total number of bedrooms, population, median income, median house value, and proximity to the ocean. We use these features to gain insights into patterns and trends in the California real estate market.

## Insights Obtained

During the exploratory data analysis, we obtained several valuable insights:

1. **Median House Age and Prices:** We found no significant correlation between the median age of houses and prices. This suggests that other factors have a greater influence on property values.

2. **Location and Prices:** We observed that houses located near the coast tend to have higher prices. This indicates that location is an important factor in determining house prices.

3. **Median Income and House Prices:** We found a strong correlation between median family income and house prices. Areas with higher median income tend to have more expensive houses.

4. **Population Density and Prices:** Contrary to expectations, we discovered that areas with more expensive houses are not necessarily less populous.

5. **Median Income and Location:** Individuals with higher median income tend to prefer living near the coast.

## Results of the Best Model (Random Forest Best param)

After training various regression models, the model that performed best was the Random Forest with the following parameters:

- Maximum Depth: 20
- Minimum Samples per Leaf: 2
- Minimum Samples to Split a Node: 5
- Number of Estimators: 350

### Model Results:

- **Mean Absolute Error (MAE):** [30172.15]
- **Mean Absolute Percentage Error (MAPE):** [0.17]
- **Root Mean Squared Error (RMSE):** [46466.93]
- **Model Score:** [0.841416]

These results indicate that the Random Forest model is capable of making accurate predictions about house prices in California, with a good score and low errors.

## Conclusion

This project provides valuable insights into the California real estate market and offers a precise model for predicting house prices based on different characteristics. The results can be useful for real estate professionals, investors, and urban planners to make informed and strategic decisions.
