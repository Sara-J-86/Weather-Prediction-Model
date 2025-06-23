# Weather Prediction and Climate Change Analysis
This project is divided into 2 parts. Part 1 involves developing an ML model using the GHCN dataset, which contains historical weather records. Part 2 involves performing Climate Change analysis using Earth
Surface Temperature Data. Both datasets are first cleaned and processed to prepare them for the Ridge Regression models. 

Ridge Regression, a type of linear regression with L2 regularization, can be used for weather prediction by modeling historical weather data to forecast future conditions. It is particularly useful when dealing with multicollinearity among weather variables, a common issue in weather datasets. The regularization aspect of ridge regression helps prevent overfitting and improves the model's generalization to unseen data. 
The first model is used to analyse short-term weather patterns, whereas the second is used to understand long-term climate variations.

The accuracy metric used is Mean Absolute Error (MAE) which calculates the average of the differences between the actual and predicted values. The value was reduced from 5.14 to 4.7 by adjusting the predictors in the weather dataset. 

## Ridge Regression Plot for Climate Change Analysis
![](assets/visualisations/ridgeregression_climate.png)
Climate Change is analysed by calculating average land temperature for each year and plotting the values from mid-19th to 20th century. The graph provides evidence for global warming, as indicated by an upward trend in temperature, especially in recent decades.
