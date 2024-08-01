# IBM Intern Project - Analysis of Pune Air Pollution

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

![00](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/d6792d21-5557-40cd-a3ea-7a09e3998cd5)

## Project Overview

This project involves the analysis of historical air pollution data for Pune, Maharashtra, India, spanning the past four years. The aim is to visualize various pollutants, calculate the Air Quality Index (AQI) and AQI buckets, predict future AQI, and forecast AQI trends. The analysis was conducted as part of an internship project at IBM SkillBuild's AI & Cloud virtual internship, utilizing IBM Cloud's IBM Watson Studio.

![8](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/d7cd554d-0c16-4c26-91c1-03d79db99219)
![9](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/5d47f6af-2d25-4ecc-a641-edeca1964e5f)

## Data Source

The air pollution data was fetched from the [OpenWeatherMap API](http://api.openweathermap.org) which provides historical pollution data. The data includes hourly measurements of various pollutants such as PM2.5, PM10, NO2, SO2, CO, NO, O3, and NH3.

![10](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/62cc4d72-a162-4b9a-9adb-410cb3904d34)

## Project Objectives

1. **Data Collection**: Fetch historical air pollution data for Pune using the OpenWeatherMap API.
2. **Data Processing**: Clean and process the data for analysis.
3. **Data Visualization**: Visualize the levels of various pollutants over time.
4. **AQI Calculation**: Calculate the Air Quality Index (AQI) and classify it into AQI buckets.
5. **AQI Prediction**: Predict AQI values based on historical data.
6. **AQI Forecasting**: Forecast future AQI trends using the available data and computational resources.

![15](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/64cf6798-880c-4ccd-b4ea-913ff378d41f)

## Technologies Used

- **Python**: For data fetching, processing, and analysis.
- **IBM Watson Studio**: For project creation and data processing.
- **Pandas**: For data manipulation and analysis.
- **Requests**: For API data fetching.
- **Matplotlib/Seaborn**: For data visualization.
- **Machine Learning Algorithms**: For AQI prediction and forecasting.

![16](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/d7faebb0-5495-4b47-934b-e2a5d68d005e)


## Data Collection and Processing

The data fetching process involves making API requests to the OpenWeatherMap API to retrieve historical pollution data for Pune. The data is processed to extract relevant pollutant information and stored in a pandas DataFrame.

![17](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/f95d8383-569a-4c4f-963f-3913628ee917)

### Key Steps:

1. **Fetch Data**: Make API requests to the OpenWeatherMap API using Pune's coordinates (latitude: 18.5204, longitude: 73.8567) and specified date ranges.
2. **Process Data**: Extract hourly pollutant measurements from the API response, including PM2.5, PM10, NO2, SO2, CO, NO, O3, and NH3.
3. **Store Data**: Save the processed data in a CSV file for further analysis.

![14](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/ee9ac446-a732-4407-9106-fe0fac23c0b1)


## Data Analysis and Visualization

The processed data is analyzed to understand the levels of various pollutants over time. Visualizations such as line plots and bar charts are created to represent the data visually. This helps in identifying trends and patterns in the pollution data.

![12](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/c72e9548-837f-4667-8756-57388484caf1)


## AQI Calculation

The Air Quality Index (AQI) is calculated based on the pollutant concentrations. The AQI is classified into different buckets to understand the severity of air pollution. The AQI calculation formula and classification criteria are based on standard guidelines.

![0](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/1811eb63-d35b-4753-a12b-a0713d03b8a6)

## AQI Prediction and Forecasting

Machine learning algorithms are used to predict AQI values based on historical data. Limited data and computational resources posed a challenge, but various models were tested to achieve the best possible accuracy. Forecasting AQI trends helps in predicting future air quality and planning necessary actions.

## Challenges and Solutions

- **Data Availability**: Historical pollution data was only available from November 27, 2020, onwards.
- **Computational Resources**: Limited resources in IBM Watson Studio required optimization of code and models.
- **Data Quality**: Ensuring the accuracy and completeness of fetched data was critical for reliable analysis.

![11](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/8fb69149-4187-41d8-816a-a6adf52eb528)

## Conclusion

The project successfully analyzed and visualized historical air pollution data for Pune. The AQI calculation, prediction, and forecasting provided valuable insights into air quality trends. This analysis can aid in understanding pollution levels and planning mitigation measures for improving air quality in Pune.

## Future Work

- **Enhanced Prediction Models**: Utilize more advanced machine learning models for better AQI prediction accuracy.
- **Extended Data Sources**: Incorporate data from additional sources for a more comprehensive analysis.
- **Real-time Monitoring**: Implement real-time air quality monitoring and alerts.

![000](https://github.com/themihirmathur/IBM-Intern-Project/assets/92594107/2dc3c022-fdf2-4da9-b117-5a6b405e5c7a)

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Acknowledgments

- IBM SkillBuild AI & Cloud Internship
- OpenWeatherMap for providing the historical pollution data

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>
