# Robot-Model
This repository contains ROS (Robot Operating System), Gazebo, and Unity integration for the Waveshare JetBot ROS AI Kit. The kit includes a URDF model for the robot with  a CSI camera and RealSense depth camera.

**Prerequisites**

Before using this code, make sure you have the following installed:

1. ROS (Robot Operating System) - [Installation Guide](https://wiki.ros.org/Installation).

**Setup**

1. Clone this repository to your ROS workspace:

   ```bash
   git clone https://github.com/ICONgroupCWC/jetbot_world.git
   
2. Build the ROS workspace:
   ```bash
   cd your_ros_workspace
   catkin_make
   source devel/setup.bash

**Usage**
1. ROS

   Launch the Robot model node:
      ```bash
      roslaunch jetbot_world multi_jetbot.launch
      ```
   After running the launch file, you can import the robot model through the RViz view.As shown in the figure 1 below.



2. Unity

   To integrate with Unity, use the Unity Technology URDF Importer plugin. Refer to the documentation for installation and usage instructions.[Installation Guide](https://github.com/Unity-Technologies/URDF-Importer).

   ![Screenshot (14)](https://github.com/MadushankaHP/Robot-Model/assets/68281297/ecc70025-fbbe-479b-adcb-51c5a474aa68)
