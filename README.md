# Rainfall_Prediction_System

Dataset
The dataset weatherAUS.csv includes historical weather information such as temperature, humidity, pressure, and more. The target variable is RainTomorrow, which indicates if it will rain the next day.

Features Used
Location: Location name
MinTemp: Minimum temperature
MaxTemp: Maximum temperature
Rainfall: Amount of rainfall
WindGustDir: Direction of wind gust
WindGustSpeed: Speed of wind gust
Humidity9am and Humidity3pm: Humidity in the morning and afternoon
Pressure9am and Pressure3pm: Atmospheric pressure
And other relevant weather features.

Model
This project uses a Random Forest Classifier for rainfall prediction. The model is trained on historical weather data and uses various preprocessing steps:
Missing Value Imputation: Replaces missing values using the most frequent values.
Label Encoding: Converts categorical features to numeric.
Standard Scaling: Scales features for optimal model performance.

Performance
The model is evaluated using metrics such as:
Accuracy Score
Classification Report
Confusion Matrix
