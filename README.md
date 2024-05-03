# Weather Prediction using Linear Regression
This project aims to predict maximum temperatures using historical weather data from World War II. Initially, a simple linear regression model is employed to predict the maximum temperature. Then, the model is refined using the coefficient of determination (R-squared) to improve its accuracy.

# Dataset
The dataset used for this project is stored in a CSV file named ww-ii-data.csv. This dataset contains historical weather data including the station number (STA), year (YR), month (MO), day (DA), maximum temperature (MaxTemp), and other meteorological features.

# Setup
Ensure you have Python installed on your system.
Install the required libraries using pip:

pip install -r Requirement.txt

# Usage
Running the Code:
Clone this repository or download the ww-ii-data.csv file.
Open a terminal or command prompt and navigate to the project directory.
Run the Python script weatherprediction_Regression.py.

python weatherprediction_Regression.py

# Interpreting the Results:
Mean Absolute Error (MAE) is a measure of the average absolute difference between the predicted and actual values. A lower MAE indicates better performance.
R-squared (R2) score measures the proportion of variance in the target variable that is predictable from the features. It ranges from 0 to 1, where higher values indicate better fit. An R2 score of 1 indicates a perfect fit.

# Conclusion
This project demonstrates the use of linear regression for weather prediction. By utilizing historical weather data, we can build models to forecast maximum temperatures. The refinement of the model using the coefficient of determination helps improve its accuracy.