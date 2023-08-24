# Seoul Bike-Sharing Demand Regression Model

## Seoul Bike Sharing Demand Prediction
This project uses machine learning to predict the number of bikes rented per hour in the Seoul Bike Sharing System.

## Data
The data used for this project is from the UCI Machine Learning Repository. It contains 8760 observations, each of which represents the number of bikes rented per hour in Seoul, South Korea. The data also includes weather information (temperature, rainfall, etc.) as well as date information (time of day, functioning days, etc.).

## Libraries
The following libraries were used in this project:
- NumPy and pandas were used to represent and manipulate the data
- Seaborn and MatPlotLib were used to visualize the data
- scikit-learn was used to transform the data (encoding text categories, standardize & scale, etc.), create pipelines, and test different models

## Results
The best model that I found was a random forest regressor. It has a root mean squared error of 233.76.

![image](https://github.com/edisonwang03/seoul-bike-sharing-demand/assets/49788106/cbc4b1ca-b4c5-4e25-84e2-ed329e202bd7)

## Future Work
Some possible future work for this project includes:
- Using more data to train the model
- Trying other machine learning algorithms
- Improving the data preprocessing steps
