# **Optimal Location for Wind Farm in Kenya**
## **Introduction**
This project aims to address Kenya's persistent blackout issues caused by grid overload through the strategic implementation of wind farms. By leveraging data science techniques, we seek to identify optimal locations for wind farms, contributing to a sustainable and reliable energy solution.

<img src="./wind-turbin.gif">

## **Business Understanding**
Kenya's electricity grid faces frequent overloads, resulting in widespread blackouts that adversely impact businesses and households. The project's goal is to alleviate this issue by identifying the most suitable locations for wind farms. This approach involves analyzing historical wind data to maximize energy output and supplement the existing grid with renewable sources.

## **Objectives**
### Primary Objective:
- To model wind patterns in Kenya and pinpoint optimal locations for potential wind farms based on comprehensive wind strength and direction analysis

### Secondary Objectives:
- To quantify the annual energy output potential of a wind turbine of size X in targeted Kenyan regions by modeling regional wind data, enabling precise evaluation for effective wind energy project planning

- To forecast next-year output of a size X wind turbine across various Kenyan regions through analysis of historical wind patterns, aiding proactive project planning


## **Data Understanding**
## Data Gathering and Understanding:
Data for this project is collected sourced from Copernicus Climate Change Service (C3S) [website](https://cds.climate.copernicus.eu/about-c3s). The collected historical wind data includes parameters such as wind speed, direction, and strength at various locations in Kenya. The aim is to utilize data science techniques to analyze and forecast wind patterns, identifying optimal locations for wind farms.

- Key Parameters to be Analyzed:
    - Wind Speed (wind_speed): Measurement of wind speed in units like meters per second (m/s), kilometers per hour (km/h), or knots.
    - Wind Direction (wind_direction): Direction from which the wind is blowing, measured in degrees.
    - 10m Wind Gust (10m_wind_gust): Maximum instantaneous wind speed observed at 10 meters above the ground.
    - 10m U Component of Wind (10m_u_component_of_wind): Eastward component of wind speed at 10 meters above the ground.
    - 10m V Component of Wind (10m_v_component_of_wind): Northward component of wind speed at 10 meters above the ground.
    - 100m Wind Speed (100m_wind_speed): Similar to 10m wind speed but measured at 100 meters above the ground.
    - 100m Wind Direction (100m_wind_direction): Wind direction at 100 meters above the ground.
    - 100m U Component of Wind (100m_u_component_of_wind): Eastward component of wind speed at 100 meters above the ground.
    - 100m V Component of Wind (100m_v_component_of_wind): Northward component of wind speed at 100 meters above the ground.
  

## **Modeling**



## **Deployment** 



## **Installation**
```bash
pip install -r requirements
