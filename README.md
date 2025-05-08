# Warehouse-Automation-with-ROS-2
This project demonstrates how to combine perception and grasping techniques to automate warehouse tasks using ROS 2. It focuses on enabling a robot to autonomously detect, pick, and place objects within a warehouse environment.
# Warehouse Automation with ROS 2

This project demonstrates how to combine perception and grasping techniques to automate warehouse tasks using ROS 2. It focuses on enabling a robot to autonomously detect, pick, and place objects within a warehouse environment.

##  Overview

Warehouse automation is essential for enhancing operational efficiency, reducing labor costs, and ensuring accuracy in inventory management. This project integrates perception and grasping to create advanced robotic solutions capable of autonomously handling objects.

##  Robot Used

- **BotBox**: A mobile robot equipped with sensors and a manipulator arm, suitable for warehouse automation tasks.

##  What You'll Learn

- Integrating perception and grasping techniques.
- Developing ROS 2 nodes for object detection and manipulation.
- Implementing autonomous pick-and-place operations.

##  Technologies Used

- ROS 2
- Python
- OpenCV
- MoveIt 2

##  Project Structure
warehouse_automation_ros2/
├── perception/
│ └── object_detection_node.py
├── manipulation/
│ └── pick_and_place_node.py
├── launch/
│ └── warehouse_automation.launch.py
├── config/
│ └── parameters.yaml
├── urdf/
│ └── botbox.urdf.xacro
├── worlds/
│ └── warehouse.world
├── README.md
└── package.xml
