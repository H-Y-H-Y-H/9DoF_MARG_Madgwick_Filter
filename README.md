# MPU9250 Madgwick Filter

This project inplements attitude estimation by using Madgwick filter, which is a low computational cost and high accuracy data fusion algorithm, based on a 9 degree of freedom MARG(magnetic angular rate and gravity, i.e., IMU + magnetometer). The MARG used in this project is [MPU9255](https://www.amazon.com/UCTRONICS-MPU-9255-Compass-Accelerometer-Gyroscope/dp/B01DIGRR8U/ref=sr_1_3?dchild=1&keywords=MPU9255&qid=1597109290&sr=8-3), [MPU9250](https://www.amazon.com/HiLetgo-Gyroscope-Acceleration-Accelerator-Magnetometer/dp/B01I1J0Z7Y/ref=sr_1_4?dchild=1&keywords=MPU9250&qid=1597109421&sr=8-4) is also supported since they use same library in Arduino.

