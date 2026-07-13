# Robotics papers 🌱 🤖
A repository providing a state-of-the-art overview of the most important algorithms as a basis for their use in greenhouse agriculture. It focuses on computer vision algorithms using cameras and LiDARs, amongst other sensors.

<div align="center"> 
  <img width="700" height="300" alt="image" src="https://github.com/user-attachments/assets/fb4ad2c5-85ff-45f7-a888-cdcfb2e47ac8" />
</div>

*Author: Fernando Cañadas Aránega, PhD student in Agriculture Robotics at the University of Almeria, Spain.*

*Gmail: fernando.ca@ual.es*

*Website: https://linktr.ee/FerCanAra*



## Vision algorithms for robotics
<details>
<summary>Classification</summary>

  <details>
  <summary>1. Articles on mathematical foundations</summary>

  1. ImageNet Classification with Deep Convolutional Neural Networks (AlexNet) (2012) [[link](https://dl.acm.org/doi/abs/10.1145/3065386)]. We trained a large, deep convolutional neural network to classify the 1.2 million high-resolution images in the ImageNet LSVRC-2010 contest into the 1000 different classes.
  
  <div align="center"> 
    <img width="400" height="120" alt="image" src="https://github.com/user-attachments/assets/c0b36d27-d13a-46b9-8a08-ff7f1d03ef4c" />
  </div>

  2. CLRNet Video Lane Pipeline [[link](https://github.com/yigitbalcioglu/Advanced-Lane-Detection-CLRNet)]: This repository is a practical lane-detection project built around CLRNet, focused on running ONNX inference on videos and producing stable, interpretable lane outputs.
  <div align="center"> 
    <img width="480" height="360" alt="image" src="https://github.com/user-attachments/assets/fe2f1ec3-e7cf-4073-b5eb-89a1c30a96dd" />
  </div>
  
  3. Deep Residual Learning for Image Recognition (ResNet) [[link](https://arxiv.org/pdf/1512.03385)][[Repository](https://github.com/KaimingHe/deep-residual-networks)]. We explicitly reformulate the layers as learning residual functions with reference to the layer inputs, instead of learning unreferenced functions. 
  
  <div align="center"> 
    <img width="350" height="150" alt="image" src="https://github.com/user-attachments/assets/964b0b6e-dea4-438e-9778-622ad0173606" />
  </div>
  
  4. A ConvNet for the 2020s (ConvNext) [[link](https://arxiv.org/pdf/2201.03545)][[Repository](https://github.com/facebookresearch/ConvNeXt)]. A vanilla ViT, on the other hand, faces difficulties when applied to general computer vision tasks such as object detection and semantic segmentation. It is the hierarchical Transformers (e.g., Swin Transformers) that reintroduced several ConvNet priors, making Transformers practically viable as a generic vision backbone and demonstrating remarkable performance on a wide variety of vision tasks.
  
  <div align="center"> 
    <img width="350" height="200" alt="image" src="https://github.com/user-attachments/assets/9617dd38-49d3-4017-8ac1-6ed2d76525a7" />
  </div>
  </details>
</details>

  <details>
  <summary>2. Articles on greenhouse farming</summary>

  1. High-precision pest and disease detection in greenhouses using the novel IM-AlexNet framework (2025) [[link](https://www.nature.com/articles/s41538-025-00426-7)]]. This study proposes an improved AlexNet (IM-AlexNet) model incorporating ReLU6, batch normalization, and GoogleNet Inception-v3 to enhance pest and disease identification. 

  <div align="center"> 
    <img width="500" height="333" alt="image" src="https://github.com/user-attachments/assets/83e64ee9-d86a-4ad6-9835-a3b6249eab94" />
  </div>

  2. Intelligent Agricultural Greenhouse Extraction Method Based on Multifeature Modeling: Fusion of Geometric, Spatial, and Spectral Characteristics (2025) [[link](https://ieeexplore.ieee.org/abstract/document/10858674)]]. This article proposes an intelligent extraction model that effectively addresses the geometric, spatial, and spectral features of agricultural greenhouses in remote sensing images.

  <div align="center"> 
    <img width="480" height="700" alt="image" src="https://github.com/user-attachments/assets/0a41026b-f485-42f5-a22c-a93c9e2b70c2" />
  </div>

  3. Visual-language transformer-based tomato leaf disease detection for portable greenhouse monitoring device (2025) [[link](https://link.springer.com/article/10.1186/s13007-025-01456-8)]]. This paper introduces the Tomato Leaf Disease Visual Language Model (TLDVLM), a novel approach based on the BLIP-2 architecture enhanced with Low-Rank Adaptation (LoRA), for precise classification of 10 distinct tomato leaf diseases.

  <div align="center"> 
    <img width="400" height="100" alt="image" src="https://github.com/user-attachments/assets/94b6effe-2a71-4e75-b60a-17cfa92dc2d8" />
  </div>

  4. An environment-guided visual–temporal deep learning framework for early disease detection in greenhouse horticultural crops (2026) [[link](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1796407/full)]]. This study provides a practically valuable technical pathway for early intelligent warning and precise regulation of greenhouse crop diseases. 

  <div align="center"> 
    <img width="600" height="140" alt="image" src="https://github.com/user-attachments/assets/7e5a09fd-51b6-40fc-b4c7-4453cdfaf0dc" />
  </div>

  5. Real-Time Monitoring and Disease Detection in Greenhouses Using IoT and Deep Learning (2025) [[link](https://link.springer.com/chapter/10.1007/978-3-031-82733-4_14)]]. A deep learning model, built on the DenseNet121 architecture and trained on a comprehensive plant disease dataset, is embedded within Node-RED to facilitate immediate disease identification, achieving an impressive accuracy of 97.11% across 16,012 images spanning ten classes.

  <div align="center"> 
    <img width="700" height="300" alt="image" src="https://github.com/user-attachments/assets/7eb8340d-600e-4fae-a6d4-e1676792e07b" />
  </div>

  </details>
<details>
<summary>Object detecction</summary>

1. SAM3 ROS Wrapper [[link](https://github.com/SanghyunPark01/sam3_ros_wrapper)]: This repository provides a ROS wrapper for SAM3 (Segment Anything Model 3), compatible with both ROS1 and ROS2. It enables using SAM3-based segmentation within ROS pipelines while keeping the model code and ROS integration loosely coupled.
<div align="center">
  <img width="415" height="251" alt="image" src="https://github.com/user-attachments/assets/30e6a956-3b41-4cc7-81b4-05fda4488c29" />
</div>

2. PointFusion: Deep Sensor Fusion for 3D Bounding Box Estimation [[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_PointFusion_Deep_Sensor_CVPR_2018_paper.pdf)]: a generic 3D object detection
method that leverages both image and 3D point cloud information.
<div align="center">
  <img width="500" height="100" alt="image" src="https://github.com/user-attachments/assets/3dbe2eae-37ba-44d7-830d-50dbe6251c9a" />
</div>

3. Rich Feature Hierarchies for Accurate Object Detection and Semantic Segmentation (R-CNN) [[paper](https://openaccess.thecvf.com/content_cvpr_2014/html/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.html)]: Object detection performance, as measured on the canonical PASCAL VOC dataset, has plateaued in the last few years. The best-performing methods are complex ensemble systems that typically combine multiple low-level image features with high-level context. In this paper, we propose a simple and scalable detection algorithm that improves mean average precision (mAP) by more than 30% relative to the previous best result on VOC 2012—achieving
a mAP of 53.3%.
<div align="center">
  <img width="400" height="150" alt="image" src="https://github.com/user-attachments/assets/42d80b9f-2948-40f1-a128-0d6850efc8a5" />
</div>

4. You Only Look Once: Unified, Real-Time Object Detection (YOLO) [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Redmon_You_Only_Look_CVPR_2016_paper.html)][[Github](https://github.com/mgonzs13/yolo_ros/tree/yolo_ros)]: Object detection performance, as measured on the canonical PASCAL VOC dataset, has plateaued in the last few years. The best-performing methods are complex ensemble systems that typically combine multiple low-level image features with high-level context. In this paper, we propose a simple and scalable detection algorithm that improves mean average precision (mAP) by more than 30% relative to the previous best result on VOC 2012—achieving
a mAP of 53.3%.
<div align="center">
  <img width="400" height="150" alt="image" src="https://github.com/user-attachments/assets/42d80b9f-2948-40f1-a128-0d6850efc8a5" />
</div>

</details>
<details>
<summary>Segmentation</summary>

2. Semantic Segmentation Layer [[link](https://github.com/kiwicampus/semantic_segmentation_layer)]: A custom nav2 costmap layer plugin inspired on stvl, that integrates semantic segmentation data into the navigation costmap. INCLUDE A NAV2 IMPLEMENTATION.
<div align="center">
  <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/11f2e4c5-60df-4b37-9eda-10eb8547b120" />
</div>

3. Pointclouds GroundSegmentation Intel RealSense [[link](https://github.com/open-edge-platform/edge-ai-suites/tree/main/robotics-ai-suite/components/groundfloor/pointcloud_groundfloor_segmentation)]: This repository contains a realization of an efficient groundfloor segmentation approach for 3D pointclouds. The application comes with three default use cases: standalone use with RealSense camera (or other depth cameras), integration with the Wandering demo on Aaeon robot, and direct use with 3D pointcloud input.
<div align="center">
  <img width="470" height="270" alt="image" src="https://github.com/user-attachments/assets/07c7ba4f-6241-48e4-b74d-a2368ee5c689" />
</div>


</details>
<details>
<summary>Generative</summary>


</details>









## LiDAR algorithms for robotics
<details>
<summary>Vision algorithms for robotics</summary>


1. Ground Segmentation ROS 2 Node (GSeg3D) [[link](https://github.com/dfki-ric/ground_segmentation_ros2?tab=readme-ov-file)]: This package implements a ROS 2 node that wraps the GSeg3D ground segmentation algorithm and exposes it as a real-time perception component for robotic systems. The node subscribes to LiDAR point clouds (optionally synchronized with IMU data), performs two-phase grid-based ground segmentation, and publishes ground and obstacle point clouds for downstream navigation and perception modules. INCLUDE A NAV2 IMPLEMENTATION.
<div align="center">
  <img width="450" height="180" alt="image" src="https://github.com/user-attachments/assets/15d83492-40ba-4883-9db4-e655abbc550f" />
</div>


VERY DEEP CONVOLUTIONAL NETWORKS FOR LARGE-SCALE IMAGE RECOGNITION

</details>




## Robotics tools

<details>
<summary>Maps generative</summary>

[ROS-SLAM-Map-Editor](https://github.com/GyroPalm/ROS-SLAM-Map-Editor): A web-based map editor for quick editing of ROS and ROS2 SLAM maps

<div align="center">
  <img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/a2783929-038d-4e8f-a857-d5553352ffc4" />
</div>

</details>




