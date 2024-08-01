# IBM Intern Project - Analysis of Pune Air Pollution

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

![000](https://github.com/user-attachments/assets/7244b02f-e10b-4dab-8a24-66e7e84284e0)

## Project Overview

This project involves the analysis of historical air pollution data for Pune, Maharashtra, India, spanning the past four years. The aim is to visualize various pollutants, calculate the Air Quality Index (AQI) and AQI buckets, predict future AQI, and forecast AQI trends. The analysis was conducted as part of an internship project at IBM SkillBuild's AI & Cloud virtual internship, utilizing IBM Cloud's IBM Watson Studio.

![9](https://github.com/user-attachments/assets/aa7b89de-9723-442a-9e2f-d7679d6e5f02)
![10](https://github.com/user-attachments/assets/33fe134a-cf2e-4a33-bf27-d321c0c9f051)

## Data Source

The air pollution data was fetched from the [OpenWeatherMap API](http://api.openweathermap.org) which provides historical pollution data. The data includes hourly measurements of various pollutants such as PM2.5, PM10, NO2, SO2, CO, NO, O3, and NH3.

![11](https://github.com/user-attachments/assets/5c6c2763-9fa3-4063-93ef-ecd2f5ea9b1e)

## Project Objectives

1. **Data Collection**: Fetch historical air pollution data for Pune using the OpenWeatherMap API.
2. **Data Processing**: Clean and process the data for analysis.
3. **Data Visualization**: Visualize the levels of various pollutants over time.
4. **AQI Calculation**: Calculate the Air Quality Index (AQI) and classify it into AQI buckets.
5. **AQI Prediction**: Predict AQI values based on historical data.
6. **AQI Forecasting**: Forecast future AQI trends using the available data and computational resources.

![16](https://github.com/user-attachments/assets/b2d60dfe-fd33-4ab5-91f1-eedacdd2d89a)

## Technologies Used

- **Python**: For data fetching, processing, and analysis.
- **IBM Watson Studio**: For project creation and data processing.
- **Pandas**: For data manipulation and analysis.
- **Requests**: For API data fetching.
- **Matplotlib/Seaborn**: For data visualization.
- **Machine Learning Algorithms**: For AQI prediction and forecasting.

![17](https://github.com/user-attachments/assets/bcef930c-0f80-4e9b-bb21-a6e6b1d807cd)

## Data Collection and Processing

The data fetching process involves making API requests to the OpenWeatherMap API to retrieve historical pollution data for Pune. The data is processed to extract relevant pollutant information and stored in a pandas DataFrame.

![18](https://github.com/user-attachments/assets/682d853d-1c77-4b3a-9dea-91dfbdb230ac)

### Key Steps:

1. **Fetch Data**: Make API requests to the OpenWeatherMap API using Pune's coordinates (latitude: 18.5204, longitude: 73.8567) and specified date ranges.
2. **Process Data**: Extract hourly pollutant measurements from the API response, including PM2.5, PM10, NO2, SO2, CO, NO, O3, and NH3.
3. **Store Data**: Save the processed data in a CSV file for further analysis.

![13](https://github.com/user-attachments/assets/0ba0c981-ae64-4297-aa9a-78add88bbf77)

## Data Analysis and Visualization

The processed data is analyzed to understand the levels of various pollutants over time. Visualizations such as line plots and bar charts are created to represent the data visually. This helps in identifying trends and patterns in the pollution data.

![12](https://github.com/user-attachments/assets/ed527601-f785-44fd-a647-3013c064517a)

## AQI Calculation

The Air Quality Index (AQI) is calculated based on the pollutant concentrations. The AQI is classified into different buckets to understand the severity of air pollution. The AQI calculation formula and classification criteria are based on standard guidelines.

![00](https://github.com/user-attachments/assets/013c0e81-c870-40b4-8f82-827f1f3a6c21)

## AQI Prediction and Forecasting

Machine learning algorithms are used to predict AQI values based on historical data. Limited data and computational resources posed a challenge, but various models were tested to achieve the best possible accuracy. Forecasting AQI trends helps in predicting future air quality and planning necessary actions.

## Challenges and Solutions

- **Data Availability**: Historical pollution data was only available from November 27, 2020, onwards.
- **Computational Resources**: Limited resources in IBM Watson Studio required optimization of code and models.
- **Data Quality**: Ensuring the accuracy and completeness of fetched data was critical for reliable analysis.

![19](https://github.com/user-attachments/assets/a88f31fa-9487-4ff8-8efa-256aa8635330)

## Conclusion

The project successfully analyzed and visualized historical air pollution data for Pune. The AQI calculation, prediction, and forecasting provided valuable insights into air quality trends. This analysis can aid in understanding pollution levels and planning mitigation measures for improving air quality in Pune.

## Future Work

- **Enhanced Prediction Models**: Utilize more advanced machine learning models for better AQI prediction accuracy.
- **Extended Data Sources**: Incorporate data from additional sources for a more comprehensive analysis.
- **Real-time Monitoring**: Implement real-time air quality monitoring and alerts.

![0](https://github.com/user-attachments/assets/5ec848bd-02ab-4ce7-bbb8-7fcdfe9aad8e)

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Acknowledgments

- IBM SkillBuild AI & Cloud Internship
- OpenWeatherMap for providing the historical pollution data

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>
