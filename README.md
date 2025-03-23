# Capstone Project: Forecasting Turkish Construction Company Revenue with Earthquake Correlation Analysis (ARIMA)

This repository contains the code and resources for a capstone project focused on forecasting a Turkish construction company's revenue using ARIMA modeling and analyzing the potential correlation between actual earthquakes and revenue fluctuations.

## Project Overview

The primary objective of this project is to develop an accurate time-series forecasting model for a Turkish construction company's revenue using ARIMA. Additionally, this project investigates the potential correlation between earthquake occurrences in Turkey and the company's revenue. The project aims to determine whether earthquakes have a statistically significant impact on revenue, potentially due to increased construction demands following such events.

## Repository Contents

-   `capstone.ipynb`: Jupyter Notebook containing the data analysis, preprocessing, correlation analysis, ARIMA model training, and evaluation code.
-   `README.md`: This file, providing an overview of the project.
-   (Potentially other files such as data files, saved models etc.)

## Data

The dataset used in this project includes:

-   **Construction Company Revenue Data:** Time-series data representing the company's revenue over a specific period.
-   **Earthquake Data:** Historical earthquake data for Turkey, including date, magnitude, and location.

(Include the source of the data if available)

## Methodology

The project follows these key steps:

1.  **Data Acquisition and Exploration:**
    -   Loading the revenue and earthquake datasets.
    -   Performing initial data exploration and visualization.
    -   Identifying patterns and trends in both datasets.

2.  **Data Preprocessing:**
    -   Cleaning and formatting the data.
    -   Time-series data manipulation and aggregation.
    -   Feature engineering to create relevant earthquake-related features.

3.  **Correlation Analysis:**
    -   Performing statistical tests to determine the correlation between earthquake events and revenue.
    -   Analyzing the time lag between earthquakes and potential revenue impacts.
    -   Visualizing the correlation results.
    -   **Result:** The correlation analysis didn't show any significant correlation between earthquakes and the construction company's revenue.

4.  **ARIMA Model Selection and Training:**
    -   Splitting the revenue data into training and testing sets.
    -   Identifying optimal ARIMA parameters (p, d, q) using techniques like ACF, PACF, and auto_arima.
    -   Training the ARIMA model on the revenue data.
    -   Evaluating the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE).

5.  **Model Evaluation:**
    -   Evaluating the ARIMA model's performance on the test set.
    -   Analyzing the model's predictions and residuals.

6.  **Interpretation and Conclusion:**
    -   Drawing conclusions about the revenue forecasting using ARIMA.
    -   Confirming the lack of a significant correlation between earthquakes and revenue.

## Libraries Used

-   `pandas`
-   `numpy`
-   `scikit-learn`
-   `matplotlib`
-   `seaborn`
-   `statsmodels` (for ARIMA)
-   `pmdarima` (for auto_arima)
-   (Any other relevant libraries)

## Running the Code

1.  Clone the repository:

    ```bash
    git clone [https://github.com/erenkbgc/capstone_project.git](https://www.google.com/search?q=https://github.com/erenkbgc/capstone_project.git)
    cd capstone_project
    ```

2.  Install the required libraries:

    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn statsmodels pmdarima
    # Install other libraries as needed
    ```

3.  Open and run the Jupyter Notebook:

    ```bash
    jupyter notebook capstone.ipynb
    ```

## Results

(Summarize the key findings and the model's performance. Include metrics and visualizations as appropriate.)

For example:

-   The ARIMA model achieved an RMSE of $X$ and an MAE of $Y$ on the test set.
-   The correlation analysis showed no significant correlation between earthquake events and the construction company's revenue.
-   The ARIMA model provided reasonable revenue forecasts based on historical data.

## Future Improvements

-   Incorporate more detailed economic and political factors into the forecasting model.
-   Explore other time-series forecasting models to potentially improve accuracy.
-   Conduct a more in-depth analysis of external factors influencing revenue.
-   Consider adding exogenous variables to the ARIMA model.

## Author

-   erenkbgc

