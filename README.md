## Project Title: Time Series Analysis on Chicago Taxi Trip

### Technology used:
<div align ='left'>
<img src ='https://technology.amis.nl/wp-content/uploads/2020/11/image_thumb-27.png', height = "50" alt = 'Jupyter'/><img width='12'/> 
<img src = 'https://cdn.dribbble.com/users/6569/screenshots/16471177/media/8bbfe7fd594073dc6271d5d852c7381a.png', height = "50" alt = 'Vs code'/><img width = '12'/>
<img src = 'https://thomasjpfan.github.io/data-umbrella-2020-streamlit-slides/images/streamlit.png', height = "50" alt = 'Streamlit'/><img width = '12'/>
<img src = 'https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png', height = "50 alt = 'Github'/><img width = '12'/>
<img src = 'https://img.uxwing.com/wp-content/themes/uxwing/download/brands-social-media/chatgpt-icon.png', height = "50" alt = 'ChatGPT'/><img width = '12'/>
</div>

## Overview
This project is a comprehensive time series analysis of Chicago taxi trip data. aim to understand and forecast the patterns in taxi trip demand 
using various time series analysis techniques. I have used ARIMA, Prophet, and Plotly for visualization, along with statistical tests such as 
ADFuller and KPSS for stationarity analysis.

## Data
I have utilized a dataset containing historical Chicago taxi trip data. The dataset includes information such as trip date and total trips. This data will be the basis for my time series analysis.

## ARIMA Modeling
I have employed the Autoregressive Integrated Moving Average (ARIMA) model to capture the temporal patterns in the taxi trip data. The ARIMA model
involves differencing the data to achieve stationarity, determining the order of autoregressive (p), differencing (d), and moving average (q) 
terms, and then fitting the model. The ARIMA model helps me make short-term forecasts and identify trends and seasonality.

## Prophet Modeling
In addition to ARIMA, I have utilized the Prophet forecasting model developed by Facebook. Prophet is designed to handle time series data with 
strong seasonal and holiday patterns. It automatically detects changepoints in the data and incorporates them into the forecast. This model 
provides me with flexibility and robustness in capturing time series patterns.

## Visualization with Plotly
I have leveraged Plotly, a powerful Python library, for data visualization. With Plotly, I have created interactive and informative plots to 
visualize the taxi trip data, model predictions, and forecasted trends. These visualizations enhance my understanding of the dataset and model 
performance.

## Stationarity Analysis
To ensure the suitability of time series models like ARIMA and Prophet, I have conducted stationarity analysis using the Augmented Dickey-Fuller
(ADF) test and Kwiatkowski-Phillips-Schmidt-Shin (KPSS) test. Stationarity is a crucial assumption in time series analysis, and these tests help
me determine whether differencing is necessary to achieve stationarity.

## Deployment with Streamlit
I have deployed the time series analysis using Streamlit, a Python library for creating web applications with minimal effort. The Streamlit app 
allows users to interact with the analysis, explore the visualizations, and make predictions based on the models I've developed. You can access 
the deployed application by following this link: [Streamlit](https://project5chicagotaxitripstimeseries-wwn89ktpevfmjexzrssvfq.streamlit.app/)

## Conclusion
This project provides a comprehensive time series analysis of Chicago taxi trip data. I have applied ARIMA and Prophet models for forecasting, 
used Plotly for visualization, and deployed the analysis with Streamlit for an interactive web-based experience. Additionally, I have performed 
stationarity analysis to validate my modeling approach. The insights gained from this analysis can be valuable for taxi service providers, 
policymakers, and anyone interested in understanding and predicting taxi trip demand in Chicago.

Feel free to explore the code, findings, and the Streamlit app in this repository to gain a deeper understanding of the analysis and the methods I used. If you have any questions or feedback, please don't hesitate to reach out.

Thank you for visiting this project!

**Author:** Mohammed Anas Khan
**Contact:** 132anaskhan@gmail.com

