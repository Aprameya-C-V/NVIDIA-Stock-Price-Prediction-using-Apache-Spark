# NVIDIA Stock Price Prediction using Apache Spark

This project utilizes Apache Spark and Python to predict the stock prices of NVIDIA Corporation (NVDA). By leveraging historical stock data and machine learning models implemented in Apache Spark, this project aims to forecast future stock prices and analyze the performance metrics of the predictive models.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methods and Technologies Used](#methods-and-technologies-used)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Stock price prediction is a crucial task in financial markets for making informed investment decisions. This project focuses on predicting the closing stock prices of NVIDIA using historical data. Apache Spark is chosen for its capability to handle large-scale data processing and machine learning tasks efficiently.

## Dataset

The dataset used in this project is sourced from Yahoo Finance and covers the daily stock prices of NVIDIA from January 1, 2010, to June 17, 2024. The dataset includes the following columns:
- Date
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

## Methods and Technologies Used

- **Apache Spark:** For distributed data processing and implementing machine learning models.
- **Python:** Programming language used for data manipulation, modeling, and visualization.
- **Pandas:** For data manipulation and analysis in Python.
- **Matplotlib:** Python library for plotting graphs and visualizations.
- **Statsmodels:** Used for time series analysis and forecasting.
- **Scikit-learn:** For machine learning models and performance metrics.

## Project Structure

- **`nvda_data.csv`:** CSV file containing the raw dataset from Yahoo Finance.
- **`NVIDIA_Stock_Prediction.ipynb`:** Jupyter Notebook containing the entire project workflow, including data preprocessing, model building, evaluation, and forecasting.
- **`README.md`:** This file providing an overview of the project, setup instructions, usage, and results.
- **`requirements.txt`:** File listing all Python libraries required to run the project.

## Setup Instructions

To run this project locally, follow these steps:

1. Clone this repository:
   ```
   git clone https://github.com/Aprameya-C-V/NVIDIA-Stock-Price-Prediction-using-Apache-Spark.git
   cd NVIDIA-Stock-Price-Prediction-using-Apache-Spark
   ```

2. Install the required Python libraries:
   ```
   pip install -r requirements.txt
   ```

3. Ensure you have Apache Spark installed and configured locally or on a cluster.

## Usage

1. Open and execute the `NVIDIA_Stock_Prediction.ipynb` notebook using Jupyter or any compatible environment.
2. Follow the notebook to understand the data preprocessing steps, model building, evaluation, and forecasting.
3. Modify or extend the notebook as needed for further analysis or improvements.

## Results

The project achieves high accuracy in predicting NVIDIA stock prices using the implemented machine learning models in Apache Spark. Key performance metrics include:

- **RMSE:** Root Mean Squared Error
- **MAE:** Mean Absolute Error
- **R-squared:** Coefficient of Determination

Detailed performance metrics and results are documented within the `NVIDIA_Stock_Prediction.ipynb` notebook.

## Contributing

Contributions to improve the project, add new features, or fix issues are welcome. Please fork the repository, make changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the LICENSE file for details.

---

