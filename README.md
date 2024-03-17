Linear Regression using OneHotEncoder
Introduction

This Python script demonstrates the use of linear regression with OneHotEncoder for predicting housing prices. The script utilizes the HousingDB dataset, containing housing-related features such as lot size, number of bedrooms, bathrooms, stories, garage capacity, and additional amenities like rec room, full basement, and air conditioning.
Key Statistics

The dataset's key statistics are as follows:

    Price: Mean price: $68,121.60, Standard deviation: $26,702.67, Minimum: $25,000, Maximum: $190,000.
    Lotsize: Mean: 5150.27, Standard deviation: 2168.16, Minimum: 1650, Maximum: 16200.
    Bedrooms: Mean: 2.97, Standard deviation: 0.74, Minimum: 1, Maximum: 6.
    Bathrooms: Mean: 1.29, Standard deviation: 0.50, Minimum: 1, Maximum: 4.
    Stories: Mean: 1.81, Standard deviation: 0.87, Minimum: 1, Maximum: 4.
    Garage Capacity: Mean: 0.69, Standard deviation: 0.86, Minimum: 0, Maximum: 3.

Data Preprocessing

    OneHotEncoder is used to encode categorical features (rec room, full basement, air conditioning).
    The dataset is split into training and test sets with a test size of 20%.
    Data scaling is performed using StandardScaler.

Model Building

    A linear regression model is trained on the training data.
    Predictions are made on the test data, and model performance metrics are calculated.

Results

The linear regression model's performance metrics are as follows:

    R-squared (R2): 0.54
    Adjusted R-squared: 0.53
    Mean Absolute Error (MAE): $12,127.85
    Mean Squared Error (MSE): $253,496,059.87
    Root Mean Squared Error (RMSE): $15,921.56

Conclusion

The linear regression model using OneHotEncoder achieved an R-squared value of 0.54, indicating that the model explains 54% of the variance in housing prices. Further optimization and feature engineering could potentially improve model performance.
License

This project is licensed under the MIT License.
