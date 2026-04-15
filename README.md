# Air-Quality-Index-Prediction-using-Machine-Learning
This project demonstrates how to build a complete machine learning pipeline to analyze and forecast Air Quality Index (AQI) using Python and the Facebook Prophet time-series forecasting model. The workflow follows a structured approach, starting from raw data collection to generating meaningful future predictions and visual insights.

Project Overview:

Air pollution is a critical environmental issue, and predicting air quality trends can help in proactive decision-making. This project leverages historical air quality data and applies time-series forecasting techniques to predict future trends of environmental factors such as humidity and pollutant levels.

Dataset:

The project uses the UCI Air Quality Dataset, which contains hourly sensor readings from an Italian city. The dataset includes:

Pollutants: Carbon Monoxide (CO), Nitrogen Oxides (NOx), Hydrocarbons, etc.
Environmental factors: Temperature, Relative Humidity, and more
Workflow:
1. Data Collection
Imported the dataset in a semicolon-separated format
Loaded and inspected raw sensor data
2. Data Pre-processing
Handled missing values (encoded as -200) by replacing them with column means
Removed null or irrelevant columns
Converted date and time into a unified datetime format
Structured the dataset to meet Prophet requirements (ds and y columns)
3. Time-Series Forecasting
Applied the Facebook Prophet model for forecasting
Trained the model on historical data
Generated future predictions for selected air quality metrics
4. Visualization & Insights
Visualized forecasted results and trends
Analyzed:
📅 Monthly trends (long-term patterns)
📆 Weekly variations
⏰ Hourly cycles
📈 Results

The model successfully captures seasonal patterns and trends in air quality data, providing interpretable forecasts that can be used for environmental monitoring and planning.

Technologies Used:
Python
Pandas
NumPy
Matplotlib / Seaborn
Prophet (Facebook Prophet)
Conclusion:
This project showcases the power of time-series analysis in predicting environmental conditions. The pipeline is flexible and can be adapted to forecast different air quality indicators or similar temporal datasets.
