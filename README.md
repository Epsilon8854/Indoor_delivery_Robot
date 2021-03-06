# Indoor_delivery_Robot

## Requirement
- ubuntu 16.04

## Overview

The purpose of this project is to deliver safely to the target point. To decide path, It create a map in advance by using [gmapping](http://wiki.ros.org/gmapping). Also recognize Robot's Location by using **AMCL**.
And use [DWA_path_planner](http://wiki.ros.org/dwa_local_planner) for navigation.
Once robot arrived target point, you can receipt Obj by showing personal QR to the robot.

## Experimental robot & Modeling
![](image/mbRobot.png)

## Demo video (click the image!)
[![deliveryRobot](https://img.youtube.com/vi/MRtj2YxjFOw/0.jpg)](https://youtu.be/MRtj2YxjFOw)


## Mapping
It can get map by using Gmapping. Because of robot's suspension, it use very slow accelation.
- video(click the image!)
  
[![deliveryRobot](https://img.youtube.com/vi/XwCZ3GI8F34/0.jpg)](https://youtu.be/XwCZ3GI8F34)

- result
  
![](image/MappingResult.png)


## Localization & DWA Planner(click the image!)
[![deliveryRobot](https://img.youtube.com/vi/cLcv_yD-Egs/0.jpg)](https://youtu.be/cLcv_yD-Egs)