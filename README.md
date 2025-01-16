# Agricultural Data Dashboard: Analysis, Predictions, and Visualizations
This project contains an interactive Streamlit dashboard for visualizing and predicting agricultural export trends. The dashboard enables users to analyze agricultural data, predict export values, and forecast future trends, facilitating data-driven decision-making in the agricultural sector.


You can access the dashboard directly through Streamlit via the bottom provided below, or clone the repository and run it locally on your machine.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://blank-app-151z7fxhmko.streamlit.app/)
### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
# Introduction

A dashboard was created to analyze agricultural data, predict export values, and forecast future trends, enabling data-driven decision-making in the agricultural sector. The tool allows users to select a specific country and commodity, input or adjust production metrics (e.g., export quantity, producer price, production value), and explore historical data through a dynamic, downloadable table. Using a pre-trained linear regression model, the dashboard predicts export values based on user inputs and employs a ARIMA model to generate 20-year forecasts, presenting trends through interactive Plotly visualizations. Additionally, the dashboard includes an Interactive Visualizations section, where users can explore production and export trends across countries, trade balances, and other aggregated metrics, further enhancing the tool’s ability to provide actionable insights.


## Feature 1: Historical Data and Predictions

Users can view the historical data table, copy the latest year's values, input them into the fields on the left, instantly generate a predicted export value, and download the table as a CSV file for personal analysis.
This feature allows users to select a date range, dynamically updating all charts and visualizations to reflect the selected period's data.

![dashboard_instructions](https://github.com/user-attachments/assets/fca9810a-ad3e-4d0b-a630-0fb3cb23a03d)

## Feature 2: Automated Forecast Integration

The dashboard automatically inputs the predicted export value into the forecasting section, allowing users to directly click the "Generate Forecast" button to create a 20-year forecast. Please note that it will take a few seconds to run the prediction.


![dashboard_instructions2](https://github.com/user-attachments/assets/bf242937-539e-44a8-8165-392281d6ff38)

## Feature 3: Interactive Visualization Navigation

After forecasting values, users can navigate to the top menu and move to the "Interactive Visualizations" section. Here, they can explore different visualizations such as maps, line charts, histograms, and more to gain deeper insights.

![dashboard_instructions3](https://github.com/user-attachments/assets/b5c5fbaf-d075-48ec-9fe8-dc899bb10b46)

## Feature 4: Interactive Maps and Trade Balance Visualizations

Users can visualize different maps showcasing production trends, export trends, and import trends. After exploring the maps, users can move to the Trade Balance feature, where they can view a line chart comparing trade balances across multiple countries. The sidebar allows users to add or remove lines representing different countries for customized comparisons. Additionally, users can analyze each country's trade balance independently by selecting a specific country in the sidebar.


![dashboard_instructions4](https://github.com/user-attachments/assets/5672825e-cbea-49b8-9572-9e8107384c66)

## Feature 5: Comparative Bar Chart Visualization

Users can visualize a bar chart comparing different countries. The sidebar allows users to add or remove countries for customized comparisons. Additionally, users can select predefined groups, such as all countries, EU countries, or worldwide countries, for focused analysis. A slider enables interactive selection of the year for dynamic visualization updates.



![dashboard_instructions5](https://github.com/user-attachments/assets/2735e683-1350-4a48-8747-efe2cb04f15a)

## Feature 6: Export Value Visualizations

Users can visualize export values in a line chart for comparisons across multiple countries. Additionally, the export value tree map allows users to select a rectangle, such as one representing Ireland, to analyze its export details more thoroughly.


![dashboard_instructions6](https://github.com/user-attachments/assets/f5572334-2a3e-46b2-a7ee-3543241657a2)

## How to Use the Dashboard

 - Navigate to the desired section using the sidebar menu.

 - Use filters and dropdown menus to customize the data displayed.

 - Adjust production metrics to observe changes in predictive analytics.

 - Interact with the charts and visuals for detailed insights.

 - Export data or reports as needed for offline use.

## Technical Details

Languages Used: Python

Frameworks/Libraries: Pandas, NumPy, Joblib, OS, Plotly (Express and Graph Objects), Statsmodels (for SARIMA), Streamlit

Models Used: Pre-trained Linear Regression model and SARIMA model

### Setup:

 - Clone the repository: git clone <repo-url>

 - Install dependencies: pip install -r requirements.txt

 - Run the dashboard: streamlit_app.py

 - Hosting: The dashboard is hosted on Streamlit.

## Contact and Support

For any issues or questions, please reach out to federicoariton@outlook.es or open an issue in the repository.

