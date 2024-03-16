# Weather Prediction and Analysis using Matplotlib and Scikit-Learn
## Introduction
  This project aims to predict and analyze weather data using machine learning techniques implemented with Matplotlib and Scikit-Learn. The dataset used in this project is the Mars Weather dataset.

## Prerequisites
  Before running the code, make sure you have the following installed:

  Python (version 3.x)
  Pandas
  Matplotlib
  Scikit-Learn
  Installation
  Clone this repository to your local machine.

```bash
git clone https://github.com/your_username/your_repository.git
```
  Navigate to the cloned repository.
```bash
cd your_repository
```
  ## Usage
  Ensure you have the dataset mars-weather.csv available in the specified path.
  Run the weather_prediction.py script to execute the weather prediction and analysis.
  ```bash
  python weather_prediction.py
```
  View the generated plots for analysis.
  ## Code Explanation
  The dataset is loaded using Pandas from the provided CSV file.
  Missing values in the dataset are imputed using the mean strategy.
  Linear regression model is trained using Scikit-Learn's LinearRegression class.
  Predictions are made using the trained model.
  Actual vs. predicted values are plotted using Matplotlib.
  Additional analysis, such as plotting the coefficients of the linear regression model, is performed.
  Files Included
  weather_prediction.py: Python script containing the code for weather prediction and analysis.
  mars-weather.csv: Dataset containing weather data.
  README.md: Readme file containing instructions and information about the project.
