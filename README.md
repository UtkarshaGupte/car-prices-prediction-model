# Car-Prices-Prediction

The goal was to understand how exactly the prices vary with the independent variables which can be used by the management to manipulate the designs of the cars and their business strategy. Various Machine Learning Models were trained to find the significant variables in predicting the price of a car, how well does the variables describe the Car Prices. To acheive the goal, two models were trained:

Generalized Linear Model (GLM)
Gradient Boosting Machine Model (GBM)
The GLM model after performing model tuning ran with a performance of RMSE value of 36293, MAE of 21881, and R^2 of 0.81 on the test dataset.

Interpreted finally trained GLM model by plotting permutation feature importance

The GBM model after model tuning performed with an RMSE value of 18736, MAE of 8083, and R^2 of 0.95 on the test dataset.

Interpreted final GBM model by plotting global feature importance using shapley values, permutation feature importance, summary plot and individual observation analysis using shapley values.

The most important feature was found out to be year, it has a positive correlation with the prices of cars. The higher the value of year feature(the recent model it is), the higher is the Car Price(impact on model output). Meaning the cars manufactured in the recent years will have higher prices.The second important feature was found to be model. The next was the mileage having negative correlation with Car Price. The higher the mileage, the lower is the price.
