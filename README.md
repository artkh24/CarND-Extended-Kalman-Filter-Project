# **Extended Kalman Filter** 

---

**Extended Kalman filter Project**

The goals / steps of this project are the following:
* Implement extended Kalman filter to predict the position of an object from LIDAR and RADAR noisy measurements
* Test on simulator that the filter successfully predicts object trajectory
* Summarize the results with a written report


[//]: # (Image References)

[image1]: ./images/Dataset1.jpg "Dataset 1"
[image2]: ./images/Dataset2.jpg "Dataset 2"


---
### Files Submitted 

The following files were changed during the implementation:
* tools.cpp contains RMSE and Jacobian matrix calculation
* kalman_filter.cpp contains functionality of predicting and updating tracking values
* FusionEKF.cpp containing a filter working pipeline
* Extended_Kalman_Filter.md summarizing the results


#### 1. Project Basics

In this project the C++ was used to program. The RADAR and LIDAR noisy measurements were taken to track the position of an object. The code were tested using Udacities simulator.



#### 3. Accuracy

According to the project rubric  the px, py, vx, and vy RMSE should be less than or equal to the values [.11, .11, 0.52, 0.52].

*Dataset 1 RMSE [0.0973,0.0855,0.4513,0.4399]
*Dataset 2 RMSE  [0.0726,0.0965,0.4216,0.4932]

![alt text][image1]
![alt text][image2]
