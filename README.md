# tracking_with_rplidar

This package is created in ros-noetic

Note - URDF is not created from any tool

## Required packages -
Keep following packages and this package(trackingwithrp) in same ros-workspace
1. To use tracking camera T265: [realsense-ros](https://github.com/IntelRealSense/realsense-ros)
2. To use RPLidar A1: [rplidar_ros](https://github.com/Slamtec/rplidar_ros)
3. To modify laser angle scan: [laser_filters (noetic-devel)](https://github.com/ros-perception/laser_filters/tree/noetic-devel)

## Run following command -
```
roslaunch trackingwithrp display.launch
```
