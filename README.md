BNO-055
=======

Teensiduino sketch for 9-axis BNO-055 motion sensor + MS5637 pressure sensor

Basic sketch to configure the sensors and get scaled accelerometer, gyroscope, and magnetometer data from the BNO-055 9-axis motion sensor and MS5637 pressure sensor. 

For some reason the BNO-055 chip has software ID code 02.B0 when it should be running 03.04. Maybe these initial chips from Mouser are using a slightly outdated firmware or are engineering evaluation chips.

Added accel and gyro calibration, comparison of software and hardware sensor fusion results.

Magnetometer calibration next.

Work in progress...
