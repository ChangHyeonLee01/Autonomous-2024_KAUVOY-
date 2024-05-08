# Autonomous-2024_KAUVOY-
Repository for recording what I do for Autonomous Driving Club in 2024 as Team leader.

## Overview


### DEC 2023

### JAN 2024

### FEB 2024

### MAR 2024

MAR 04(MON) : Make document about "how to use ROS system in UBUNTU(LINUX)" for teammates.

MAR 05(TUE) : Meeting with LiDAR Processing Team. Discuss the tools for processing and decide it. -> Downsampling(VOXEL Downgrid), ROI(delete the backwards), Noise Filtering(RANSAC), Clustering(DBSCAN)

MAR 07(THU) : Meeting with GPS/IMU Processing Team. Discuss the tools for processing and decide it. -> Convert Cordinates(WGS84 to UTMK), Timestamp Matching, Filtering(Extended Kalman Filter & Unscented Kalman Filter), SLAM(LIO-SAM)

MAR 10(SUN) : Check the cause of the IMU launch file execution. (File Path Error) Fix the path.

MAR 11(MON) : Synchronize the time of IMU to time from GPS. Change format of GPS data from WGS84 to UTMK

MAR 16(SAT) : Another Path eroor occurs. Fix the File Path Error.

MAR 19(TUE) : Report from teammates. Error about python.(Python3 not downloaded). Major error occurs.

MAR 20(WED) : Delete all the system(FORMAT). Re-Install UBUNTU 20.04 and ROS Noetic.

MAR 21(THU) : Re-Install packages about LiDAR, IMU, GPS. 

MAR 22(FRI) : Check the RTK-GPS accurcy from outside the University. (about 2km out). Mean Covariance = 0.2 (connected to computer, wifi, Anthena was on the window). Offset was about 1m. (Compared by Google Map)

MAR 23(SAT) : Check the RTK-GPS accurcy inside the University. Some Problems occur. 1) RTK NOT FIXED. 2) Radio Interference from Military nearby. (connected to laptop, wifi, outdoor).

MAR 24(SUN) : Packaging Lane Detecting Alghritom(Powered by Pytorch Lightning)

MAR 26(TUE) : Check the output format of Lane Detect Algorhitm. Write the algorhitm to Print the data on the terminal and visualization on the image output.

MAR 27(WED) : Apply DBSCAN Clustering on PCD Data. Make the algorhitm that making the Bounding Box Marker Array and Visualizaion on RVIZ tool.

MAR 30(SAT) : Adjust Parameters of PCD Processing on the outdoor. Feedback LandDetecting Algorhitm and YOLOV9 Algorhitm. Notice the Problem of power distribution. We use DC TO AC Inverter(DC12V -> AC220V.) But when we use too much deep learning algorhitm, the input vlotage drop(12v -> 11.4v) occurs and inverter can't operate.

### APR 2024

APR 02(THU) : Meeting with Professor. Get advice about GPS Problem. -> For prevent Radio Interference, check the rtcm messages for higer level model

APR 04(SAT) : For Solve the power distrubution problem, add Power Bank for some machines(Monitor, LiDAR). -> Problem Not occurs anymore but Power Bank is not enough for 3hour operating.

APR 27(SAT) : 
