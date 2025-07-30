# Arduinobot ROS 2 Workspace

This is the development workspace for a custom ROS 2 robot arm, designed for integration with large language models (LLMs) to enable natural language-based manipulation tasks.

## 🚧 Project Status: Under Development

This project is currently a work in progress. The main focus at this stage is building and testing the robot's simulation and control infrastructure in ROS 2, with eventual integration into a perception and language interface system.

## 📦 Features

- Custom URDF robot model
- Gazebo launch support for robot simulation
- ROS 2 package structure
- Initial groundwork for natural language interaction pipeline using Arduino and LLMs (e.g., Gemini)

## 🧪 How to Use

You can currently launch the robot in Gazebo using the provided launch files:

```bash
ros2 launch arduinobot_description gazebo.launch.py
```
However, the method of loading the files will defer based on the user and their version of linux and Ubuntu. Therefore a full process is not available yet and will be worked on in the near future.
