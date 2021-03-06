# Extended kalman Filter for Sensor Fusion - Autonomous Driving
The objective of this project is to detect a bicyle travelling around a car. The car is fitted with Lidar and radar sensors. Noisy lidar and radar data measurements are avilable. An extended Kalman Filter has been implemented for this purpose.

[//]: # (Image References)

[video1]: ./ekf_sim.mov "VideoEKF"
[image1]: ./ekf_1.png "ekf car1"

* An extended Kalman filter using the constant velocity model (CV) is implemented.

* Lidar measurements are red circles, radar measurements are blue circles with an arrow pointing in the direction of the observed angle, and estimation markers are green triangles. The image and the video below shows what the simulator looks like when a c++ script is using its Kalman filter to track the object. A simulator provides the script the measured data (lidar and/or radar), and the script feeds back the measured estimation marker, and RMSE values from its Kalman filter.

![alt text][image1]

* [Here's a video of the performance of EKF algorithm in the simulator][video1]


#### Note: This Project is part of the Udacity Self Driving Car nanodegree program. Instructions related to environment 
setup and the simulator can be found [here](https://github.com/udacity/CarND-Extended-Kalman-Filter-Project)
