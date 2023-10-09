# Traffic Volume Prediction Project

This project aims to predict the traffic volume on I-94 Interstate highway using various features such as weather conditions, time of the day, and whether the day is a holiday or not. The dataset used for this project was obtained from Kaggle and contains hourly data from 2012 to 2018.

## Dataset Information

The dataset contains hourly data on the traffic volume for westbound I-94, a major interstate highway in the US that connects Minneapolis and St. Paul, Minnesota. The data was collected by the Minnesota Department of Transportation (MnDOT) from 2012 to 2018 at a station roughly midway between the two cities.

- **Instances:** 48,204
- **Attributes:** 9

### Attribute Information

1. **holiday:** Categorical variable indicating whether the date is a US national holiday or a regional holiday (such as the Minnesota State Fair).
2. **temp:** Numeric variable showing the average temperature in kelvin.
3. **rain_1h:** Numeric variable showing the amount of rain in mm that occurred in the hour.
4. **snow_1h:** Numeric variable showing the amount of snow in mm that occurred in the hour.
5. **clouds_all:** Numeric variable showing the percentage of cloud cover.
6. **weather_main:** Categorical variable giving a short textual description of the current weather (e.g., Clear, Clouds, Rain, etc.).
7. **weather_description:** Categorical variable giving a longer textual description of the current weather (e.g., light rain, overcast clouds, etc.).
8. **date_time:** DateTime variable showing the hour of the data collected in local CST time.
9. **traffic_volume:** Numeric variable showing the hourly I-94 reported westbound traffic volume.

## Tools and Libraries Used

The following tools and libraries were used in this project:

- `pandas` and `numpy` for data manipulation
- `matplotlib` and `seaborn` for data visualization
- `dataprep.eda` for exploratory data analysis (EDA)
- `scikit-learn` for machine learning tasks (e.g., model selection, evaluation, preprocessing)
- `XGBoost` for gradient boosting
- `MLPRegressor` for neural network regression

## Getting Started

To run this project, ensure we have the necessary libraries installed. We can install them using `pip`:

```bash
pip install pandas numpy matplotlib seaborn dataprep scikit-learn xgboost
```
## Script Explanation

pandas and numpy: Python libraries for data manipulation and numerical operations.
matplotlib and seaborn: Libraries for data visualization.
dataprep.eda.create_report: A function from the dataprep library for generating an exploratory data analysis (EDA) report.
sklearn: The scikit-learn library for machine learning tasks.
xgboost: A gradient boosting library for machine learning.
MLPRegressor: A neural network regressor from scikit-learn.
Various regressors like LinearRegression, Lasso, Ridge, DecisionTreeRegressor, RandomForestRegressor for modeling.
Various metrics for evaluating the models: mean_squared_error, mean_absolute_error, r2_score.
Various scalers and encoders for preprocessing the data: RobustScaler, MinMaxScaler, LabelEncoder, StandardScaler.


