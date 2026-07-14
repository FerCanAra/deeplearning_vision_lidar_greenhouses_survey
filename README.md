# Robotics papers 🌱 🤖
A repository providing a state-of-the-art overview of the most important algorithms as a basis for their use in greenhouse agriculture. It focuses on computer vision algorithms using cameras and LiDARs, amongst other sensors.

<div align="center"> 
  <img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/fb4ad2c5-85ff-45f7-a888-cdcfb2e47ac8" />
</div>

*Author: Fernando Cañadas Aránega, PhD student in Agricultural Robotics at the University of Almería, Spain.*

*Gmail: fernando.ca@ual.es*

*Website: https://linktr.ee/FerCanAra*

## Vision algorithms for robotics

The foundational articles underpinning the most significant advances in vision technology are available for subsequent application in agriculture, specifically in greenhouses.

<div align="center">
  <img width="500" height="423" alt="image" src="https://github.com/user-attachments/assets/f28ec83f-27d0-4b56-ac4e-cbc57965b4b6" />
</div>

<details>
<summary><strong>Classification</strong></summary>

<details>
  <summary><strong>1. Articles on mathematical foundations</strong></summary>

  1. Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). _Imagenet classification with deep convolutional neural networks (AlexNet)_. Advances in neural information processing systems, 25. [[paper](https://dl.acm.org/doi/abs/10.1145/3065386)].
  
  2. He, K., Zhang, X., Ren, S., & Sun, J. (2016). _Deep residual learning for image recognition (ResNet)_. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 770-778). [[paper](https://arxiv.org/pdf/1512.03385)].

  3. Huang, G., Liu, Z., Van Der Maaten, L., & Weinberger, K. Q. (2017). _Densely connected convolutional networks (DenseNet)_. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 4700-4708). [[paper](https://arxiv.org/abs/1608.06993)].

  4. Tan, M., & Le, Q. (2019). _Efficientnet: Rethinking model scaling for convolutional neural networks_. In International conference on machine learning (pp. 6105-6114). PMLR. [[paper](https://arxiv.org/abs/1608.06993)]. 

  5. Dosovitskiy, A., Beyer, L., Kolesnikov, A., Weissenborn, D., Zhai, X., Unterthiner, T., Mostafa, D., Mattias, M., Georg, H., Sylvain, G., Jakob, U., & Houlsby, N. (2020). _An image is worth 16x16 words: Transformers for image recognition at scale (ViT)_. arXiv preprint arXiv:2010.11929. [[paper](https://arxiv.org/pdf/2010.11929/100)].

 6. Liu, Z., Lin, Y., Cao, Y., Hu, H., Wei, Y., Zhang, Z., Stephen, L., & Guo, B. (2021). _Swin transformer: Hierarchical vision transformer using shifted windows_. In Proceedings of the IEEE/CVF international conference on computer vision (pp. 10012-10022). [[paper](https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Swin_Transformer_Hierarchical_Vision_Transformer_Using_Shifted_Windows_ICCV_2021_paper)].

  7. Liu, Z., Mao, H., Wu, C. Y., Feichtenhofer, C., Darrell, T., & Xie, S. (2022). A convnet for the 2020s. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 11976-11986). [[paper](https://arxiv.org/pdf/2201.03545)].

</details>
<details>
  <summary><strong>2. Articles on greenhouse farming</strong></summary>

  ### AlexNet Algoritm


  ### VGG Algoritm
  1. High-precision pest and disease detection in greenhouses using the novel IM-AlexNet framework (2025) [[link](https://www.nature.com/articles/s41538-025-00426-7)]]. This study proposes an improved AlexNet (IM-AlexNet) model incorporating ReLU6, batch normalization, and GoogleNet Inception-v3 to enhance pest and disease identification. 

  <div align="center"> 
    <img width="500" height="333" alt="image" src="https://github.com/user-attachments/assets/83e64ee9-d86a-4ad6-9835-a3b6249eab94" />
  </div>

  2. Transfer Learning for Multi-Crop Leaf Disease Image Classification using Convolutional Neural Network VGG (2026) [[link](https://www.sciencedirect.com/science/article/pii/S2589721721000416)]]. The CNN based Visual Geometry Group (VGG) model is used for improved performance measures. The crops leaves images dataset is considered for training and testing the model. 

  <div align="center"> 
    <img width="712" height="244" alt="image" src="https://github.com/user-attachments/assets/e6ddeebf-1d13-4bc2-bd01-9f844303bab1" />
  </div>

  3. Intelligent Agricultural Greenhouse Extraction Method Based on Multifeature Modeling: Fusion of Geometric, Spatial, and Spectral Characteristics (2025) [[link](https://ieeexplore.ieee.org/abstract/document/10858674)]]. This article proposes an intelligent extraction model that effectively addresses the geometric, spatial, and spectral features of agricultural greenhouses in remote sensing images.

  <div align="center"> 
    <img width="480" height="700" alt="image" src="https://github.com/user-attachments/assets/0a41026b-f485-42f5-a22c-a93c9e2b70c2" />
  </div>

  4. Visual-language transformer-based tomato leaf disease detection for portable greenhouse monitoring device (2025) [[link](https://link.springer.com/article/10.1186/s13007-025-01456-8)]]. This paper introduces the Tomato Leaf Disease Visual Language Model (TLDVLM), a novel approach based on the BLIP-2 architecture enhanced with Low-Rank Adaptation (LoRA), for precise classification of 10 distinct tomato leaf diseases.

  <div align="center"> 
    <img width="400" height="100" alt="image" src="https://github.com/user-attachments/assets/94b6effe-2a71-4e75-b60a-17cfa92dc2d8" />
  </div>

  5. An environment-guided visual–temporal deep learning framework for early disease detection in greenhouse horticultural crops (2026) [[link](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1796407/full)]]. This study provides a practically valuable technical pathway for early intelligent warning and precise regulation of greenhouse crop diseases. 

  <div align="center"> 
    <img width="600" height="140" alt="image" src="https://github.com/user-attachments/assets/7e5a09fd-51b6-40fc-b4c7-4453cdfaf0dc" />
  </div>

  6. Real-Time Monitoring and Disease Detection in Greenhouses Using IoT and Deep Learning (2025) [[link](https://link.springer.com/chapter/10.1007/978-3-031-82733-4_14)]]. A deep learning model, built on the DenseNet121 architecture and trained on a comprehensive plant disease dataset, is embedded within Node-RED to facilitate immediate disease identification, achieving an impressive accuracy of 97.11% across 16,012 images spanning ten classes.

  <div align="center"> 
    <img width="700" height="300" alt="image" src="https://github.com/user-attachments/assets/7eb8340d-600e-4fae-a6d4-e1676792e07b" />
  </div>

  7. CLRNet Video Lane Pipeline [[link](https://github.com/yigitbalcioglu/Advanced-Lane-Detection-CLRNet)]: This repository is a practical lane-detection project built around CLRNet, focused on running ONNX inference on videos and producing stable, interpretable lane outputs.
  <div align="center"> 
    <img width="480" height="360" alt="image" src="https://github.com/user-attachments/assets/fe2f1ec3-e7cf-4073-b5eb-89a1c30a96dd" />
  </div>

  
  </details>
</details>

</details>
<details>
<summary><strong>Object detecction</strong></summary>

<details>
  <summary><strong>1. Articles on mathematical foundations</strong></summary>

  1. Girshick, R., Donahue, J., Darrell, T., & Malik, J. (2014). _Rich feature hierarchies for accurate object detection and semantic segmentation (R-CNN)_. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 580-587). [[paper](https://openaccess.thecvf.com/content_cvpr_2014/html/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.html)].
  
  2. Girshick, R. (2015). _Fast r-cnn_. In Proceedings of the IEEE international conference on computer vision (pp. 1440-1448). [[paper](https://openaccess.thecvf.com/content_iccv_2015/html/Girshick_Fast_R-CNN_ICCV_2015_paper.html)].

  3. Ren, S., He, K., Girshick, R., & Sun, J. (2015). _Faster r-cnn: Towards real-time object detection with region proposal networks_. Advances in neural information processing systems, 28. [[paper](https://proceedings.neurips.cc/paper/2015/hash/14bfa6bb14875e45bba028a21ed38046-Abstract.html)].

  4. Redmon, J., Divvala, S., Girshick, R., & Farhadi, A. (2016). _You only look once: Unified, real-time object detection (YOLO)_. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 779-788). [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Redmon_You_Only_Look_CVPR_2016_paper.html)] 

  5. Liu, W., Anguelov, D., Erhan, D., Szegedy, C., Reed, S., Fu, C. Y., & Berg, A. C. (2016). SSD: Single shot multibox detector. In European conference on computer vision (pp. 21-37). Cham: Springer International Publishing. [[paper](https://link.springer.com/chapter/10.1007/978-3-319-46448-0_2)].

 6. Lin, T. Y., Goyal, P., Girshick, R., He, K., & Dollár, P. (2017). _Focal loss for dense object detection (RetinaNet)_. In Proceedings of the IEEE international conference on computer vision (pp. 2980-2988). [[paper](https://openaccess.thecvf.com/content_iccv_2017/html/Lin_Focal_Loss_for_ICCV_2017_paper.html)].

  7. Carion, N., Massa, F., Synnaeve, G., Usunier, N., Kirillov, A., & Zagoruyko, S. (2020). _End-to-end object detection with transformers (DETR)_. In European conference on computer vision (pp. 213-229). Cham: Springer International Publishing. [[paper](https://link.springer.com/chapter/10.1007/978-3-030-58452-8_13)].

  8. He, K., Gkioxari, G., Dollár, P., & Girshick, R. (2017). _Mask R-CNN_. In Proceedings of the IEEE international conference on computer vision (pp. 2961-2969). [[paper](https://openaccess.thecvf.com/content_iccv_2017/html/He_Mask_R-CNN_ICCV_2017_paper.html)].

</details>
<details>
  <summary><strong>2. Articles on greenhouse farming</strong></summary>
  
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
</details>

<details>
<summary><strong>Segmentation</strong></summary>

<details>
  <summary><strong>1. Articles on mathematical foundations</strong></summary>

  1. Long, J., Shelhamer, E., & Darrell, T. (2015). _Fully convolutional networks for semantic segmentation (FCN)_. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 3431-3440). [[paper](https://openaccess.thecvf.com/content_cvpr_2015/html/Long_Fully_Convolutional_Networks_2015_CVPR_paper.html)].
  
  2. Ronneberger, O., Fischer, P., & Brox, T. (2015). _U-net: Convolutional networks for biomedical image segmentation_. In International Conference on Medical image computing and computer-assisted intervention (pp. 234-241). Cham: Springer international publishing. [[paper](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28)].

  3. Chen, L. C., Papandreou, G., Kokkinos, I., Murphy, K., & Yuille, A. L. (2017). _Deeplab: Semantic image segmentation with deep convolutional nets, atrous convolution, and fully connected crfs_. IEEE transactions on pattern analysis and machine intelligence, 40(4), 834-848. [[paper](https://ieeexplore.ieee.org/abstract/document/7913730)].

  4. Zhao, H., Shi, J., Qi, X., Wang, X., & Jia, J. (2017). _Pyramid scene parsing network (PSPNet)_. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 2881-2890). [[paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Zhao_Pyramid_Scene_Parsing_CVPR_2017_paper.html)] 

  5. Xie, E., Wang, W., Yu, Z., Anandkumar, A., Alvarez, J. M., & Luo, P. (2021). _SegFormer: Simple and efficient design for semantic segmentation with transformers_. Advances in neural information processing systems, 34, 12077-12090. [[paper](https://proceedings.neurips.cc/paper/2021/hash/64f1f27bf1b4ec22924fd0acb550c235-Abstract.html)].

 6. Kirillov, A., Mintun, E., Ravi, N., Mao, H., Rolland, C., Gustafson, L., Tete, X., Spencer, W., Alexander, B., Wan-Yen, L., Piotr, D., & Girshick, R. (2023). _Segment anything (SAM)_. In Proceedings of the IEEE/CVF international conference on computer vision (pp. 4015-4026). [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Kirillov_Segment_Anything_ICCV_2023_paper.html)].

</details>

<details>
  <summary><strong>2. Articles on greenhouse farming</strong></summary>

2. Semantic Segmentation Layer [[link](https://github.com/kiwicampus/semantic_segmentation_layer)]: A custom nav2 costmap layer plugin inspired on stvl, that integrates semantic segmentation data into the navigation costmap. INCLUDE A NAV2 IMPLEMENTATION.
<div align="center">
  <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/11f2e4c5-60df-4b37-9eda-10eb8547b120" />
</div>

3. Pointclouds GroundSegmentation Intel RealSense [[link](https://github.com/open-edge-platform/edge-ai-suites/tree/main/robotics-ai-suite/components/groundfloor/pointcloud_groundfloor_segmentation)]: This repository contains a realization of an efficient groundfloor segmentation approach for 3D pointclouds. The application comes with three default use cases: standalone use with RealSense camera (or other depth cameras), integration with the Wandering demo on Aaeon robot, and direct use with 3D pointcloud input.
<div align="center">
  <img width="470" height="270" alt="image" src="https://github.com/user-attachments/assets/07c7ba4f-6241-48e4-b74d-a2368ee5c689" />
</div>


</details>
</details>
<details>
<summary><strong>Generative</strong>strong></summary>


<details>
  <summary><strong>1. Articles on mathematical foundations</strong></summary>

  1. Karras, T., Laine, S., & Aila, T. (2019). _A style-based generator architecture for generative adversarial networks (StyleGAN)_. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 4401-4410). [[paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Karras_A_Style-Based_Generator_Architecture_for_Generative_Adversarial_Networks_CVPR_2019_paper.html)].
  
  2. Zhu, J. Y., Park, T., Isola, P., & Efros, A. A. (2017). _Unpaired image-to-image translation using cycle-consistent adversarial networks (CycleGAN)_. In Proceedings of the IEEE international conference on computer vision (pp. 2223-2232). [[paper](https://openaccess.thecvf.com/content_iccv_2017/html/Zhu_Unpaired_Image-To-Image_Translation_ICCV_2017_paper.html)].

  3. Rombach, R., Blattmann, A., Lorenz, D., Esser, P., & Ommer, B. (2022). _High-resolution image synthesis with latent diffusion models (Stable Diffusion)_. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 10684-10695). [[paper](https://openaccess.thecvf.com/content/CVPR2022/html/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.html?utm_source=rns.dwaiai.de)].

  4. Ramesh, A., Pavlov, M., Goh, G., Gray, S., Voss, C., Radford, A., Chen, M., & Sutskever, I. (2021). _Zero-shot text-to-image generation (DALL-E)_. In International conference on machine learning (pp. 8821-8831). Pmlr. [[paper](https://proceedings.mlr.press/v139/ramesh21a.html?ref=journey)] 

  5. Radford, A., Metz, L., & Chintala, S. (2015). _Unsupervised representation learning with deep convolutional generative adversarial networks (DCGAN)_. arXiv preprint arXiv:1511.06434. [[paper](https://arxiv.org/abs/1511.06434)].


</details>


<details>
  <summary><strong>2. Articles on greenhouse farming</strong></summary>


</details>

</details>









## LiDAR algorithms for robotics
<div align="center">
  <img width="500" height="432" alt="image" src="https://github.com/user-attachments/assets/55cb1db4-f464-4f9b-a0f3-fdebc508851b" />
</div>


<details>
<summary>Vision algorithms for robotics</summary>


1. Ground Segmentation ROS 2 Node (GSeg3D) [[link](https://github.com/dfki-ric/ground_segmentation_ros2?tab=readme-ov-file)]: This package implements a ROS 2 node that wraps the GSeg3D ground segmentation algorithm and exposes it as a real-time perception component for robotic systems. The node subscribes to LiDAR point clouds (optionally synchronized with IMU data), performs two-phase grid-based ground segmentation, and publishes ground and obstacle point clouds for downstream navigation and perception modules. INCLUDE A NAV2 IMPLEMENTATION.
<div align="center">
  <img width="450" height="180" alt="image" src="https://github.com/user-attachments/assets/15d83492-40ba-4883-9db4-e655abbc550f" />
</div>


VERY DEEP CONVOLUTIONAL NETWORKS FOR LARGE-SCALE IMAGE RECOGNITION
</details>
</details>




## Robotics tools

<details>
<summary>Maps generative</summary>

[ROS-SLAM-Map-Editor](https://github.com/GyroPalm/ROS-SLAM-Map-Editor): A web-based map editor for quick editing of ROS and ROS2 SLAM maps

<div align="center">
  <img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/a2783929-038d-4e8f-a857-d5553352ffc4" />
</div>

</details>




