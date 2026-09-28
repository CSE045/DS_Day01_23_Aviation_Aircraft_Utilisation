# DS_Day01_23 - Aviation Aircraft Utilisation Analysis

## Project Title
Is the Airline Using Its Aircraft Efficiently?

## Industry
Aviation

## Objective
The objective of this project is to analyse aircraft utilisation,
passenger load factor, route performance, and aircraft efficiency
using flight and passenger data.

## Dataset

The dataset contains:

- Flight ID
- Aircraft Type
- Route
- Flight Duration
- Turnaround Time
- Route Distance
- Passenger Capacity
- Actual Passengers

## Analysis Performed

- Data cleaning and validation
- Exploratory Data Analysis
- Passenger Load Factor calculation
- Aircraft type comparison
- Route utilisation analysis
- Low occupancy route identification
- Route-aircraft combination analysis
- Route distance vs passenger utilisation analysis
- Linear Regression

## Key Results

- Average Passenger Load Factor: 78.48%
- Route Distance vs Load Factor Correlation: -0.0455
- Linear Regression MAE: 8.77
- Linear Regression RMSE: 10.46
- Linear Regression R²: -0.0386

## Lowest Load Factor Route-Aircraft Combination

Delhi-Bengaluru + Airbus A320

Passenger Load Factor: 65.28%

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Machine Learning Model

Linear Regression was used to predict Passenger Load Factor
using:

- Flight Duration
- Turnaround Time
- Route Distance
- Passenger Capacity

## Conclusion

The analysis shows an overall passenger load factor of 78.48%.
Some route-aircraft combinations have comparatively low utilisation.
Route distance has almost no meaningful linear relationship with
passenger load factor.

The Linear Regression model achieved an R² of -0.0386, indicating
that additional demand-related variables would be required for
better prediction.

## Dataset Note

The dataset used in this project is a synthetic educational dataset
created to match the requirements of the assignment. It does not
represent real airline operational data.
