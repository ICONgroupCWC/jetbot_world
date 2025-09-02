# Waveshare JetBot ROS AI Kit – URDF Model
This repository provides a **URDF/XACRO robot description** of the [**Waveshare JetBot ROS AI Kit**](https://www.waveshare.com/jetbot-ros-ai-kit.htm), with integration for **ROS**, **Gazebo**, and **Unity**. It includes the robot model with a **CSI camera**, **Intel RealSense depth camera**, and support for onboard sensors such as the **IMU**, **Camera** and **2D LiDAR**.

## 🛠️ Prerequisites

Before using this code, make sure you have the following installed:

1. ROS (Robot Operating System) - [Installation Guide](https://wiki.ros.org/Installation).

## 🚀 Setup

1. Clone this repository to your ROS workspace:

   ```bash
   git clone https://github.com/ICONgroupCWC/jetbot_world.git
   ```
   
2. Build the ROS workspace:
   ```bash
   cd your_ros_workspace
   catkin_make
   source devel/setup.bash
   ```

## ▶️ Usage
### ROS Simulation

   Launch the JetBot simulation with multiple robots:
   
   ```bash
   roslaunch jetbot_world multi_jetbot.launch
   ```
      
   After running the launch file, you will see a Gazebo simulation environment with two Jetbot robots, along with the RViz visualization displaying the robot models and their sensor data.

   Figures below illustrate:
   - The Gazebo world with two Jetbots. 
   - The RViz view showing the robot models.
     
   ***Gazebo view:***
   
   ![gazebo](https://github.com/user-attachments/assets/30cc5d41-f64d-4db5-ae41-4a7bfa6f7b86)
   
   ***RViz view:***
   
   ![Screenshot from 2025-04-23 13-22-56](https://github.com/user-attachments/assets/fba80a6e-9508-4f77-b011-1b18551b787e)




### Unity Integration

   To integrate with Unity, use the Unity Technology URDF Importer plugin. Refer to the documentation for installation and usage instructions.[Installation Guide](https://github.com/Unity-Technologies/URDF-Importer).
   
***Unity view:***
   ![Screenshot (14)](https://github.com/MadushankaHP/Robot-Model/assets/68281297/ecc70025-fbbe-479b-adcb-51c5a474aa68)
   
## 🎥 Demo
[![Demo: Jetbot Robot model](https://img.youtube.com/vi/pvjqGRFbfh8/sddefault.jpg)](https://youtu.be/pvjqGRFbfh8)

## 🤝 Contributing

Contributions are welcome!
- Open an issue for bugs or feature requests.
- Submit a pull request for improvements.

## 📖 Citation

If you use this repository in your research or projects, please cite:

```bibtex
@misc{jetbot_ros_ai_kit,
  author       = {ICONGroup},
  title        = {Waveshare JetBot ROS AI Kit URDF Model},
  year         = {2025},
  publisher    = {GitHub},
  journal      = {GitHub repository},
  howpublished = {\url{https://github.com/ICONgroupCWC/jetbot_world}}
}
```
## 📜 License
This project is licensed under the MIT License.
