# Papers_robotics


# Ground segmentation

1. Ground Segmentation ROS 2 Node (GSeg3D) [link](https://github.com/dfki-ric/ground_segmentation_ros2?tab=readme-ov-file)): This package implements a ROS 2 node that wraps the GSeg3D ground segmentation algorithm and exposes it as a real-time perception component for robotic systems. The node subscribes to LiDAR point clouds (optionally synchronized with IMU data), performs two-phase grid-based ground segmentation, and publishes ground and obstacle point clouds for downstream navigation and perception modules. INCLUDE A NAV2 IMPLEMENTATION.
<img width="450" height="180" alt="image" src="https://github.com/user-attachments/assets/15d83492-40ba-4883-9db4-e655abbc550f" />

2. Semantic Segmentation Layer [link](https://github.com/kiwicampus/semantic_segmentation_layer): A custom nav2 costmap layer plugin inspired on stvl, that integrates semantic segmentation data into the navigation costmap. INCLUDE A NAV2 IMPLEMENTATION.
<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/11f2e4c5-60df-4b37-9eda-10eb8547b120" />

3. Pointclouds GroundSegmentation Intel RealSense [link](https://github.com/open-edge-platform/edge-ai-suites/tree/main/robotics-ai-suite/components/groundfloor/pointcloud_groundfloor_segmentation): This repository contains a realization of an efficient groundfloor segmentation approach for 3D pointclouds. The application comes with three default use cases: standalone use with RealSense camera (or other depth cameras), integration with the Wandering demo on Aaeon robot, and direct use with 3D pointcloud input.

<img width="470" height="270" alt="image" src="https://github.com/user-attachments/assets/07c7ba4f-6241-48e4-b74d-a2368ee5c689" />

# Image segmentation
1. SAM3 ROS Wrapper [link](https://github.com/SanghyunPark01/sam3_ros_wrapper): This repository provides a ROS wrapper for SAM3 (Segment Anything Model 3), compatible with both ROS1 and ROS2. It enables using SAM3-based segmentation within ROS pipelines while keeping the model code and ROS integration loosely coupled.
<img width="415" height="251" alt="image" src="https://github.com/user-attachments/assets/30e6a956-3b41-4cc7-81b4-05fda4488c29" />

https://github.com/yigitbalcioglu/Advanced-Lane-Detection-CLRNet

1. CLRNet Video Lane Pipeline [link](https://github.com/yigitbalcioglu/Advanced-Lane-Detection-CLRNet): This repository is a practical lane-detection project built around CLRNet, focused on running ONNX inference on videos and producing stable, interpretable lane outputs.
2. 
<img width="480" height="360" alt="image" src="https://github.com/user-attachments/assets/fe2f1ec3-e7cf-4073-b5eb-89a1c30a96dd" />
