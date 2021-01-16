# Sensor Fusion of IMU, GPS & LIDAR with Error State Extended Kalman Filter for State Estimation  and Localization

## Overview 
Implementation of Error State-Extended Kalman Filter for state estimation & localization. Input data for IMU, GNSS (GPS), and LIDAR is given along with time stamp. All data is in vehicle frame, except for LIDAR data. A transformation is done on LIDAR data before using it for state estimation.

<p align="center">
<img src="https://github.com/varunasthana92/Sensor_Fusion_IMU_GPS_LIDAR_ES_EKF/blob/main/data/motion_model.png" width = 350>
<img src="https://github.com/varunasthana92/Sensor_Fusion_IMU_GPS_LIDAR_ES_EKF/blob/main/data/linearized_motion.png" width = 350>
</p>

<p align="center">
<img src="https://github.com/varunasthana92/Sensor_Fusion_IMU_GPS_LIDAR_ES_EKF/blob/main/data/gnss_model.png" width = 350>
</p>
<p align="center">
<img src="https://github.com/varunasthana92/Sensor_Fusion_IMU_GPS_LIDAR_ES_EKF/blob/main/data/lidar_model.png" width = 350>
</p>

### Ground Truth for result comparision
<p align="center">
<img src="https://github.com/varunasthana92/Sensor_Fusion_IMU_GPS_LIDAR_ES_EKF/blob/main/output/gtruth.png" width = 400>
</p>

### State Estimation and Localization
<p align="center">
<img src="https://github.com/varunasthana92/Sensor_Fusion_IMU_GPS_LIDAR_ES_EKF/blob/main/output/estimation.png" width = 350>
<img src="https://github.com/varunasthana92/Sensor_Fusion_IMU_GPS_LIDAR_ES_EKF/blob/main/output/error_plots.png" width = 350>
</p>



