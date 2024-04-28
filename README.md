# Unemployment Rate Forecasting by Age Group

## Overview
This GitHub repository hosts a Python project that performs comprehensive analysis and forecasting of unemployment rates across various age groups. Utilizing various statistical models and data visualization techniques, this project aims to uncover patterns, distributions, and potential anomalies within unemployment data, as well as predict future trends.

## Features

### Data Visualization
- **Histograms of Age Group Distributions**: Visualize the frequency distribution for different age groups to understand the variability within the data.
- **Box Plots Over Time**: Explore how the statistical distribution of unemployment rates for each age group varies over the years.

### Correlation Analysis
- **Heatmaps**: Employ heatmaps to visualize the correlation between numerical features in the dataset, identifying potentially interesting patterns that may influence unemployment trends.

### Anomaly Detection
- **Isolation Forest**: Implement the Isolation Forest algorithm to detect outliers within the data, which can help in identifying data points that deviate significantly from the norm.

### Forecasting
- **SARIMAX Model**: Use the Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors model to forecast unemployment rates for the next 10 years, providing insights into future trends.

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib for data visualization
- Seaborn for heatmap generation
- Scikit-Learn for anomaly detection
- Statsmodels for time-series analysis

## Installation

Clone the repository and install the necessary packages:

```bash
git clone https://github.com/Zzl85199/unemployment_rate_predict.git
cd unemployment_rate_predict
pip install -r requirements.txt
```

## Usage

To run the analysis, navigate to the project directory and start the Jupyter Notebook:

```bash
jupyter notebook unemployment_rate_predict.ipynb
```

This will open the notebook in your web browser where you can execute the provided code cells to see the analysis results and visualizations.

## Visualizations

- **Distribution of Age Groups**:
  - Generates histograms showing the frequency of unemployment rates across different age groups.

- **Unemployment Trends by Year**:
  - Displays box plots to visualize the trends and variations in unemployment rates by year for each age group.

- **Correlation Matrix**:
  - A heatmap to illustrate the correlations between different numerical features.

- **Anomaly Detection**:
  - Visual representation of anomalies detected in the dataset using the Isolation Forest method.

- **Forecasting Unemployment Rates**:
  - Line plots showing predicted unemployment rates for the next decade, helping in policy formulation and economic planning.

## Contributing

Contributions to this project are welcome. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-new-feature`.
3. Make your changes and commit them: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin my-new-feature`.
5. Submit a pull request.

## Acknowledgments

- Thanks to all the data providers for making the data available for analysis.

## Contact

For any further inquiries or issues, please contact [zzl] at [jonathan40507@gmail.com].

## Support

If you find any bugs or issues, please report them in the issues section of the GitHub repository, or even better, consider contributing a fix.

