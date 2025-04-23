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
   After running the launch file, you will see a Gazebo simulation environment with two Jetbot robots, along with the RViz visualization displaying the robot models and their sensor data.

   Figures below illustrate:

   The Gazebo world with two Jetbots.
   
   The RViz view showing the robot models.
   ![gazebo](https://github.com/user-attachments/assets/30cc5d41-f64d-4db5-ae41-4a7bfa6f7b86)
   ![Screenshot from 2025-04-23 13-22-56](https://github.com/user-attachments/assets/fba80a6e-9508-4f77-b011-1b18551b787e)


   




3. Unity

   To integrate with Unity, use the Unity Technology URDF Importer plugin. Refer to the documentation for installation and usage instructions.[Installation Guide](https://github.com/Unity-Technologies/URDF-Importer).

   ![Screenshot (14)](https://github.com/MadushankaHP/Robot-Model/assets/68281297/ecc70025-fbbe-479b-adcb-51c5a474aa68)
