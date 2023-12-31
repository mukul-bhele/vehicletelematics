# Advanced Vehicle Telematics Analysis

## Introduction

**Vehicle Telematics Analysis** is a comprehensive exploration of telematics data, offering valuable insights into gear detection, driving patterns, safety measures and fuel efficiency. This project utilizes data collected from various sensors, including accelerometers and magnetometers, to provide a deeper understanding of driver behavior and enhance vehicle performance.

![image](https://github.com/mukul-bhele/vehicletelematics/assets/145564456/d090e253-a1dd-48f4-8717-36273a036262)

## Data Acquisition and Sensors

The core of this project revolves around data acquisition and sensor analysis. Raw data is collected from sensors like accelerometers and magnetometers, which are commonly found in modern vehicles. The data acquisition process involves thorough cleaning, processing, and conversion of raw sensor readings into meaningful and actionable information. This ensures that the data is ready for in-depth analysis.

## About Data
The provided dataset is a sample of real-time data collected from around 30 different four-wheeled vehicles over a span of four months. Data collection occurs at varying frequencies: OBD data is recorded at a rate of 1Hz, equating to one record per second, while accelerometer data is sampled at a higher frequency of 25Hz, resulting in 25 data points per second.

This dataset contains essential metadata, including unique device IDs, timestamps, trip IDs, accelerometer readings, GPS-derived speed measurements, battery voltage, coolant temperature, diagnostic trouble codes, engine load, intake air temperature, manifold absolute pressure, calculated fuel efficiency, mass airflow, engine RPM, OBD-derived speed, timing advance, throttle position, and magnetometer data.

**Dataset** : https://www.kaggle.com/datasets/yunlevin/levin-vehicle-telematics

This dataset serves as an example of the real-time data that we gather. This dataset was gathered on about 30 4-wheelers over the course of four months. While accelerometer data is gathered at 25 Hz (25 data points per second), OBD data is recorded at 1Hz frequency (one record per second).

- **Sensor Types**: Utilizes accelerometers and magnetometers for data collection.
- **Data Preprocessing**: Describes data cleaning and preprocessing techniques.
- **Actionable Insights**: Highlights the conversion of raw sensor data into actionable insights.
  
Preprocessing of the data were done in Excel. This involved handling missing data, cleaning, and ensuring consistent formats. Also aggregated and filtered data, created new features, and conducted basic data quality checks using **Excel**.

## Analysis
The various kinds of analysis that has been done are:

**1). Fuel Efficiency   
2). Gear Detection   
3). Sharp Turn Detection   
4). Driving Pattern**   

## Fuel Efficiency

Optimizing fuel efficiency is a crucial goal for both drivers and vehicle manufacturers. Our analysis has uncovered a strong correlation between engine load, throttle position, and fuel efficiency. To make these relationships more tangible, we've created various visualizations, including scatter plots and heatmaps. These visualizations help us understand the optimal driving practices that contribute to improved fuel efficiency.

- **Fuel Optimization**: Highlights the significance of fuel efficiency for drivers and manufacturers.
- **Variable Analysis**: Discusses the impact of engine load and throttle position on fuel efficiency.
- **Visualizations**: Depicts relationships through scatter plots and heatmaps.

## Gear Detection

Gear transitions play a significant role in a vehicle's performance and efficiency. We've developed a robust system for detecting gear changes using data such as speed and RPM. To achieve this, we've harnessed the power of Kernel Density Estimation (KDE) and Jenks Natural Breaks. These techniques allow us to accurately identify gear change points, providing valuable insights into how drivers utilize different gears during their journeys.

- **Performance Impact**: Describes the impact of gear transitions on vehicle performance.
- **Methodology**: Explains the use of Kernel Density Estimation (KDE) and Jenks Natural Breaks for gear detection.
- **Change Points**: Identifies gear change points using speed and RPM data.

## Sharp Turns Detection

Sharp turns are a critical aspect of driving behavior. To detect these, we have implemented algorithms that leverage accelerometer and gyroscope data. These algorithms are designed to identify sharp turns based on both the rapid change in the vehicle's orientation and the angle of the turn. This allows us to gain insights into how drivers navigate turns and assess the safety of their driving habits.

- **Safety Significance**: Explains the importance of detecting sharp turns for driving safety.
- **Sensor Data**: Details the use of accelerometer and gyroscope data.
- **Orientation Changes**: Detects sharp turns through rapid vehicle orientation changes.
  
## Driving Patterns Analysis

One of the primary objectives of this project is to identify and analyze driving patterns. By examining variables such as vehicle speed, RPM (Revolutions Per Minute), throttle position, and engine load over time, we gain insights into various aspects of driving behavior. This includes distinguishing between city and highway driving, detecting instances of aggressive driving, and pinpointing scenarios that promote fuel-efficient driving.

- **Relevant Variables**: Examines speed, RPM, throttle position, and engine load.
- **City vs. Highway Driving**: Distinguishes between driving patterns using speed data.
- **Visualizations**: Utilizes scatter plots to identify driving clusters.

## Dashboard
 - Developed an interactive **Tableau** dashboard to effectively visualize driving patterns for both city and highway scenarios, highlighting sharp turns, hard braking events, acceleration variations, and average speeds. Additionally, incorporated fuel efficiency metrics, allowing users to gain valuable insights by applying various filters and parameters.
 - Dashboard Link : https://drive.google.com/drive/folders/1GBTuSX0VZudNwjtdr69oVe6JCcmbGsZC?usp=drive_link
   
## Conclusion

In conclusion, **Vehicle Telematics Analysis** demonstrates the capabilities of data analysis in understanding vehicle telematics. By delving into sensor data, we've gained deep insights into driving behavior, safety, and fuel efficiency. These insights open doors for vehicle optimization, enhanced safety measures, and improved driver experiences.


Feel free to explore the code and visualizations provided in this repository. If you have any questions or suggestions, please don't hesitate to reach out.




