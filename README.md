# ABB_MultiBot_Feedback_Project

This repository will be a workground for a number of things to support a multi-robot ABB IRB120 experiment. A TBD force/torque sensor and visual segmentation work will be completed for feedback on the robots motion planner. 

This repository will also act as a staging ground for my updated ABB_Drivers package which will enable 2 or more robots to interact in ROS with a single IRC5 controller. Setup instructions for how to setup multiple robots and changes to the ROS-I abb_driver will be included. 

## Instructions for modification of abb_driver for multiple robots through ethernet connection to an IRC5 with additional drive modules. 
TBA


## Demo MultiBot Motion
This includes a python ROS node meant as a quick test of your multirobot abb_driver was currently installed on the IRC5 controller and the launch file is communicating with the controller. This will make the two robots complete a simple trajectory as outlined in the traj.txt file. It will execute 1 point at a time at a fixed rate. 

## multi_robot_single_controller.launch
This launch file will launch the two robots on the workstation computer. Each robot will be in its own namespace and have its own separate topics for publishing and substribing telemetry. 
