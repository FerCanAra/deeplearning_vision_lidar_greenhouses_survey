# Machine Learning in Precision Agriculture Robotics: A Systematic Review of Vision and LiDAR Perception in Greenhouses 🌱 🤖

[![arXiv](https://img.shields.io/badge/arXiv-preprint-b31b1b.svg)](https://arxiv.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Updated](https://img.shields.io/badge/last%20updated-2026--09-blue)](.)
[![Papers Reviewed](https://img.shields.io/badge/papers%20reviewed-208-success)](.)
 
A curated, actively maintained repository accompanying our systematic review on machine learning algorithms for vision and LiDAR perception in greenhouse mobile robotics. It provides a structured, browsable overview of the foundational algorithms and the 208 primary studies analyzed, organized around four scopes — **classification, detection, segmentation, and generation/reconstruction** — for both **vision** and **3D LiDAR** modalities.

<div align="center"> 
  <img width="607" height="415" alt="image" src="https://github.com/user-attachments/assets/df75a052-c2bd-43d0-badb-564b9c739569" />
</div>

*Author: Fernando Cañadas Aránega, PhD student in Agricultural Robotics at the University of Almería, Spain.*

*Gmail: fernando.ca@ual.es*

*Website: https://linktr.ee/FerCanAra*

<!-- Algoritmo de visión que utilizan -->

## Citation

If you use this repository or the associated review, please cite:

```bibtex
Soon!
```
 
## Vision algorithms for robotics

The foundational articles underpinning the most significant advances in vision technology are available for subsequent application in agriculture, specifically in greenhouses.

<div align="center">
  <!-- <img width="500" height="423" alt="image" src="https://github.com/user-attachments/assets/f28ec83f-27d0-4b56-ac4e-cbc57965b4b6" />-->
<img width="490" height="320" alt="image" src="https://github.com/user-attachments/assets/a0c0ad92-91d9-44a3-b047-3f4e9b0489b2" />
</div>

<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ---------------------------------------------------------- Clasification --------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->

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
    <summary><strong>2. Articles on greenhouses</strong></summary>
  
  1. Mashamba, M. M., Telukdarie, A., Munien, I., Onkonkwo, U., & Vermeulen, A. (2024). *Detection of bacterial spot disease on tomato leaves using a Convolutional Neural Network (CNN)*. Procedia Computer Science, 237, 602-609. [[paper](https://www.sciencedirect.com/science/article/pii/S187705092401161X)].
  
  2. Tang, R., Aridas, N. K., Talip, M. S. A., Yang, J., & Tang, J. (2025). *High-precision pest and disease detection in greenhouses using the novel IM-AlexNet framework*. npj Science of Food, 9(1), 68. [[paper](https://www.nature.com/articles/s41538-025-00426-7)].
  
  3. Rao, S. T., Dulla, T. C., Kolla, V. K., Kurakula, G. S., Suneetha, M., Moturi, S., & Reddy, D. V. (2025). Deep-learning-based tomato leaf disease identification: Enhancing classification with AlexNet. IEEE IATMSI, Vol. 3, pp. 1-6. [[paper](https://ieeexplore.ieee.org/abstract/document/10984969)].
  
  4. Jiang, N. (2025). Crop disease detection for greenhouses: a lightweight solution combining ResNet and Inception. SPIE IC-AAIP 2025, Vol. 13933, pp. 50-56. [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13933/1393309/Crop-disease-detection-for-greenhouses--a-lightweight-solution-combining/10.1117/12.3090705.short)].
  
  5. Wang, L., Li, Y., Lin, H., Tong, J., Sun, L., Wang, X., & Jiang, J. (2025). RTR-CNN: Rotated tray region selection and young seedling health status detection by CNN in greenhouse seedbed. Computers and Electronics in Agriculture, 229, 109723. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169924011141)].
  
  6. Zhang, L., Li, X., Yang, Z., Yang, B., Yu, S., Zhao, S., et al. (2025). Tomato seedling stem and leaf segmentation method based on an improved ResNet architecture. Frontiers in Plant Science, 16, 1571445. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1571445/full)].
  
  7. Cohen, A., Muriki, H., Sun, Y., Qin, Z., Gan, L., & Chen, Y. (2025). A Proof-of-Concept for Non-Destructive Lettuce Nutrient Assessment Using Vision Transformers and Residual Networks on Raw Hyperspectral Imagery. Smart Agricultural Technology, 101501. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525007324)].
  
  8. Jain, S., & Rajpoot, R. (2025). Real-Time Monitoring and Disease Detection in Greenhouses Using IoT and Deep Learning. In Computational Intelligence Techniques for 5G Enabled IoT Networks (pp. 213-235). Springer. [[paper](https://link.springer.com/chapter/10.1007/978-3-031-82733-4_14)].
  
  9. Kavitha, K. (2025). Deep Learning-Driven Computer Vision Techniques for Advancing Smart Greenhouse Agriculture. IEEE ICSCN 2025, pp. 24-30. [[paper](https://ieeexplore.ieee.org/abstract/document/11308643)].
  
  10. Saxena, A., Agarwal, A., Nagrath, B., Jayavanth, C. S., Thulasidoss, S., Maheswari, S., & Sasikumar, P. (2025). Deep learning-driven IoT solution for smart tomato farming. Scientific Reports, 15(1), 31092. [[paper](https://www.nature.com/articles/s41598-025-15615-)].
  
  11. Pounambal, M., & Vellingiri, J. (2025). Advancing agricultural sustainability with gradient weighted Densenet-201 model for accurate detection of plant leaf diseases. Environment, Development and Sustainability, 1-27. [[paper](https://link.springer.com/article/10.1007/s10668-025-06314-0)].
  
  12. Alam, M. S., Ali, M. R., & Rahman, A. (2025). Detection and Localization of Ripe Tomato in Greenhouse Environment Using Keras-Based Deep Learning Models. Journal of Agriculture and Food Research, 102182. [[paper](https://www.sciencedirect.com/science/article/pii/S2666154325005538)].
  
  13. Shi, D., Liang, L., Chen, X., Yang, X., Li, M., & Diao, M. (2025). DTM-Unet: A Deep Learning Framework Incorporating DenseNet and Transformer for Precise Identification and Quantitative Segmentation of Cucumber Leaf Disease. Smart Agricultural Technology, 101659. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525008901)].
  
  14. Sajid, S., Li, P., Zhang, L., Jie, C., Ali, A., & Ullah, F. (2025). Leveraging VGG-19 for automated fruit classification in smart agriculture. PeerJ Computer Science, 11, e3391. [[paper](https://peerj.com/articles/cs-3391/)].
  
  15. Siva, V., & Ponnusamy, V. (2025). Tomato Ripeness Evaluation Through Cutting-Edge Deep Learning Models. World Conf. on Information Systems for Business Management, pp. 413-423. Springer. [[paper](https://link.springer.com/chapter/10.1007/978-3-032-13006-8_40)].
  
  16. Ray, R. K., Chakravarty, S., Dash, S., Ghosh, A., Mohanty, S. N., Chirra, V. R. R., et al. (2025). Precision pest management in agriculture using Inception V3 and EfficientNet B4: A deep learning approach for crop protection. Information Processing in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2214317325000484)].
  
  17. Shanthini, S., & Dheeran, S. (2025). EfficientNet-Based Feature Extraction and Ensemble Learning for Tomato Quality Classification. IEEE ISACC 2025, pp. 589-595. [[paper](https://ieeexplore.ieee.org/abstract/document/10969232)].
  
  18. Wang, X. (2025). EfficientNet-SE: A Lightweight Attention-Enhanced CNN for Real-Time Crop Leaf Disease Detection in Precision Agriculture. IEEE IoTAIMA 2025, pp. 63-67. [[paper](https://ieeexplore.ieee.org/abstract/document/11212650)].
  
  19. Zeng, Z., Mahmood, T., Wang, Y., Rehman, A., & Mujahid, M. A. (2025). AI-driven smart agriculture using hybrid transformer-CNN for real time disease detection in sustainable farming. Scientific Reports, 15(1), 25408. [[paper](https://www.nature.com/articles/s41598-025-10537-6)].
  
  20. Verma, P. K., Gupta, N., Sharma, A. K., Rakesh, N., & Gulhane, M. (2025). ViTCon: a hybrid CNN-ViT model for improved plant leaf disease detection. Cogent Food & Agriculture, 11(1), 2562165. [[paper](https://www.tandfonline.com/doi/full/10.1080/23311932.2025.2562165)].
  
  21. Huo, Y., Liu, Y., He, P., Hu, L., Gao, W., & Gu, L. (2025). Identifying Tomato Growth Stages in Protected Agriculture with StyleGAN3–Synthetic Images and Vision Transformer. Agriculture, 15(2), 120. [[paper](https://www.mdpi.com/2077-0472/15/2/120)].
  
  22. Guttikonda, B. S., Al-Khafaji, Z. A., Senthil, P., & Kavitha, P. (2025). Smart Agriculture Framework for Multi-Crop Disease Detection using IoT and Vision Transformer. IEEE ICICKE 2025, pp. 1-7. [[paper](https://ieeexplore.ieee.org/abstract/document/11136532)].
  
  23. Iftee, I. K., Ahmed, F., Jobaier, M. H., Osama, A. U., & Aziz, N. H. A. (2025). Smart Agriculture: Cucurbit Leaf Disease Detection Using Swin Transformer. IEEE ICEET 2025, pp. 1-6. [[paper](https://ieeexplore.ieee.org/abstract/document/11423931)].
  
  24. Zhang, H., Gong, Z., Hu, C., Chen, C., Wang, Z., Yu, B., et al. (2025). A transformer-based detection network for precision cistanche pest and disease management in smart agriculture. Plants, 14(4), 499. [[paper](https://link.springer.com/chapter/10.1007/978-981-96-8796-1_19)].
  
  25. Murugesan, S., Chinnadurai, J., Srinivasan, S., Mathivanan, S. K., Chandan, R. R., & Moorthy, U. (2025). Robust multiclass classification of crop leaf diseases using hybrid deep learning and Grad-CAM interpretability. Scientific Reports, 15(1), 29955. [[paper](https://www.nature.com/articles/s41598-025-14847-7)].
  
  26. Landolfo, M., Perotti, F., Pistillo, A., Pennisi, G., Gianquinto, G., & Orsini, F. (2025). Optimizing artificial lighting for convolutional neural network-based crop monitoring with low-cost RGB imaging in indoor cultivation. Smart Agricultural Technology, 101677. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525009086)].
  
  27. Bashir, A., Wang, Y., Ojo, M. O., & Zahid, A. (2025). A Vision System for Occluded Cutting Point Localization in Robotic Harvesting of Greenhouse Lettuce. IEEE Transactions on AgriFood Electronics. [[paper](https://ieeexplore.ieee.org/abstract/document/11219194)].
  
  28. Cardenas-Gallegos, J. S., Severns, P. M., Klimeš, P., Lacerda, L. N., Peduzzi, A., & Ferrarezi, R. S. (2025). Reliable plant segmentation under variable greenhouse illumination conditions. Computers and Electronics in Agriculture, 229, 109711. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169924011025)].
  
  29. Amir, A., Giri, S., Giri, S., & Butt, M. (2025). An advanced approach to tomato apex head thickness measurement using lightweight YOLO variants, faster RCNN, and RGB-depth sensor. Smart Agricultural Technology, 101214. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525004459)].
  
  30. Bhaskar, C. G., Krishnan, C. A., & Manimekala, B. (2026). Automated tomato leaf disease diagnosis with improved Alex Net model. AIP Conference Proceedings, Vol. 3427, No. 1, 020015. [[paper](https://pubs.aip.org/aip/acp/article-abstract/3427/1/020015/3392439/Automated-tomato-leaf-disease-diagnosis-with)].
  
  31. Zhang, K., Chai, Q., Gao, R., Shen, A., Liu, X., Yang, L., et al. (2026). Deep learning-powered diagnosis of greenhouse tomato growth using time-series RGB images. Computers and Electronics in Agriculture, 245, 111566. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169926001614)].
  
  32. Yusof, M. I., Yasin, F. N. M., Risangtuni, A. G., Putra, N. K., Samseh, S. H., Zainal, A., & Sani, M. A. A. (2026). Enhancing Greenhouse Pollination with CNN-Based Micro-UAV for Real-Time Flower Detection. [[paper](https://www.preprints.org/manuscript/202602.2026)].
  
  33. Liang, L., Chen, J., Tian, Y., Wang, H., Cai, Y., Zhong, F., Wang, A., Hou, M., & Lu, J. (2026). DenseNet-BiFPN-ECA Fusion Network: An Enhanced Transfer Learning Approach for Tomato Leaf Disease Recognition. Horticulturae, 12(4), 423. [[paper](https://www.mdpi.com/2311-7524/12/4/423)].
  
  34. Santoso, H. A., Fandhi Safsalta, B., Febrianto, N., Wilujeng Saraswati, G., & Haw, S. C. (2026). Comparative analysis of convolutional neural network and DenseNet121 transfer learning in agriculture focusing on crop leaf disease identification. Applied Computing and Informatics, 22(3-4), 316-328. [[paper](https://www.emerald.com/aci/article/22/3-4/316/1248414)].
  
  35. Huang, Y., Huang, T., Du, J., Qiu, J., Liu, C., Wan, F., et al. (2026). DenseNet-CSL: An Enhanced Network for Multi-Class Recognition of Agricultural Pests, Weeds, and Crop Diseases. Agriculture, 16(4), 394. [[paper](https://www.mdpi.com/2077-0472/16/4/394)].
  
  36. Sundaravadivel, P., Reyes-Ramirez, R., Sethurani, P. M., Brown, C., Borah, S. S., & Kousik, S. (2026). AI-Enabled Reconfigurable Edge Device for Plant Health Assessment in Greenhouse Environment. First Int. Workshop on AI in Agriculture. [[paper](https://openreview.net/forum?id=7GDdzjv6EZ)].
  
  37. Ni, L., Ye, F., Cui, X., Peng, X., Song, S., & Luo, W. (2026). Comparative Study of Lightweight Deep Learning Models for Greenhouse Tomato Leaf Disease Classification Using the Public TLID Dataset. Digital Intelligence in Agriculture, 2(1), 45-53. [[paper](https://www.icck.org/article/abs/dia.2026.103152)].
  
  38. Subhan, M., Rana, N., Qamar, F., Jeribi, F., Alhazmi, A. H., Tahir, A., & Shahzadi, R. (2026). Crop disease detection using EfficientNetB0 deep learning approach for precision agriculture. Discover Computing, 29(1), 25. [[paper](https://link.springer.com/article/10.1007/s10791-025-09881-y)].
  
  39. Rajendran, M., & Muruganantham, M. (2026). Tomato leaf disease classification using a vision transformer with cascaded group attention (ViT-CGA) for real-time decision support in precision agriculture. Journal of Plant Diseases and Protection, 133(3), 91. [[paper](https://link.springer.com/article/10.1007/s41348-026-01274-7)].
  
  40. Venkatesh, K., Prasad, M., Kurikala, G., & Singh, L. K. (2026). Crop Health Identification by Exploiting CNN-ViT Synergy: Detecting Multi-Nutrient Deficiencies. IEEE AICAPS 2026, pp. 1-4. [[paper](https://ieeexplore.ieee.org/abstract/document/11452925)].
  
  41. Liu, H., Gan, Y., Ren, X., Xu, J., Lin, P., & Chen, Y. (2026). Vision-based quantitative assessment of strawberry ripeness using a detail-aware perception transformer in complex agricultural environments. Journal of Food Measurement and Characterization, 20(4), 6418-6440. [[paper](https://link.springer.com/article/10.1007/s11694-026-04078-3)].
  
  42. Haqiq, N., Zaim, M., Sbihi, M., El Alaoui, M., El Amraoui, K., El Kazini, Y., Roukhe, H., & Masmoudi, L. (2026). Lightweight Hybrid Deep Learning for Strawberry Disease Recognition and Edge Deployment Using Dynamic Multi-Scale CNN–Transformer Fusion. AgriEngineering, 8(2), 75. [[paper](https://www.mdpi.com/2624-7402/8/2/75)].
  
  43. Zhang, Q., Zhao, J., Cai, Y. L., Liu, K., & Li, Y. (2026). Toward smart agriculture: a hybrid mamba-transformer vision framework for plant disease detection. Frontiers in Plant Science, 17, 1846242. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1846242/full)].
  
  44. Vanmathi, C., Mangayarkarasi, R., Agrawal, R., Sumalatha, L., & Shankar, V. (2026). Cross Disease Similarity Awareness Learning (CDSAL) with DenseNet–EfficientNet embedding fusion for high-precision tomato leaf pathology classification with Grad-CAM explainability. Scientific Reports. [[paper](https://www.nature.com/articles/s41598-026-48099-w)].
  
  45. Xing, X., Gao, J., Qi, P., Wang, S., Wang, F., Peng, X., Fangyan, W., Hou, X., & Gao, J. (2026). A Lightweight Multi-View Detection and Counting Method for Real-Time Cherry Tomato Yield Estimation Using Greenhouse Inspection Robots. Smart Agricultural Technology, 102260. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526004843)].
  
  46. Guo, J., Zhang, B., Zhou, P., Xu, Y., Luo, S., Ji, J., Zhuo, Y., Xu, X., & Lin, L. (2026). A Digital Framework for Smart Greenhouse Tomato Cultivation. Smart Agricultural Technology, 101879. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526001036)].
  
  </details>
  
  <details>
    <summary><strong>3. Entries excluded based on PRISMA</strong></summary>
  
  1. Ragavee, U., Oviya, R., & KR, N. (2025). *Renewable Energy-Driven IoT System for Automated Greenhouse Monitoring*. IEEE ICECIT 2025, pp. 1-6. — Reason: IoT monitoring system paper, not a classification-algorithm study retained in the final table. [[paper](https://ieeexplore.ieee.org/abstract/document/11450958)].
  
  2. Zimmermann, G. B., Pellenz, M. E., Costa, Y. M., & Britto Jr, A. D. S. (2025). *Enhancing Disease and Pest Detection in Greenhouse Tomato Cultivation Using Advanced Machine Learning on New Dataset of Images*. Journal of the Brazilian Computer Society, 31(1). — Reason: not referenced by any citation key in the final Classification table; original link also carried an exposed institutional access token and was not reused. [[paper](https://openurl.ebsco.com/EPDB%3Agcd%3A16%3A20183152/detailv2)].
  
  3. Parvez, S., Uddin, M. A., Islam, M. M., Bharman, P., & Talukder, M. A. (2025). *Tomato leaf disease detection using convolutional neural network*. In Applied Intelligence for Healthcare Informatics (pp. 42-55). CRC Press. — Reason: book chapter not selected as a primary study in the final table. [[paper](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003583363-4/tomato-leaf-disease-detection-using-convolutional-neural-network-shamima-parvez-md-ashraf-uddin-md-manowarul-islam-pallab-bharman-md-alamin-talukder)].
  
  4. Kiran, K., Gopal, L., Agarwal, V., Bansal, V., & Gupta, R. (2026). *CNN-Based Tomato Leaf Disease Detection for Sustainable Agriculture*. IEEE INDIACom 2026, pp. 1-6. — Reason: not referenced in the final Classification table. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11526549)].
  
  5. Xiang, J., Ge, J., Fu, C., Huang, J., Lu, M., Zhang, Z., et al. (2026). *An environment-guided visual–temporal deep learning framework for early disease detection in greenhouse horticultural crops*. Frontiers in Plant Science, 17, 1796407. — Reason: duplicated three times in the original README (entries 8, 43, 46) and not present in the final Classification table under any citation key. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1796407/full)].
  
  6. Antony, A. J., & Murugan, R. (2026). *Transforming Agriculture with AI: Insights into Computer Vision Applications for Sustainable Farming*. IEEE IC-AIDA 2026, pp. 1-12. — Reason: broad opinion/insight paper, not a primary classification study. [[paper](https://ieeexplore.ieee.org/abstract/document/11564160)].
  
  7. Upadhyay, A., Chandel, N. S., Singh, K. P., Chakraborty, S. K., Nandede, B. M., Kumar, M., et al. (2025). *Deep learning and computer vision in plant disease detection: a comprehensive review of techniques, models, and trends in precision agriculture*. Artificial Intelligence Review, 58(3), 92. — Reason: survey/review article, not a primary study eligible for the table. [[paper](https://link.springer.com/article/10.1007/s10462-024-11100-x)].
  
  8. Swamy, L. N., Parande, P. V., Kumar, H. M., Rakshitha, V., Thimmaraju, S. N., & Yogesha, T. (2026). *Convolutional Neural Network Architectures for Enhanced Tomato Leaf Disease Classification using ResNet-152 and VGGNet Model*. Indian Journal of Agricultural Research, 60(1), 130-134. — Reason: not referenced in the final Classification table. [[paper](https://indianjournals.com/article/ijar2-60-1-019)].
  
  9. Jain, E., Kukreja, V., Kaushik, P., Ahuja, V., & Bansal, A. (2025). *Hybrid ViT-ResNet: A High-Accuracy AI Model for Automated Strawberry Ripeness Classification in Precision Agriculture*. Applied Fruit Science, 67(5), 368. — Reason: not referenced in the final table (distinct from the retained `Jain2025IoTDenseNet` entry). [[paper](https://link.springer.com/article/10.1007/s10341-025-01576-4)].
  
  10. Muthaiah, U., Reddy, Y. N., & Roy, R. V. (2026). *RESNET Based Crop Disease Detection Models Using Convolutional Neural Networks*. In Operations Research and Data Analytics (pp. 365-386). Springer Nature Singapore. — Reason: not referenced in the final Classification table. [[paper](https://link.springer.com/chapter/10.1007/978-981-96-8327-7_20)].
  
  11. Xue, X., Thakur, V., Dhumras, H., Jhaveri, R. H., & Gadekallu, T. R. (2025). *Real-Time Pest Detection Using ResNet-50 and Vision Transformer: An IoT-Enabled Mobile Application for Smart Agriculture*. IEEE Transactions on Consumer Electronics. — Reason: not referenced in the final Classification table. [[paper](https://ieeexplore.ieee.org/abstract/document/11127220)].
  
  12. Jain, S., & Rajpoot, R. (2025). *Real-Time Monitoring and Disease Detection in Greenhouses Using IoT and Deep Learning*. In Computational Intelligence Techniques for 5G Enabled IoT Networks (pp. 213-235). Springer. — Reason: duplicate entry (same reference kept once under `Jain2025IoTDenseNet` in the matched list). [[paper](https://link.springer.com/chapter/10.1007/978-3-031-82733-4_14)].
  
  13. Kavitha, K. (2025). *Deep Learning-Driven Computer Vision Techniques for Advancing Smart Greenhouse Agriculture*. IEEE ICSCN 2025, pp. 24-30. — Reason: duplicate entry (same reference kept once under (Kavitha et al, 2025) in the matched list). [[paper](https://ieeexplore.ieee.org/abstract/document/11308643)].
  
  14. Paymode, A. S., & Malode, V. B. (2022). *Transfer learning for multi-crop leaf disease image classification using convolutional neural network VGG*. Artificial Intelligence in Agriculture, 6, 23-33. — Reason: outside the review's 2024-onward search window; not referenced in the final table. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721721000416)].
  
  15. Ram, B. G., Howatt, K., Mettler, J., & Sun, X. (2025). *Addressing computation resource exhaustion associated with deep learning training of three-dimensional hyperspectral images using multiclass weed classification*. Artificial Intelligence in Agriculture, 15(2), 131-146. — Reason: duplicated three times in the original README (entries 44, 94, 97) and not referenced in the final Classification table. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000248)].
  
  16. Swapna, B., Kameswaran, S., & Ramakrishna, M. (2026). *Deep Learning in Plant Pest Control*. In Plant Genomic Prediction: AI-Enhanced Models for Plant Genomics and Crop Improvement (pp. 335-351). CABI. — Reason: book chapter overview, not a primary classification study. [[paper](https://www.cabidigitallibrary.org/doi/full/10.1079/9781836991328.0017)].
  
  17. Islam, M. S., Rahman, N., Mahmud, M. T., Naidu, A., Toha, M. A., Yasar, S., et al. (2026). *An Automated Approach for Classifying The Severity of Cucumber Diseases Using Deep Learning and Transfer Learning*. IEEE ICMI 2026, pp. 1-5. — Reason: not referenced in the final Classification table. [[paper](https://ieeexplore.ieee.org/abstract/document/11539878)].
  
  18. Sahu, S., & Verma, P. (2026). *UAV-based real-time detection of corn earworm using EfficientNet and machine learning*. Journal of Environmental Science and Health, Part B, 1-14. — Reason: open-field/UAV study, outside the review's greenhouse domain filter. [[paper](https://www.tandfonline.com/doi/full/10.1080/03601234.2026.2660035?scroll=top&needAccess=true)].
  
  19. Yang, Q., Lao, D., Wu, Y., Liu, C., Zhang, Z., Li, Z., et al. (2026). *Leaf thermal infrared imaging and lightweight deep learning enable early detection of water stress in watermelon for precision irrigation*. Agricultural Water Management, 329, 110344. — Reason: not referenced in the final Classification table. [[paper](https://www.sciencedirect.com/science/article/pii/S0378377426002258)].
  
  20. Nashrulloh, M. H., & Subarkah, A. (2025). *Fruit Image Classification Using CNN With EfficientNet Architecture for Visual Education*. Journal of Intelligent Systems Technology and Informatics, 1(2), 67-71. — Reason: educational-context study, not referenced in the final table. [[paper](https://journal.aptika.org/index.php/jistics/article/view/9)].
  
  21. Hasasneh, A., Ghannam, R., & Masri, S. (2025). *WeedNet-ViT: A Vision Transformer Approach for Robust Weed Classification in Smart Farming*. Geographies, 5(4), 64. — Reason: general open-field weed classification, not referenced in the final Classification table. [[paper](https://www.mdpi.com/2673-7086/5/4/64)].
  
  22. ÖZDEN, C. (2026). *Vision Transformer and CNN-Based Models for Image Analysis of Plant Diseases: An Approach for Agricultural Decision Support Systems*. ISPEC Journal of Agricultural Sciences. — Reason: not referenced in the final Classification table. [[paper](https://ispecjournal.com/index.php/ispecjas/article/view/915)].
  
  23. Lata, K., Kaur, N., & Singh, S. (2025). *Satellite-Based Crop Recognition Using Vision Transformer Models for Smart Agriculture*. Engineering Proceedings, 118(1), 34. — Reason: satellite/remote-sensing scope, outside the review's greenhouse robotics domain. [[paper](https://www.mdpi.com/2673-4591/118/1/34)].
  
  24. Cho, S. B., Choi, J. W., Hidayat, M. S., Cho, J. I., Lee, H., Cho, B. K., & Kim, G. (2025). *Development of a CNN classifier with XAI to detect interpretable water stress in sweet potato using RGB images*. Agricultural Water Management, 321, 109899. — Reason: not referenced in the final Classification table. [[paper](https://www.sciencedirect.com/science/article/pii/S0378377425006134)].
  
  25. Wu, Y., Dai, J., Zhu, Y., & Zhang, T. (2025). *Intelligent Agricultural Greenhouse Extraction Method Based on Multifeature Modeling: Fusion of Geometric, Spatial, and Spectral Characteristics*. IEEE JSTARS, 18, 5568-5581. — Reason: remote-sensing greenhouse-structure extraction, not a crop-level classification study. [[paper](https://ieeexplore.ieee.org/abstract/document/10858674)].
  
  26. Song, W., He, H., Dai, J., & Jia, G. (2025). *Extraction of agricultural plastic greenhouses based on a U-Net convolutional neural network coupled with edge expansion and loss function improvement*. Journal of the Air & Waste Management Association, 75(2), 109-120. — Reason: greenhouse-structure remote-sensing extraction, outside the crop-classification scope of the final table. [[paper](https://www.tandfonline.com/doi/full/10.1080/10962247.2024.2412708)].
  
  27. Das, A., Pathan, F., Jim, J. R., Kabir, M. M., & Mridha, M. F. (2025). *Deep learning-based classification, detection, and segmentation of tomato leaf diseases: A state-of-the-art review*. Artificial Intelligence in Agriculture, 15(2), 192-220. — Reason: survey/review article, not a primary study. [[paper](https://www.sciencedirect.com/science/article/pii/S258972172500025X)].
  
  28. Cheng, T., Zhang, D., Zhang, G., Wang, T., Ren, W., Yuan, F., et al. (2025). *High-throughput phenotyping techniques for forage: Status, bottleneck, and challenges*. Artificial Intelligence in Agriculture, 15(1), 98-115. — Reason: review article on forage phenotyping, outside the greenhouse-classification scope. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000029)].
  
  29. Gomez-Zamanillo, L., Bereciartua-Perez, A., Picon, A., Parra, L., Oldenbuerger, M., Navarra-Mestre, R., et al. (2025). *Digitalizing greenhouse trials: An automated approach for efficient and objective assessment of plant damage using deep learning*. Artificial Intelligence in Agriculture, 15(2), 280-295. — Reason: not referenced in the final Classification table. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000285)].
  
  30. Yang, Y., Chen, L., Diao, Z., Gao, P., Zhang, B., & Zhao, C. (2026). *Recent advances in crop pest detection, forecasting and early warning: A review*. Artificial Intelligence in Agriculture. — Reason: survey/review article, not a primary study. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000279)].
  
  31. Wiafe, E. K., Betitame, K., Ram, B. G., & Sun, X. (2025). *Technical study on the efficiency and models of weed control methods using unmanned ground vehicles: A review*. Artificial Intelligence in Agriculture, 15(4), 622-641. — Reason: review article on UGV weed control, outside the vision-classification scope of the final table. [[paper](https://www.sciencedirect.com/science/article/pii/S258972172500056X)].

 </details>

</details>
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ----------------------------------------------------------Detección -------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->

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

  1. Zhang, X., Zhang, G., Wang, J., Yang, J., Ge, Q., Zhao, R., & Yang, W. (2025). Efficient instance segmentation for strawberry in greenhouses using YOLOv8n-MCP on edge devices. Information Processing in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2214317325000344)].
  
  2. Weng, W., Lai, Z., Cui, Z., Chen, Z., Chen, H., Lin, T., Wang, J., Zheng, S., & Chen, G. (2025). GCD-YOLO: A deep learning network for accurate tomato fruit stalks identification in unstructured environments. Smart Agricultural Technology, 101465. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525006963)].
  
  3. Liu, X., Teng, W., Yu, H., Yao, Z., Wang, C., Peng, Y., Han, X., & Liu, J. (2025). GAE-YOLO: a lightweight multimodal detection framework for tomato smart agriculture with edge computing. Frontiers in Plant Science, 16, 1712432. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1712432/full)].
  
  4. Aranega, F. C., Border, R., Claraco, J. L. B., & Úbeda, J. C. M. (2025). NBV Planning for the detection of hidden tomatoes in greenhouses with AgriSEE. Jornadas de Automática, (46). [[paper](https://revistas.udc.es/index.php/JA_CEA/article/view/12234)].
  
  5. Kamat, P., Gite, S., Chandekar, H., Dlima, L., & Pradhan, B. (2025). Multi-class fruit ripeness detection using YOLO and SSD object detection models. Discover Applied Sciences, 7(9), 931. [[paper](https://link.springer.com/article/10.1007/s42452-025-07617-7)].
  
  6. Rezgui, J., & Ly, W. (2025). AI-based Plant Disease Detection: Development and Deployment of YOLO Models for Agricultural Innovation. IEEE ISNCC 2025, pp. 1-6. [[paper](https://ieeexplore.ieee.org/abstract/document/11250413)].
  
  7. Ruhad, F. M., Fahim, M., Hossain, M. S., Monir, M. F., Islam, A., & Amin, M. A. (2025). Beyond Classification: Benchmarking Object Detection Models for Efficient Tomato Leaf Disease Identification on a Real-World Dataset. Smart Agricultural Technology, 101336. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525005672)].
  
  8. Carbone, G., Gurtatta, A. S., & Malyshev, D. (2025). Development and implementation of a hybrid visual prediction algorithm for robotic smart tomato harvesting. Engineering Applications of Artificial Intelligence, 161, 112261. [[paper](https://www.sciencedirect.com/science/article/pii/S0952197625022699)].
  
  9. Amir, A., Giri, S., Giri, S., & Butt, M. (2025). An advanced approach to tomato apex head thickness measurement using lightweight YOLO variants, faster RCNN, and RGB-depth sensor. Smart Agricultural Technology, 101214. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525004459)].
  
  10. Tamrakar, N., Paudel, B., Karki, S., Deb, N. C., Arulmozhi, E., Kook, J. H., et al. (2025). Peduncle Detection of Ripe Strawberry to Localize Picking Point Using DF-Mask R-CNN and Monocular Depth. IEEE Access. [[paper](https://ieeexplore.ieee.org/abstract/document/10976681)].
  
  11. Wang, X., Burusa, A. K., Rapado-Rincón, D., Versmissen, T. A., van Henten, E. J., & Kootstra, G. (2025). Multiple object tracking with multi-view active vision to effectively find plant nodes in a cluttered tomato greenhouse. Computers and Electronics in Agriculture, 234, 110266. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925003722)].
  
  12. Gao, Y., Yin, F., Hong, C., Chen, X., Deng, H., Liu, Y., Li, Y., & Yao, Q. (2025). Intelligent field monitoring system for cruciferous vegetable pests using yellow sticky board images and an improved Cascade R-CNN. Journal of Integrative Agriculture, 24(1), 220-234. [[paper](https://www.sciencedirect.com/science/article/pii/S2095311924002405)].
  
  13. Rajagopal, S., & Venkatasubramaniam, K. (2025). Freshness Grading of Tomato Using Fast R-CNN. IEEE ICITIIT 2025, pp. 1-6. [[paper](https://ieeexplore.ieee.org/abstract/document/11041523)].
  
  14. Lyu, D. Y., Li, X. C., Wang, W. D., Wu, B. R., Shi, S. H., & Shen, H. Y. (2025). A melon fruit diameter measurement method based on an improved Mask R-CNN. INMATEH — Agricultural Engineering. [[paper](https://api.inmateh.eu/public/uploads/77-09-N1707-Deyang-LYUe919c8af-e304-45eb-aa86-023ae6e02762.pdf)].
  
  15. Montilla, J. C. A., Aniceto, M. J. C., & Caya, M. V. C. (2025). Eggplant Size Acquisition using Mask R-CNN. IEEE IICAIET 2025, pp. 210-214. [[paper](https://ieeexplore.ieee.org/abstract/document/11265158)].
  
  16. Grbović, Ž., Panić, M., Filipović, V., Brdar, S., De Villiers, H., Mensink, M., & Chauhan, A. (2025). An efficient encoding spectral information in hyperspectral images for transfer learning of Mask R-CNN for instance segmentation of tomato sepals. IEEE Access. [[paper](https://ieeexplore.ieee.org/abstract/document/11000115)].
  
  17. Sahu, K., Tiwari, S., Singh, M. K., Pahareeya, J., Shakya, H. K., Kumar, G., & Selvarajan, S. (2025). Plant disease detection using a hybrid dilated CNN with attention mechanisms and optimized mask RCNN segmentation. Scientific Reports. [[paper](https://www.nature.com/articles/s41598-025-26192-w)].
  
  18. Sapkota, R., Cheppally, R. H., Sharda, A., & Karkee, M. (2025). Rf-detr object detection vs yolov12: A study of transformer-based and cnn-based architectures for single-class and multi-class greenfruit detection in complex orchard environments under label ambiguity. arXiv preprint arXiv:2504.13099. [[paper](https://arxiv.org/abs/2504.13099)].
  
  19. Tang, Z., Fang, L., Sun, S., Gong, Y., & Li, Q. (2025). ML-DETR: Multiscale-Lite Detection Transformer for identification of mature cherry tomatoes. IEEE Transactions on Instrumentation and Measurement. [[paper](https://ieeexplore.ieee.org/abstract/document/11156100)].
  
  20. Rong, Z., Wang, G., Sun, Q., Sun, J., Li, R., Xu, Y., & Yang, L. (2025). A Lightweight and Efficient Model for Safety Protection Equipment Detection Based on Improved RT-DETR. IEEE Access, 14, 5510-5521. [[paper](https://ieeexplore.ieee.org/abstract/document/11230344)].
  
  21. Ren, W., Qian, T., Li, G., & Li, X. (2025). RT-DETR-MC: A Novel Fusion of Multi-Scale Features and Gating Mechanism for Lettuce Disease Detection. Proc. 2025 6th ICCIBDA, pp. 196-202. [[paper](https://dl.acm.org/doi/full/10.1145/3746709.3746745)].
  
  22. Tarasiuk, K., Mystkowski, A., Ostaszewski, M., Kwaśniewski, K. K., Majka, A., & Czarnigowski, J. (2026). Agriculture surrounding monitoring and object identification based on optimized you only look once and single shot multibox detector setups using combined vision and thermal images. Scientific Reports. [[paper](https://www.nature.com/articles/s41598-026-36181-2)].
  
  23. Ahmad, A., Lloret, J., Parra, L., Sendra, S., & Di Gioia, F. (2026). Comparative Analysis of R-CNN and YOLOv8 Segmentation Features for Tomato Ripening Stage Classification and Quality Estimation. Horticulturae, 12(2), 127. [[paper](https://www.mdpi.com/2311-7524/12/2/127)].
  
  24. Zhang, J., Guo, J., Zhao, C., Li, W., & Yuan, T. (2026). LeafRemoval-YOLO-K: A hybrid visual recognition network for stem-petiole segmentation and cutting point localization in tomato plants. Computers and Electronics in Agriculture, 246, 111485. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169926000803)].
  
  25. Ali, A. S., Narayan, J., Shukla, A., & Shree, R. (2026). Enhancing precision farming with YOLO models for real-time growth detection of basil plants. Environmental Sustainability, 1-11. [[paper](https://link.springer.com/article/10.1007/s42398-026-00454-3)].
  
  26. Jia, W., Lin, S., Wei, Z., Tian, B., Meng, X., & Zhang, Y. (2026). Research on Intelligent Identification Method for Nitrogen Content in Greenhouse Cucumber Leaves Integrating YOLOv11n Segmentation and Machine Learning. Agriculture, 16(13), 1376. [[paper](https://www.mdpi.com/2077-0472/16/13/1376)].
  
  27. Singh, R., Kaur, M., Alirezaee, S., & Hussain, I. (2026). YOLO26-RipeLoc Lite: A lightweight architecture for tomato ripeness detection and picking point localization in greenhouse robotic harvesting. arXiv preprint arXiv:2605.27129. [[paper](https://arxiv.org/abs/2605.27129)].
  
  28. Moni, M. A., Chaitee, A. S., Tanvir, K. M., Rahman, M. A., Banik, S., & Habib, M. T. (2026). Machine vision-based pepper breed classification Using yolov10 and transfer learning models. IEEE ICIPCN 2026, pp. 544-549. [[paper](https://ieeexplore.ieee.org/abstract/document/11438307)].
  
  29. Liu, Y., Wang, H., Wu, H., Xu, M., Yuan, G., Yan, R., & Zou, J. A Hybrid YOLO–EfficientNet Architecture for Multi-Task Recognition of Pests and Diseases in Greenhouse Crops. SSRN 5939218. [[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5939218)].
  
  30. Zhao, B., Zheng, D., Yang, C., Jomartova, S., Sonza, R., Mansurova, M., & Liu, H. (2026). DTBi-YOLOv8-seg: A dual-backbone deep learning framework for automated tomato ripeness detection in greenhouse environments. Scientia Horticulturae, 361, 114855. [[paper](https://www.sciencedirect.com/science/article/pii/S0304423826002487)].
  
  31. Kuang, M., Wang, Y., Li, X., Zou, X., Liu, D., Xiang, Y., Bader, S., Cie, F., Zhang, Y., & Li, X. (2026). GCP-YOLO: high-precision detection of tiny chili flowers in complex greenhouse scenes. Frontiers in Plant Science, 17, 1879612. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1879612/full)].
  
  32. Su, Y., Zhang, P., Li, H., Kang, F., Zhao, P., & Wang, L. (2026). YOLO-FLBM: a lightweight and high-performance model for tomato ripeness detection in complex greenhouse environments. Frontiers in Plant Science, 17, 1824558. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1824558/full)].
  
  33. Chen, M., Ma, K., Geng, X., Hu, D., Fei, S., He, S., Du, X., Shu, S., Zhang, R., & Ma, Y. (2026). MS-R outperforms RGB: Lightweight CYOLO-BiCNet enables efficient detection and storage optimization of cotton flowers. Precision Agriculture, 27(4), 92. [[paper](https://link.springer.com/article/10.1007/s11119-026-10396-9)].
  
  34. Gao, L., Li, Y., Wu, J., Feng, Q., Chen, L., Shen, C., et al. (2026). YOLO-GPP: End-to-end prediction of the grasp position and pose on tomato peduncle for robotic harvesting. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000206)].
  
  35. Li, X., Lin, Z., Liang, Z., Wang, G., & Zou, X. (2026). Research on tomato object all-day detection and occlusion scenario analysis methods. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000498)].
  
  36. Huang, L., Li, H., Yang, H., Fu, C., Zhang, Y., & Chang, F. (2026). Research on real-time target detection algorithm for strawberry-picking robot based on improved YOLOv5. Journal of Food Measurement and Characterization, 20(1), 847-868. [[paper](https://link.springer.com/article/10.1007/s11694-025-03703-x)].
  
  37. Xu, S. S. D., Wedajew, G. N., Ku, C. M., Chiu, C. C., & Yusuf, S. H. (2026). An Improved Sparse R-CNN Approach for Strawberry Disease Detection. Digital Signal Processing, 106212. [[paper](https://www.sciencedirect.com/science/article/pii/S1051200426003313)].
  
  38. Deepika, P., & Arthi, B. (2026). Enhancing the severity classification of tomato plant epidemic pathogens using adaptive segmentation of mask RCNN and multiscale recurrent MobileNet. Scientific Reports. [[paper](https://www.nature.com/articles/s41598-026-42675-w)].
  
  39. Fan, X. R., Cai, D., Wang, X., & Kang, M. (2026). SGS-DETR: A Lightweight Transformer for Real-Time Strawberry Growth Stage Detection in Smart Agriculture Systems. Smart Agricultural Technology, 102118. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526003382)].
  
  40. Kuang, M., Li, X., Wu, B., Liu, D., Xiang, Y., Liu, F., et al. (2026). CF-DETR: a robust transformer-based framework for small-scale chili flower detection in industrial chili production systems. Frontiers in Plant Science, 17, 1824412. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1824412/full)].
  
  41. Guo, J., Liu, Z., Zhang, X., Wang, R., Ma, X., & Li, W. (2026). SlimTom-DETR: A Lightweight and Real-Time Tomato Detection Model for Plant Factories With Complex Lighting Conditions. IEEE Access. [[paper](https://ieeexplore.ieee.org/abstract/document/11428165)].
  
  42. Karahan, F. E., Celikel, T., & Ozcan, G. (2026). An End-to-End Deep Learning Framework for Crop Type and Phenological Stage Identification. IEEE Access. [[paper](https://ieeexplore.ieee.org/abstract/document/11577148)].
  
  43. Xu, J., Zhang, X., Wang, X., Song, H., & Wang, Y. (2026). ELSF-DETR: an efficient lightweight network for detecting strawberry flowers pollination status in non-structured greenhouse environments. Computers and Electronics in Agriculture, 243, 111398. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925015042)].

</details>

<details>
  <summary><strong>3. Entries excluded based on PRISMA</strong></summary>
  
  1. Ghantasala, G. P., Dasari, S., Kumar, P. P., Suman, B., Kumar, A. R., Reddy, A., & Vidyullatha, P. (2026). Deep Learning Framework for Multi-Class Tomato Leaf Disease Detection from Segmented Images. Genetics and Molecular Research. — Reason: classification-oriented study, not referenced by any Detection citation key. [[paper](https://geneticsmr.com/index.php/gmr/article/view/1672)].
  
  2. Kavitha, K. (2025). Deep Learning-Driven Computer Vision Techniques for Advancing Smart Greenhouse Agriculture. IEEE ICSCN 2025, pp. 24-30. — Reason: already accounted for under the Classification scope; not referenced by a Detection citation key. [[paper](https://ieeexplore.ieee.org/abstract/document/11308643)].
  
  3. Donohoe, S. P., Alege, F. P., & Delhom, C. D. (2026). Toward multi-class detection and localization of contamination in cotton fields: Comparing EfficientDet, Faster R-CNN ResNet50, SSD MobileNet V2, and YOLOv11. Computers and Electronics in Agriculture, 247, 111690. — Reason: open-field cotton study, outside the review's greenhouse domain filter. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169926002851)].
  
  4. Xu, S. S. D., Wedajew, G. N., Ku, C. M., Chiu, C. C., & Yusuf, S. H. (2026). An Improved Sparse R-CNN Approach for Strawberry Disease Detection. Digital Signal Processing, 106212. — Reason: duplicate entry (same reference kept once under `Xu2026SparseRCNNStrawberry` in the matched list). [[paper](https://www.sciencedirect.com/science/article/pii/S1051200426003313)].
  
  5. Bashir, A., Wang, Y., Ojo, M. O., & Zahid, A. (2025). A Vision System for Occluded Cutting Point Localization in Robotic Harvesting of Greenhouse Lettuce. IEEE Transactions on AgriFood Electronics. — Reason: already accounted for under the Classification scope; not referenced by a Detection citation key. [[paper](https://ieeexplore.ieee.org/abstract/document/11219194)].
  
  6. Nan, Y., Zhang, H., Zheng, J., & Yang, K. (2025). Pitaya detection using an improved lightweight Faster R-CNN based on MobileNetV3 in densely planted pitaya orchards. Journal of Agricultural Engineering, 56(4). — Reason: open orchard cultivation, outside the greenhouse domain filter. [[paper](https://www.agroengineering.org/jae/article/view/1886)].
  
  7. Bilal, M., Shah, A. A., Abbas, S., & Khan, M. A. (2025). High-Performance Deep Learning for Instant Pest and Disease Detection in Precision Agriculture. Food Science & Nutrition, 13(9), e70963. — Reason: not referenced in the final Detection table. [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/fsn3.70963)].
  
  8. Alfred, R., Leo, J., & Kaijage, S. F. (2025). Detectron2-enhanced mask R-CNN for precise instance segmentation of rice blast disease in Tanzania: Supporting timely intervention and data-driven severity assessment. Smart Agricultural Technology, 101301. — Reason: open-field rice cultivation, outside the greenhouse domain filter. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525005325)].
  
  9. Daraghmi, Y. A., Naser, W., Daraghmi, E. Y., & Fouchal, H. (2025). Drone-Assisted Plant Stress Detection Using Deep Learning: A Comparative Study of YOLOv8, RetinaNet, and Faster R-CNN. AgriEngineering, 7(8), 257. — Reason: UAV/drone-based study, outside the greenhouse robotics domain. [[paper](https://www.mdpi.com/2624-7402/7/8/257)].
  
  10. Arik, K., & Ağgül, B. (2026). Reproducible Benchmarking of Tomato Detection in Greenhouse: Comparing Attention-Augmented and Baseline Detectors. AgriEngineering. — Reason: not referenced in the final Detection table. [[paper](https://www.researchgate.net/profile/Burak-Agguel/publication/408501666)].
  
  11. Restrepo-Arias, J. F., Montoya-Castaño, M. J., Moreno-De La Espriella, M. F., & Branch-Bedoya, J. W. (2025). An Application of Deep Learning Models for the Detection of Cocoa Pods at Different Ripening Stages: An Approach with Faster R-CNN and Mask R-CNN. Computation, 13(7), 159. — Reason: open-field cocoa cultivation, outside the greenhouse domain filter. [[paper](https://www.mdpi.com/2079-3197/13/7/159)].
  
  12. Cañadas-Aránega, F., Moreno, J. C., Blanco-Claraco, J. L., Giménez, A., Rodríguez, F., & Sánchez-Hermosilla, J. (2024). Autonomous collaborative mobile robot for greenhouses: Design, development, and validation tests. Smart Agricultural Technology, 9, 100606. — Reason: robotic-platform design paper, not a detection-algorithm study. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375524002119)].
  
  13. Zoubek, T., Bumbálek, R., Ufitikirezi, J. D. D. M., Strob, M., Filip, M., Špalek, F., Hermanek, A., & Bartoš, P. (2025). Advancing precision agriculture with computer vision: A comparative study of YOLO models for weed and crop recognition. Crop Protection, 190, 107076. — Reason: general open-field weed/crop recognition, not referenced in the final Detection table. [[paper](https://www.sciencedirect.com/science/article/pii/S0261219424005040)].
  
  14. Cañadas-Aránega, F., Muñoz, M., Moreno, J. C., & Blanco-Claraco, J. L. (2026). Integrated cloud-based architecture for robot-robot and human-robot collaboration using ROS 2-MQTT in Mediterranean Greenhouses. arXiv preprint arXiv:2606.22682. — Reason: robotics-infrastructure paper, not a detection-algorithm study. [[paper](https://arxiv.org/abs/2606.22682)].
  
  15. Cañadas-Aránega, F., Mañas-Álvarez, F. J., Moreno, J. C., & Blanco-Claraco, J. L. (2026). A ROS2 Benchmarking Framework for Hierarchical Control Strategies in Mobile Robots for Mediterranean Greenhouses. arXiv preprint arXiv:2602.15162. — Reason: robotics-benchmarking framework paper, not a detection-algorithm study. [[paper](https://arxiv.org/abs/2602.15162)].
  
  16. Singh, R., Gadade, A. M., & Hussain, I. (2025). Robust real-time strawberry maturity detection using UAV-mounted deep learning for precision agriculture. BMC Plant Biology, 25(1), 1367. — Reason: UAV-based study, outside the greenhouse robotics domain. [[paper](https://link.springer.com/article/10.1186/s12870-025-07246-7)].
  
  17. Yuan, M., Wang, D., Lin, J., Yang, S., & Ning, J. (2025). SSP-MambaNet: An automated system for detection and counting of missing seedlings in glass greenhouse-grown virus-free strawberry. Plant Phenomics, 7(2), 100043. — Reason: not referenced in the final Detection table. [[paper](https://www.sciencedirect.com/science/article/pii/S2643651525000494)].
  
  18. Ibrahim, E., Hamdy, M., El-Fishawy, A. S., A Eldolil, S., & El-Hoseny, H. (2025). Comprehensive survey on residual neural networks improvements in agricultural applications. Neural Computing and Applications, 1-42. — Reason: survey/review article, not a primary study. [[paper](https://link.springer.com/article/10.1007/s00521-025-11682-9)].
  
  19. Arif, T., Riaz, S., Shafiq, Z., & Khan, G. M. (2025). Computer Vision-Based Plant Growth Stages Analysis for Optimizing Crop Yield. IFIP AIAI 2025, pp. 283-296. — Reason: not referenced in the final Detection table. [[paper](https://link.springer.com/chapter/10.1007/978-3-031-97313-0_22)].
  
  20. Khan, Z., Liu, H., Shen, Y., Yang, Z., Zhang, L., & Yang, F. (2025). Optimizing precision agriculture: A real-time detection approach for grape vineyard unhealthy leaves using deep learning improved YOLOv7 with feature extraction capabilities. Computers and Electronics in Agriculture, 231, 109969. — Reason: open-field vineyard study, outside the greenhouse domain filter. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925000754)].
  
  21. Yilmaz, E., Bocekci, S. C., Safak, C., & Yildiz, K. (2025). Advancements in smart agriculture: A systematic literature review on state-of-the-art plant disease detection with computer vision. IET Computer Vision, 19(1), e70004. — Reason: systematic literature review, not a primary study. [[paper](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cvi2.70004)].
  
  22. Shuai, Y., Shi, J., Li, Y., Zhou, S., Zhang, L., & Mu, J. (2025). YOLO-SW: A Real-Time Weed Detection Model for Soybean Fields Using Swin Transformer and RT-DETR. Agronomy, 15(7), 1712. — Reason: open-field soybean weed detection, outside the greenhouse domain filter. [[paper](https://www.mdpi.com/2073-4395/15/7/1712)].
  
  23. Chen, Y., Liu, H., Wang, L., Chen, C., Li, S., Zhong, B., Qiao, J., Ye, R., & Li, T. (2025). Research on Instance Segmentation Algorithm for Caged Chickens in Infrared Images Based on Improved Mask R-CNN. Sensors, 25(19), 6237. — Reason: poultry-farming application, outside the greenhouse crop-robotics domain. [[paper](https://www.mdpi.com/1424-8220/25/19/6237)].
  
  24. Jiang, R., Guo, T., Liu, G., & Jia, W. (2026). GHD Net: Overlapping Green Tomato Instance Segmentation Under Facility Environments. IEEE Transactions on AgriFood Electronics. — Reason: not referenced in the final Detection table. [[paper](https://ieeexplore.ieee.org/abstract/document/11390666)].
  
  25. Sun, P., & Wu, W. (2026). Improved mask R-CNN-based instance segmentation model for coal gangue. International Journal of Coal Preparation and Utilization, 46(6), 1601-1619. — Reason: coal-processing application, unrelated to agricultural greenhouse robotics. [[paper](https://www.tandfonline.com/doi/full/10.1080/19392699.2025.2505448)].
  
  26. Gao, R., Cao, W., Zhang, Z., Cheng, X., Ji, Z., Kong, Q., & Su, Z. (2026). YOLOSc-SAM: An acceptable extraction method for farmland regions in remote sensing images using SAM. Artificial Intelligence in Agriculture. — Reason: remote-sensing farmland-region extraction, not a crop/object detection study. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000176)].
  
  27. Afzaal, H., Farooque, A. A., Randhawa, G. S., Schumann, A. W., Krouglicof, N., Gill, Y. S., & Zaman, Q. U. (2026). Zero-shot crop segmentation via 3D depth-aware vision pipeline using unsupervised clustering. Artificial Intelligence in Agriculture. — Reason: not referenced in the final Detection table. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000462)].

</details>
</details>
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------- Segmentation ------------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->

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

 <!-- ----------------- FCN -------------------- -->
  1. Gonzale, P., & Solarte, J. (2026). Semantic Segmentation Layer: A Nav2 Costmap Plugin for RGBD Semantic Segmentation. [[paper](https://github.com/kiwicampus/semantic_segmentation_layer)].
  
  2. Balaji, J. (2026). Efficient Groundfloor Segmentation for 3D Pointclouds. [[paper](https://github.com/open-edge-platform/edge-ai-suites/tree/main/robotics-ai-suites/components/groundfloor)].
  
  3. Cañadas-Aránega, F., Moreno, J. C., & Blanco-Claraco, J. L. (2026). GreenSeg: Ground Segmentation Algorithm for Agricultural Robots in Mediterranean Greenhouses using RGB-D Point Clouds. arXiv preprint arXiv:2605.25279. [[paper](https://arxiv.org/abs/2605.25279)].
  
  4. Zhang, K., Gao, R., Shen, A., Wang, Y., Pang, G., Yang, L., et al. (2026). NJ-Unet: A novel Unet-based greenhouse tomato leaf segmentation neural network and its application. Information Processing in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2214317326000077)].
  
  5. Jia, W., Wang, Z., Zhao, R., Ji, Z., Yin, X., & Liu, G. (2025). FBSM: Foveabox-based boundary-aware segmentation method for green apples in natural orchards. Expert Systems with Applications, 260, 125426. [[paper](https://www.sciencedirect.com/science/article/pii/S0957417424022930)].
  
  6. Chen, G., Luan, H., & Zhang, X. (2025). A Multi-Scale Attention U-Net for Extracting Agricultural Greenhouses from Very High Resolution Imagery. IEEE CVIDL 2025, pp. 01-06. [[paper](https://ieeexplore.ieee.org/abstract/document/11085484)].
  
  7. Bhavani, V., Pradeepini, G., & Kavya, K. C. S. (2026). An attention U-Net–enabled precision agriculture pipeline for turmeric disease detection and mapping. International Journal of System Assurance Engineering and Management, 1-16. [[paper](https://link.springer.com/article/10.1007/s13198-026-03168-1)].
  
  8. Dubey, P., & Dubey, P. (2026). ViT-U-Net fusion model for accurate localization and recognition of plant leaf diseases. Discover Artificial Intelligence, 6(1), 221. [[paper](https://link.springer.com/article/10.1007/s44163-026-01006-8)].
  
  9. Sivamurugan, J., Naveen, G., & Rajalakshmi, D. (2025). A Hybrid U-Net with Active Contours for Plant Leaf Disease Segmentation and Classification. IEEE ICEARS 2025, pp. 1799-1804. [[paper](https://ieeexplore.ieee.org/abstract/document/10940206)].
  
  10. Ghantasala, G. P., Dasari, S., Kumar, P. P., Suman, B., Kumar, A. R., Reddy, A., & Vidyullatha, P. (2026). Deep Learning Framework for Multi-Class Tomato Leaf Disease Detection from Segmented Images. Genetics and Molecular Research. [[paper](https://geneticsmr.com/index.php/gmr/article/view/1672)].
  
  11. Li, J., Guo, Z., Ye, L., & Lai, Z. (2025). Visual navigation path recognition method for tea plantation based on improved DeeplabV3+. Smart Agricultural Technology, 101555. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525007865)].
  
  12. Pisharody, S. N., Duraisamy, P., Rangarajan, A. K., Whetton, R. L., & Herrero-Langreo, A. (2025). Precise tomato ripeness estimation and yield prediction using transformer based segmentation-SegLoRA. Computers and Electronics in Agriculture, 233, 110172. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925002789)].
  
  13. Florea, C., Florea, L., & Ivanovici, M. (2025). Adaptive Select Loss Strategy for Semantic Segmentation of Agricultural Crop Images. IEEE JSTARS. [[paper](https://ieeexplore.ieee.org/abstract/document/11081431)].
  
  14. Han, Z., Qiao, C., Qin, Y., Chen, F., Li, Y., Zhang, L., & Zhang, Y. (2026). Quantitative characterization of lesion features and analysis of coupled stress effects of mixed infection by downy mildew and powdery mildew pathogens in cucumbers based on instance segmentation. Computers and Electronics in Agriculture, 242, 111286. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925013924)].
  
  15. Dong, M., Cao, H., Zhao, T., & Zhao, X. (2025). SegFormer-based nectar source segmentation in remote sensing imagery. Frontiers in Plant Science, 16, 1666619. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1666619/full)].
  
  16. Xiang, P., Pan, F., Liu, T., Zhao, X., Hu, M., He, D., & Zhang, B. (2025). MixSegNext: A CNN-Transformer hybrid model for semantic segmentation and picking point localization algorithm of Sichuan pepper in natural environments. Computers and Electronics in Agriculture, 237, 110564. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925006702)].
  
  17. Dorokhov, A., Smirnov, I., & Kutyrev, A. (2025). Autonomous Navigation of Robotic Platforms in Orchards: Semantic Segmentation and Path Planning. Int. Conf. on Agriculture Digitalization and Organic Production, pp. 1-13. Springer. [[paper](https://link.springer.com/chapter/10.1007/978-3-032-07171-2_1)].
  
  18. Cui, J., Zhang, L., Gao, L., Bai, C., & Yang, L. (2025). Cherry-Net: real-time segmentation algorithm of cherry maturity based on improved PIDNet. Frontiers in Plant Science, 16, 1607205. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1607205/full)].
  
  19. Wu, J., Rao, Y., Zeng, S., & Zhang, B. (2025). Pre-trained SAM as data augmentation for image segmentation. CAAI Transactions on Intelligence Technology, 10(1), 268-282. [[paper](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cit2.12381)].
  
  20. Huang, Z., Lee, W. S., Yang, P., Ampatzidis, Y., Shinsuke, A., & Peres, N. A. (2025). Advanced canopy size estimation in strawberry production: a machine learning approach using YOLOv11 and SAM. Computers and Electronics in Agriculture, 236, 110501. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925006076)].
  
  21. Qiu, X., Zhu, F., Huang, P., Chen, H., Li, Y., Pu, C., Li, Z., Zhong, D., Xoang, C., Chen, J., & Wang, S. (2025). Quantifying high-temperature-induced reproductive growth imbalance in citrus at anthesis: Insights from the CF-ASPM model. Computers and Electronics in Agriculture, 236, 110421. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925005277)].
  
  22. González-Muñoz, A., Wu, D. J., Perera-Rodríguez, A. B., Rekik, M., Giancola, S., Wulff, B. B., & Gardener, C. (2025). A high-throughput pipeline for phenotyping, object detection and quantification of leaf trichomes. Theoretical and Applied Genetics, 138(8), 188. [[paper](https://link.springer.com/article/10.1007/s00122-025-04967-z)].
  
  23. Oehme, L. H., Boysen, J., Wu, Z., Stein, A., & Müller, J. (2026). Orchestrating segment anything models to accelerate segmentation annotation on agricultural image datasets. Frontiers in Artificial Intelligence, 8, 1748468. [[paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC12872900/)].
  
  24. Liu, F., Hu, Y., Zhou, Q., & Zou, H. (2026). ReLeaf-SAM: reliability-guided detail compensation for SAM-based plant disease segmentation. Frontiers in Plant Science, 17, 1865649. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1865649/full)].
  
  25. Afzaal, H., Farooque, A. A., Randhawa, G. S., Schumann, A. W., Krouglicof, N., Gill, Y. S., & Zaman, Q. U. (2026). Zero-shot crop segmentation via 3D depth-aware vision pipeline using unsupervised clustering. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000462)].
  
  26. An, Q., He, X., Deng, X., Xing, G., Liu, Y., Zhou, H., et al. (2026). Rethinking spot spraying perception frameworks: A real-time segmentation approach integrating crop contours and the weed index. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000656)].
  
      
</details>

<details>
  <summary><strong>3. Entries excluded based on PRISMA</strong></summary>

1. Wang, J., & Sun, W. (2025). Cluster segmentation and stereo vision-based apple localization algorithm for robotic harvesting. Frontiers in Plant Science, 16, 1598414. — Reason: not referenced in the final Segmentation table. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1598414/full)].

2. Duhan, S., Gulia, P., Gill, N. S., & Gupta, C. (2026). A Comprehensive Review of Image Segmentation Techniques for Plant Disease Detection in Precision Agriculture: Models, Trends, and Challenges. Archives of Computational Methods in Engineering, 1-36. — Reason: survey/review article, not a primary study. [[paper](https://link.springer.com/article/10.1007/s11831-026-10582-y)].

3. Sahlaoui, H., & Agoujil, S. (2025). Optimizing Tomato Object Detection in Smart Agriculture with Attention-Augmented AI Vision Systems. IEEE ESAI 2025, pp. 1-8. — Reason: a detection-focused study, not referenced by any Segmentation citation key. [[paper](https://ieeexplore.ieee.org/abstract/document/11438635)].

4. Natho, P., Boonying, S., Bonguleaum, P., Tantidontanet, N., & Chamuthai, L. (2025). An enhanced machine vision system for smart poultry farms using deep learning. Smart Agricultural Technology, 12, 101083. — Reason: poultry-farming application, outside the greenhouse crop-robotics domain. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525003168)].

5. ZHU, Y., LIU, Z., WU, Z., LIU, Y., ZHANG, H., & SONG, R. (2025). Semantic segmentation model for agricultural greenhouses in high-resolution remote sensing images using an improved U-Net. Transactions of the Chinese Society of Agricultural Engineering, 41(21), 155-164. — Reason: remote-sensing greenhouse-structure extraction, not a crop segmentation study. [[paper](https://www.sciopen.com/article/10.11975/j.issn.1002-6819.202503132)].

6. Agrawal, K., & Kumar, N. (2025). Computer Vision in Agriculture: Object Detection, Recognition, and Image Segmentation Techniques and Advanced Image Analysis. Computational Intelligence and Image Processing in Agriculture, 31-54. — Reason: book-chapter overview, not a primary study. [[paper](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781394320905.ch03)].

7. Singh, G., Al-Huqail, A. A., Almogren, A., Kaur, S., Joshi, K., Singh, A., Bharany, S., Hussen, S., & Rehman, A. U. (2025). Enhanced Leaf Disease Segmentation Using U-Net Architecture for Precision Agriculture: A Deep Learning Approach. Food Science & Nutrition, 13(7), e70594. — Reason: not referenced in the final Segmentation table. [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/fsn3.70594)].

8. Beloualid, S., Bajit, A., Elfourchi, A., Zahid, Y., Semako, E., Essamri, H., & Sahl, S. (2025). Autonomous Mobile Node for Plant Imagery and Health Monitor in Agricultural Greenhouse. World Conf. on Information Systems for Business Management, pp. 161-171. Springer. — Reason: monitoring-system paper, not a segmentation-algorithm study. [[paper](https://link.springer.com/chapter/10.1007/978-3-032-13003-7_16)].

9. Li, Z., Karimzadeh, S., Chavanapanit, A., Moghimi, A., & Ahamed, M. S. (2025). Detection of calcium deficiency in indoor-grown lettuce under LED lighting using computer vision. Smart Agricultural Technology, 12, 101144. — Reason: not referenced in the final Segmentation table. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525003764)].

10. Narisetti, N., Neumann, K., Altmann, T., Stolzenburg, F., Von Wiren, N., Giehl, R. F., & Gladilin, E. (2026). A multi-class deep learning segmentation approach for automated analysis of axial and lateral roots in barley plants. Computers and Electronics in Agriculture, 240, 111157. — Reason: barley root-segmentation study, not referenced and outside the review's target crops. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925012633)].

11. Sunil, G. C., Paul, N., Khan, A., Hatterman-Valenti, H., Anderson, J. V., Kandel, J. S., Horvath, D., & Sun, X. (2025). Quantifying Freeze Damage in Strawberry Plants Using Deep Learning-Based Semantic Segmentation. Journal of Agriculture and Food Research, 102560. — Reason: not referenced in the final Segmentation table. [[paper](https://www.sciencedirect.com/science/article/pii/S2666154325009317)].

12. Stephen, V., Renjini, A., Nandu, B., Pratheep, G., & Hanumanthu, Y. (2025). Cotton leaf net: DeepLabv3+ powered semantic segmentation framework for precise cotton plant leaf disease detection in smart agriculture. ICATES 2025, pp. 111-117. — Reason: open-field cotton study, outside the greenhouse domain filter. [[paper](https://ieeexplore.ieee.org/abstract/document/11514402)].

13. Zhao, Y., Li, T., Wen, W., Lu, X., Yang, S., Fan, J., Guo, X., & Chen, L. (2025). YOMASK: An instance segmentation method for high-throughput phenotypic platform lettuce images. Computers and Electronics in Agriculture, 230, 109868. — Reason: not referenced in the final Segmentation table. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169924012596)].

14. Sun, T., Xiao, L., Ata-Ul-Karim, S. T., Ma, Y., & Zhang, W. (2025). Leveraging phenotyping and crop modeling in smart agriculture. Frontiers in Plant Science, 16, 1626622. — Reason: broad review article, not a primary study. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1626622/full)].

15. Pathan, R. K., Lim, W. L., Khandaker, M. U., Ho, C. C., & Lau, S. L. (2026). The evolution of deep learning models for instance segmentation: a critical review and analysis of future trajectories. International Journal of Multimedia Information Retrieval, 15(3), 21. — Reason: survey/review article, not a primary study. [[paper](https://link.springer.com/article/10.1007/s13735-026-00407-w)].

16. Xu, D., Wang, C., Li, M., Ge, X., Zhang, J., Wang, W., & Lv, C. (2025). Improving passion fruit yield estimation with multi-scale feature fusion and density-attention mechanisms in smart agriculture. Computers and Electronics in Agriculture, 239, 110958. — Reason: not referenced in the final Segmentation table. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925010646)].

17. Cao, L., Li, S., Jiang, D., Sun, M., & Liu, X. (2025). EGF-Former: An efficient network for structural segmentation and phenotype extraction of sweet peppers in complex environments. Industrial Crops and Products, 227, 120850. — Reason: not referenced in the final Segmentation table. [[paper](https://www.sciencedirect.com/science/article/pii/S0926669025003966)].

18. Ding, M., Peng, X., Ji, X., Chen, S., Li, Q., Zou, H., Fan, Z., & Wang, S. (2026). Leveraging generative adversarial networks and SE-UNet for high-precision tobacco leaf image segmentation and blend uniformity detection. Scientific Reports. — Reason: tobacco-leaf application, outside the review's target crops. [[paper](https://www.nature.com/articles/s41598-026-57964-7)].

19. Dong, L., Zhu, L., Zhao, B., Wang, R., Ni, J., Liu, S., Chen, K., Cui, X., & Zhou, L. (2025). Semantic segmentation-based observation pose estimation method for tomato harvesting robots. Computers and Electronics in Agriculture, 230, 109895. — Reason: pose-estimation study, not referenced by a Segmentation citation key. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925000018)].

20. Joy, J., Kelvin, B., Howatt, K., Aderholdt, W., Khan, M., Peters, T., & Sun, X. (2025). Edge-deployable Segmentation and Prescription Mapping of Post-emergence Weeds in Sugar Beet Crops for UAV-based Precision Spraying. Journal of Agriculture and Food Research, 102422. — Reason: UAV-based sugar-beet field study, outside the greenhouse domain filter. [[paper](https://www.sciencedirect.com/science/article/pii/S2666154325007938)].

21. Gyale, S., Singh, U., Tekavade, Y., & Jadhav, P. (2025). Transforming Precision Agriculture through Deep Learning: CNN Encoder-Decoders and a Hybrid YOLOv8-SAM Solution for Advanced Grape Cluster Segmentation. IEEE HSWTech 2025, pp. 1-6. — Reason: open-vineyard grape-cluster study, outside the greenhouse domain filter. [[paper](https://ieeexplore.ieee.org/abstract/document/11278142)].

22. Vashisht, A., Tekade, I., Shah, J., Sawarn, A., Yadav, D. S., Sontakke, P., & Patil, R. (2025). Effective Segmentation of Grape Leaves Using Segment Anything Model 2. Int. Conf. on Smart Trends for Information Technology, pp. 375-386. Springer. — Reason: grape-leaf study, not referenced in the final table. [[paper](https://link.springer.com/chapter/10.1007/978-981-96-7517-3_32)].

23. Owais, M., Shafay, M., Zubair, M., Mohammed, S., Seneviratne, L., & Hussain, I. (2025). AgriVision: A Benchmark Dataset for Advancing Real-World Robotic Vision in Densely Fruited Blueberry Crop. Scientific Data. — Reason: dataset paper (blueberry, open-field crop), not referenced by a Segmentation citation key. [[paper](https://www.nature.com/articles/s41597-025-06263-3)].

24. Gao, G., Fang, L., Zhang, Z., & Li, J. (2025). Advancing lightweight and efficient detection of tomato main stems for edge device deployment. Artificial Intelligence in Agriculture. — Reason: detection-focused study, not referenced by a Segmentation citation key. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000972)].

</details>



</details>

<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------- Generative ------------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->

<details>
<summary><strong>Generative</strong></summary>


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

<!-- ----------------- StyleGAN -------------------- -->

  1. Ullah, S., Narisetti, N., Neumann, K., Altmann, T., Hejatko, J., & Gladilin, E. (2025). Automated generation of ground truth images of greenhouse-grown plant shoots using a GAN approach. Plant Methods, 21(1), 126. [[paper](https://link.springer.com/article/10.1186/s13007-025-01441-1)].
  
  2. Huo, Y., Liu, Y., He, P., Hu, L., Gao, W., & Gu, L. (2025). Identifying Tomato Growth Stages in Protected Agriculture with StyleGAN3–Synthetic Images and Vision Transformer. Agriculture, 15(2), 120. [[paper](https://www.mdpi.com/2077-0472/15/2/120)].
  
  3. Dong, L., Zhu, L., Zhao, B., Wang, R., Ni, J., Liu, S., Chen, K., Cui, X., & Zhou, L. (2025). Semantic segmentation-based observation pose estimation method for tomato harvesting robots. Computers and Electronics in Agriculture, 230, 109895. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925000018)].
  
  4. Sun, T., Xiao, L., Ata-Ul-Karim, S. T., Ma, Y., & Zhang, W. (2025). Leveraging phenotyping and crop modeling in smart agriculture. Frontiers in Plant Science, 16, 1626622. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1626622/full)].
  
  5. Ullah, S., Narisetti, N., Neumann, K., Altmann, T., Hejatko, J., & Gladilin, E. (2025). Automated generation of ground truth images of greenhouse-grown plant shoots using a GAN approach. Plant Methods, 21(1), 126. [[aper](https://link.springer.com/article/10.1186/s13007-025-01441-1)]

  6. Furlanetto, R. H., Buzanini, A. C., Schumann, A. W., & Boyd, N. S. (2025). Enhancing Weed Detection in Strawberry Plasticulture: Evaluating Stable Diffusion Models for Synthetic Image Generation of Geranium carolinianum. Smart Agricultural Technology, 101773. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525010044)]
     
  7. Huo, Y., Liu, Y., He, P., Hu, L., Gao, W., & Gu, L. (2025). Identifying Tomato Growth Stages in Protected Agriculture with StyleGAN3–Synthetic Images and Vision Transformer. Agriculture, 15(2), 120. [[paper](https://iopscience.iop.org/article/10.1088/2631-8695/ae086a/meta)]


</details>

<details>
  <summary><strong>3. Entries excluded based on PRISMA</strong></summary>

1. Rajakannu, A., Vishnupriyan, S., & Abubacker, K. M. (2026). CNN-Assisted Growth Monitoring and Stress Management of Cucumber in Semi-Transparent PV Greenhouses for Agrivoltaics. — Reason: not referenced in the final Generation table. [[paper](https://www.sciencedirect.com/science/article/pii/S016816992500688X)].

2. Min, X., Ye, Y., Xiong, S., & Chen, X. (2025). Computer vision meets generative models in agriculture: Technological advances, challenges and opportunities. Applied Sciences, 15(14), 7663. — Reason: survey/review article, not a primary study. [[paper](https://www.mdpi.com/2076-3417/15/14/7663)].

3. Raju, R., & Thasleema, T. M. (2025). Advancements in automated plant disease detection: a comprehensive review of imaging technologies and deep learning applications. Journal of Crop Health, 77(6), 185. — Reason: survey/review article, not a primary study. [[paper](https://link.springer.com/article/10.1007/s10343-025-01247-0)].

4. Yang, H., Xu, P., Zhang, S., Kim, H., & Shin, I. (2025). Construction of an intelligent analysis system for crop health status based on drone remote sensing data and CNN. IEEE Access. — Reason: UAV/drone-based study, outside the greenhouse robotics domain. [[paper](https://ieeexplore.ieee.org/abstract/document/10878988)].

5. Awate, P., & Nagne, A. D. (2025). Case studies on generative adversarial networks in precision farming: Gan for precision agriculture. In Generative Adversarial Networks for Remote Sensing (pp. 291-320). IGI Global. — Reason: book-chapter overview, not a primary study. [[paper](https://www.igi-global.com/chapter/case-studies-on-generative-adversarial-networks-in-precision-farming/377878)].

6. Zangana, H. M., Li, S., & Wani, S. (2025). Diffusion Models for Agricultural Imaging: A Systematic Review of Methods, Applications and Future Prospects. Impact in Agriculture, 1(1). — Reason: systematic review, not a primary study. [[paper](https://www.impaxon.com/agriculture/1/3)].

7. Furlanetto, R. H., Buzanini, A. C., Schumann, A. W., & Boyd, N. S. (2025). Enhancing Weed Detection in Strawberry Plasticulture: Evaluating Stable Diffusion Models for Synthetic Image Generation of Geranium carolinianum. Smart Agricultural Technology, 101773. — Reason: weed-detection application, not referenced by any Generation citation key. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525010044)].

8. Li, L., Li, J., Chen, D., Pu, L., Yao, H., & Huang, Y. (2025). Vllfl: A vision-language model based lightweight federated learning framework for smart agriculture. arXiv preprint arXiv:2504.13365. — Reason: not referenced in the final Generation table. [[paper](https://arxiv.org/abs/2504.13365)].

9. Liu, S., Du, Z., Wang, G., Zhang, P., Xu, W., Yu, J., & Li, D. (2026). From Traditional Machine Learning Models to Multimodal Large Models: A Review of Aquaculture. Reviews in Aquaculture, 18(1), e70111. — Reason: aquaculture-domain review, unrelated to greenhouse robotics. [[paper](https://onlinelibrary.wiley.com/doi/full/10.1111/raq.70111)].

10. Duan, S., Feng, H., Tian, Y., Zhang, X., Tang, Y., Feng, G., & Zhang, P. (2026). Review of Vector Vortex Light Field Manipulation Technology Based on Metasurfaces. Journal of Electronic Materials, 55(2), 1354-1397. — Reason: unrelated optics/metasurfaces review, outside the agricultural robotics domain. [[paper](https://link.springer.com/article/10.1007/s11664-025-12577-0)].

11. Cao, Z., Sun, S., & Bao, X. (2025). A review of computer vision and deep learning applications in crop growth management. Applied Sciences, 15(15), 8438. — Reason: survey/review article, not a primary study. [[paper](https://www.mdpi.com/2076-3417/15/15/8438)].

12. Kumar, K., Revathi, A., Lavanya, D., & Sabeena, J. (2025). Transforming Agriculture: Utilizing Artificial Intelligence Methods to Quantify Crop Disease Levels. In AI Integration for Business Sustainability (pp. 163-177). Springer Nature Singapore. — Reason: book-chapter overview, not a primary study. [[paper](https://link.springer.com/chapter/10.1007/978-981-96-3464-4_9)].

</details>





</details>

<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ----------------------------------------------------------- LIDAR ---------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ---------------------------------------------------------- Algorim --------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->

## LiDAR algorithms for robotics
<div align="center">
  <img width="530" height="333" alt="image" src="https://github.com/user-attachments/assets/ed305d7f-17d5-4640-8c06-c4f566e52b6f" />
</div>

<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------- Clasification ------------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<details>
<summary><strong>Classification</strong></summary>
  
<details>
  <summary><strong>1. Articles on mathematical foundations</strong></summary>

  1. Qi, C. R., Su, H., Mo, K., & Guibas, L. J. (2017). Pointnet: Deep learning on point sets for 3d classification and segmentation. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 652-660). [[paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Qi_PointNet_Deep_Learning_CVPR_2017_paper.html)]

  2. Qi, C. R., Yi, L., Su, H., & Guibas, L. J. (2017). Pointnet++: Deep hierarchical feature learning on point sets in a metric space. Advances in neural information processing systems, 30. [[paper](https://proceedings.neurips.cc/paper/2017/hash/d8bf84be3800d12f74d8b05e9b89836f-Abstract.html)]

  3. Maturana, D., & Scherer, S. (2015, September). Voxnet: A 3d convolutional neural network for real-time object recognition. In 2015 IEEE/RSJ international conference on intelligent robots and systems (IROS) (pp. 922-928). Ieee. [[paper](https://ieeexplore.ieee.org/document/7353481)]

  4. Zhao, H., Jiang, L., Jia, J., Torr, P. H., & Koltun, V. (2021). Point transformer. In Proceedings of the IEEE/CVF international conference on computer vision (pp. 16259-16268). [[paper](https://openaccess.thecvf.com/content/ICCV2021/html/Zhao_Point_Transformer_ICCV_2021_paper.html?ref=;)]

  5. Ma, X., Qin, C., You, H., Ran, H., & Fu, Y. (2022). Rethinking network design and local geometry in point cloud: A simple residual MLP framework. arXiv preprint arXiv:2202.07123. [[paper](https://arxiv.org/abs/2202.07123)]

  6. Qian, G., Li, Y., Peng, H., Mai, J., Hammoud, H., Elhoseiny, M., & Ghanem, B. (2022). Pointnext: Revisiting pointnet++ with improved training and scaling strategies. Advances in neural information processing systems, 35, 23192-23204. [[paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/9318763d049edf9a1f2779b2a59911d3-Abstract-Conference.html)]

</details>
<details>
  <summary><strong>2. Articles on greenhouse farming</strong></summary>

  1. Yang, X., Xu, C., Wang, Y., Feng, R., Yu, J., Su, Z., et al. (2025). PlaneSegNet: A deep learning network with plane attention for plant point cloud segmentation in agricultural environments. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000947)].
  
  2. Yang, C., Sun, L., Zhang, J., Fan, X., Zhang, D., Ren, T., Liu, M., Zhang, Z., & Ma, W. (2025). Research on the quantification and automatic classification method of Chinese cabbage plant type based on point cloud data and PointNet++. Frontiers in Plant Science, 15, 1458962. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2024.1458962/full)].
  
  3. Zhang, H., Furuhashi, K., & Kaizu, Y. (2025). An Efficient and Low-Cost 3D Phenotyping Framework for Tomato Seedlings via Neural Radiance Fields and PointNet++. Smart Agricultural Technology, 101722. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525009530)].
  
  4. Ma, B., Xia, H., Ge, Y., Zhang, H., Wu, Z., Li, M., & Wang, D. (2025). A Method for Identifying Picking Points in Safflower Point Clouds Based on an Improved PointNet++ Network. Agronomy, 15(5), 1125. [[paper](https://www.mdpi.com/2073-4395/15/5/1125)].
  
  5. Cao, R., Jiang, Y., Suo, X., Du, M., Yang, G., Wang, W., Chen, Y., Gong, Y., He, Y., & Feng, X. AgriPointr: Point cloud completion with geometry-aware transformers for crops with complex structures. SSRN 6066357. [[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6066357)].
  
  6. Wang, P., Luo, W., Liu, J., Zhou, Y., Li, X., Zhao, S., Zhang, G., & Zhao, Y. (2025). Real-time semantic SLAM-based 3D reconstruction robot for greenhouse vegetables. Computers and Electronics in Agriculture, 237, 110582. [[paper](https://www.sciencedirect.com/science/article/pii/S016816992500688X)].
  
  7. Wei, Z., Long, J., Zhang, Z., Xue, X., Sun, Y., Li, Q., Liu, W., Shen, J., Zhang, Z., Li, X., & Ma, Z. (2025). Structure-aware completion of plant 3D LiDAR point clouds via a multi-resolution GAN-inversion network. Frontiers in Plant Science, 16, 1698843. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1698843/full)].
  
  8. Ma, S., Lu, X., & Zhang, L. (2025). TSINet: A Semantic and Instance Segmentation Network for 3D Tomato Plant Point Clouds. Applied Sciences, 15(15), 8406. [[paper](https://www.mdpi.com/2076-3417/15/15/8406)].
  
  9. Du, R., Zhai, G., Qiu, T., & Jiang, Y. (2025). Towards scalable organ level 3D plant segmentation: Bridging the data algorithm computing gap. arXiv preprint arXiv:2509.06329. [[paper](https://arxiv.org/abs/2509.06329)].
  
  10. Xu, J., Liu, H., & Shen, Y. (2025). Image and Point Cloud-Based Neural Network Models and Applications in Agricultural Nursery Plant Protection Tasks. Agronomy, 15(9), 2147. [[paper — ⚠️ original README link is a Google Scholar search query, not a direct article link; replace with the MDPI/DOI link before publishing]].
  
  11. Wang, F., Zhu, T., Huang, L., Feng, C., Lu, X., Min, W., et al. (2026). VGDS-PointNet++ for organ segmentation and phenotypic trait estimation in greenhouse tomato seedlings. Frontiers in Plant Science, 17, 1753706. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1753706/full)].
  
  12. Yang, X., Shang, Z., Huang, H., Liu, C., Xu, T., & Miao, T. (2026). SMFCA-Net: Sparse Multi-Frequency Cross-Attention Network for Single-Plant Point Cloud Classification and Segmentation. IEEE Transactions on Geoscience and Remote Sensing. [[paper](https://ieeexplore.ieee.org/abstract/document/11381999)].
  
  13. Zhao, W., Chen, Z., Liu, D., Yang, H., & Zhao, J. (2026). HTMNet: A Hybrid Transformer and Mamba Network for 3D Segmentation of Brassica rapa. IEEE AETCSE 2026, pp. 859-863. [[paper](https://ieeexplore.ieee.org/abstract/document/11504061)].
  
  14. Seo, B. H., Lee, S., Lee, J. H., Seo, Y., Kim, D., Jo, Y., Lee, J., & Choi, W. (2026). Semantic segmentation of plastic greenhouse frames and its application to finite element model reconstruction for structural response assessment. Computers and Electronics in Agriculture, 240, 111184. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925012906)].
  
  15. De Silva, R., Nazari, K., Moraru, I., Li, D., Sklar, E. I., Pearson, S., & Coutts, S. (2026). AgSentry: LiDAR reflectivity based obstacle detection for safety in agricultural environments. Smart Agricultural Technology, 102014. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526002376)].


  </details>

<details>
  <summary><strong>3. Entries excluded based on PRISMA</strong></summary>

  1. Yao, J., Wang, W., Fu, H., Deng, Z., Cui, G., Wang, S., Wang, D., Wei, S., & Cao, X. (2025). Automated measurement of field crop phenotypic traits using UAV 3D point clouds and an improved PointNet++. Frontiers in Plant Science, 16, 1654232. — Reason: UAV/open-field phenotyping study, outside the review's greenhouse robotics domain. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1654232/full)].
  
  2. Fatima, Z., Zardari, S., & Tanveer, M. H. (2025). Bridging domain gaps in agricultural 3D point cloud classification using adversarial domain adaptation. Scientific Reports, 15(1), 41995. — Reason: duplicated twice in the original README (entries 3 and 22) and not referenced in the final Classification table. [[paper](https://www.nature.com/articles/s41598-025-26225-4)].
  
  3. Zhou, L., Xu, Y., Zhang, C., Zhang, X., Wu, Q., Bian, L., Elsherbiny, O., & Zhang, H. (2026). From pixels to points: An AI framework with weaker-and-fewer-labels for lightweight 3D phenotyping using 2D-3D coordinate mapping and VLMs. Artificial Intelligence in Agriculture. — Reason: not referenced in the final Classification table. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000139)].
  
  4. Tan, H., Wang, Z., Fu, H., Zhao, X., Zhang, Y., Yang, M., & Zhai, C. (2026). Precision pesticide application in greenhouse asparagus: A semantic segmentation approach for canopy-adapted variable-rate spraying. Smart Agricultural Technology, 102297. — Reason: spraying-application study, not referenced by any Classification citation key. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526005228)].
  
  5. Davarakis, D. T., Ren, Y., & Argyropoulos, D. (2025). Recent Developments of Machine Learning Combined 3D Reconstruction in Agricultural and Food Sectors. IEEE EEITE 2025, pp. 1-10. — Reason: survey/overview paper, not a primary study. [[paper](https://ieeexplore.ieee.org/abstract/document/11166193)].
  
  6. Jiang, Y., Liu, Q., Lu, W., Zhou, B., Smoleňová, K., Tekinerdogan, B., & Yang, Q. (2025). Plant stem occlusion inpainting with deep reinforcement learning. Computers and Electronics in Agriculture, 237, 110465. — Reason: not referenced in the final Classification table. [[paper](https://www.sciencedirect.com/science/article/pii/S016816992500571X)].
  
  7. Yang, Y., Wijewardane, N. K., Slonecki, T. J., Wadl, P. A., Andreason, S. A., Chen, J., & Harvey, L. (2025). Nondestructive detection of sweet potato leaf curl virus using 3D laser imaging combined with deep learning. Smart Agricultural Technology, 11, 101004. — Reason: not referenced in the final Classification table. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525002370)].
  
  8. Zhang, Q., Zhenxiang, W., Wu, W., Lizhang, X., Zhenghui, Z., & Shaowei, L. (2026). A Review of Crop Attribute Detection for Agricultural Harvesting Machinery. Agronomy, 16(10), 973. — Reason: survey/review article, not a primary study. [[paper](https://www.proquest.com/docview/3345751240)].
  
  9. Zhang, L., Huang, Z., Yang, Z., Yang, B., Yu, S., Zhao, S., Zhang, X., Li, X., Yang, H., Lin, Y., & Yu, H. (2025). Tomato stem and leaf segmentation and phenotype parameter extraction based on improved red billed blue magpie optimization algorithm. Agriculture, 15(2), 180. — Reason: not referenced in the final Classification table. [[paper](https://www.mdpi.com/2077-0472/15/2/180)].
  
  10. Gao, X., Gao, J., & Qureshi, W. A. (2025). Applications, trends, and challenges of precision weed control technologies based on deep learning and machine vision. Agronomy, 15(8), 1954. — Reason: survey/review article on weed-control technology. [[paper](https://www.mdpi.com/2073-4395/15/8/1954)].
  
  11. Tai, H., Rao, C., Li, X., Li, H., & Li, C. (2025). Extracting rubber tree parameters and estimating carbon storage using airborne LiDAR. PLoS One, 20(8), e0330768. — Reason: outdoor/airborne forestry application, outside the greenhouse robotics domain. [[paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0330768)].
  
  12. Wang, Q., Chen, Y., Li, J., Chen, Y., & Wang, H. (2026). 3D semantic map reconstruction for orchard environments using multi-sensor fusion. Agriculture, 16(4), 455. — Reason: orchard/open-field environment, outside the review's greenhouse domain filter. [[paper](https://www.mdpi.com/2077-0472/16/4/455)].
  
  13. Wang, T., Tong, R., Xu, T., Li, Y., & Chen, Y. (2025). Artificial intelligence in plant science: from image-based phenotyping to yield and trait prediction. Frontiers in Plant Science, 16, 1732979. — Reason: broad survey/review article, not a primary study. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1732979/full)].
  
  14. Pourdelan, H., Xiang, Z., Stewart, H., Nicholson, C., Tomko, M., & Khoshelham, K. (2026). Direct Estimation of Tree Volume and Aboveground Biomass Using Deep Regression with Synthetic Lidar Data. arXiv preprint arXiv:2603.04683. — Reason: forestry/outdoor biomass-estimation study, outside the greenhouse robotics domain. [[paper](https://arxiv.org/abs/2603.04683)].
  
  15. Zhu, Q., & Yu, M. (2025). A Corn Point Cloud Stem-Leaf Segmentation Method Based on Octree Voxelization and Region Growing. Agronomy, 15(3), 740. — Reason: not referenced in the final Classification table. [[paper](https://www.mdpi.com/2073-4395/15/3/740)].
  
  16. Saki, M., Keshavarz, R., Franklin, D., Abolhasan, M., Lipman, J., & Shariati, N. (2025). A Data-Driven review of remote Sensing-Based data fusion in precision agriculture from foundational to Transformer-Based techniques. IEEE Access. — Reason: survey/review article. [[paper](https://ieeexplore.ieee.org/abstract/document/11165307)].
  
  17. Manoj, M., Balaji, E., Lokesh, A., Bharathi, V., Devi, T. N., Manikandan, R., et al. (2026). Deep Learning for Real-Time Plant Monitoring Systems. In Deep Learning in Plant Science and Agricultural Biotechnology (pp. 239-269). CABI. — Reason: book-chapter overview, not referenced in the final Classification table. [[paper](https://www.cabidigitallibrary.org/doi/full/10.1079/9781836991120.0013)].
  
  18. Gao, Y., Zhu, B., & Song, K. (2026). An Overview of Remote Sensing of Agricultural Greenhouses: Advances and Perspectives. Chinese Geographical Science, 36(2), 171-190. — Reason: remote-sensing overview article, not a primary classification study. [[paper](https://link.springer.com/article/10.1007/s11769-026-1607-9)].
  
  19. Li, Z., Wang, R., & Ding, R. (2025). A review of crop attribute monitoring technologies for general agricultural scenarios. AgriEngineering, 7(11), 365. — Reason: survey/review article. [[paper](https://www.mdpi.com/2624-7402/7/11/365)].
  
  20. Qiao, G., Zhang, Z., Niu, B., Han, S., & Yang, E. (2025). Segmentation and phenotypic parameter extraction using PointNeXt. In Advanced Methods, Equipment and Platforms in Precision Field Crops Protection, Vol. II. — Reason: not referenced in the final Classification table. [[paper](https://books.google.es/books?hl=es&lr=&id=yAGVEQAAQBAJ&oi=fnd&pg=PA146&dq=Pointnext+CNN+LiDAR+greenhouse+agriculture&ots=sdBkOEL2EB&sig=XnBYGZ8VDXe-RL092tAZSFc0E6U)].
  
  21. Chu, P., Han, B., Guo, Q., Wan, Y., & Zhang, J. (2025). A three-dimensional phenotype extraction method based on point cloud segmentation for all-period cotton multiple organs. Plants, 14(11), 1578. — Reason: not referenced in the final Classification table. [[paper](https://www.mdpi.com/2223-7747/14/11/1578)].
  
  22. Sánchez-Molina, J. A., Rodríguez, F., Moreno, J. C., Sánchez-Hermosilla, J., & Giménez, A. (2024). Robotics in greenhouses. Scoping review. Computers and Electronics in Agriculture, 219, 108750. — Reason: scoping-review article, not a primary study. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169924001418)].
  
  23. Xu, J., Gu, B., & Tian, G. (2022). Review of agricultural IoT technology. Artificial Intelligence in Agriculture, 6, 10-22. — Reason: review article and outside the review's 2024-onward search window. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721722000010)].
  
  24. Zhong, B., Yang, L., Lu, J., & Xu, S. (2026). 3D Point Cloud Segmentation Algorithm Based on Deep Learning and Its Application in Phenotype Detection. IET Image Processing, 20(1), e70405. — Reason: not referenced in the final Classification table. [[paper](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ipr2.70405)].

</details>


  
</details>

<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------- Detection ------------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->

<details>
<summary><strong>Objetc detection</strong></summary>
  
<details>
  <summary><strong>1. Articles on mathematical foundations</strong></summary>

  1. Yan, Y., Mao, Y., & Li, B. (2018). Second: Sparsely embedded convolutional detection. Sensors, 18(10), 3337. [[paper](https://www.mdpi.com/1424-8220/18/10/3337)]

  2. Shi, S., Wang, X., & Li, H. (2019). Pointrcnn: 3d object proposal generation and detection from point cloud. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 770-779). [[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_PointRCNN_3D_Object_Proposal_Generation_and_Detection_From_Point_Cloud_CVPR_2019_paper.pdf)]

  3. Lang, A. H., Vora, S., Caesar, H., Zhou, L., Yang, J., & Beijbom, O. (2019). Pointpillars: Fast encoders for object detection from point clouds. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 12697-12705). [[paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Lang_PointPillars_Fast_Encoders_for_Object_Detection_From_Point_Clouds_CVPR_2019_paper.html)]

  4. Shi, S., Guo, C., Jiang, L., Wang, Z., Shi, J., Wang, X., & Li, H. (2020). Pv-rcnn: Point-voxel feature set abstraction for 3d object detection. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 10529-10538). [[paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Shi_PV-RCNN_Point-Voxel_Feature_Set_Abstraction_for_3D_Object_Detection_CVPR_2020_paper.html)]

  5. Yin, T., Zhou, X., & Krahenbuhl, P. (2021). Center-based 3d object detection and tracking. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 11784-11793). [[paper](https://openaccess.thecvf.com/content/CVPR2021/html/Yin_Center-Based_3D_Object_Detection_and_Tracking_CVPR_2021_paper.html)]

  6. Wang, Y., Guizilini, V. C., Zhang, T., Wang, Y., Zhao, H., & Solomon, J. (2022, January). Detr3d: 3d object detection from multi-view images via 3d-to-2d queries. In Conference on robot learning (pp. 180-191). PMLR. [[paper](https://proceedings.mlr.press/v164/wang22b.html?ref=https://githubhelp.com)]

</details>

<details>
  <summary><strong>2. Articles on greenhouse farming</strong></summary>

 <!-- ----------------- SECOND -------------------- -->

  1. Huang, Z., Yang, N., Cao, R., Li, Z., He, Y., & Feng, X. (2025). Autonomous navigation system in various greenhouse scenarios based on improved FAST-LIO2. Computers and Electronics in Agriculture, 234, 110279. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925003850)]

  2. Tan, H., Zhao, X., Fu, H., Yang, M., & Zhai, C. (2025). A novel fusion positioning navigation system for greenhouse strawberry spraying robot using LiDAR and ultrasonic tags. Agriculture Communications, 3(2), 100087. [[paper](https://www.sciencedirect.com/science/article/pii/S2949798125000171)]

 <!-- ----------------- POINTRCNN -------------------- -->

  3. Ma, H., Wen, W., Gou, W., Lu, X., Fan, J., Zhang, M., Liang, Y., Gu, S., & Guo, X. (2025). 3D time-series phenotyping of lettuce in greenhouses. Biosystems Engineering, 250, 250-269. [[paper](https://www.sciencedirect.com/science/article/pii/S1537511025000042)]

 <!-- ----------------- PointPillars -------------------- -->

 <!-- ----------------- PV-RCNN -------------------- -->

  4. Werner, H., Delea, C., Zantopp, N., Au, C. N., & Tiedemann, T. (2025, October). Advancing Maritime Perception: PV-RCNN for 3D LiDAR Object Detection. In Journal of Physics: Conference Series (Vol. 3123, No. 1, p. 012026). IOP Publishing. [[paper](https://iopscience.iop.org/article/10.1088/1742-6596/3123/1/012026/meta)]

  5. Jang, S. H., Cho, H. R., Hong, H. G., Kwon, T. H., Cho, Y. J., Yun, H. Y., Lee, Y.J., Ahn, W.J., & Lim, M. T. (2026). FruitTrackDB: a multi-sensor dataset for intelligent navigation in real orchard environments. Intelligent Service Robotics, 19(3), 50. [[paper](https://link.springer.com/article/10.1007/s11370-026-00702-9)]

 <!-- ----------------- CenterPoint -------------------- -->

  6. Fang, W., Bi, C., Zhou, J., Yu, H., & Zhao, M. (2025). 3D LiDAR-based crop row detection for soybean at maturity under different planting densities. Computers and Electronics in Agriculture, 239, 111046. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925011524)]

 <!-- ----------------- DETR3D -------------------- -->

  7. Zhang, D., Gajardo, J., Medic, T., Katircioglu, I., Boss, M., Kirchgessner, N., Walter, A., & Roth, L. (2025). Wheat3dgs: In-field 3d reconstruction, instance segmentation and phenotyping of wheat heads with gaussian splatting. In Proceedings of the Computer Vision and Pattern Recognition Conference (pp. 5360-5370). [[paper](https://openaccess.thecvf.com/content/CVPR2025W/V4A/html/Zhang_Wheat3DGS_In-field_3D_Reconstruction_Instance_Segmentation_and_Phenotyping_of_Wheat_CVPRW_2025_paper.html)]

</details>

<details>
  <summary><strong>3. Entries excluded based on PRISMA</strong></summary>

  1. Khan, Z., Shen, Y., & Liu, H. (2025). Object detection in agriculture: A comprehensive review of methods, applications, challenges, and future directions. Agriculture, 15(13), 1351. — Reason: survey/review article, not a primary study. [[paper](https://www.mdpi.com/2077-0472/15/13/1351)].
  
  2. Huang, Z., Yang, N., Cao, R., Li, Z., He, Y., & Feng, X. (2025). Autonomous navigation system in various greenhouse scenarios based on improved FAST-LIO2. Computers and Electronics in Agriculture, 234, 110279. — Reason: SLAM-based navigation-system paper, not referenced by a Detection citation key. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925003850)].
  
  3. Tan, H., Zhao, X., Fu, H., Yang, M., & Zhai, C. (2025). A novel fusion positioning navigation system for greenhouse strawberry spraying robot using LiDAR and ultrasonic tags. Agriculture Communications, 3(2), 100087. — Reason: positioning/navigation-system paper, not a detection-algorithm study. [[paper](https://www.sciencedirect.com/science/article/pii/S2949798125000171)].
  
  4. Ma, H., Wen, W., Gou, W., Lu, X., Fan, J., Zhang, M., Liang, Y., Gu, S., & Guo, X. (2025). 3D time-series phenotyping of lettuce in greenhouses. Biosystems Engineering, 250, 250-269. — Reason: phenotyping study, not referenced by a Detection citation key. [[paper](https://www.sciencedirect.com/science/article/pii/S1537511025000042)].
  
  5. Zhao, H., Chen, S., Yang, S., Tang, H., Xu, Z., Zheng, Y., & Kang, F. (2026). Point-cloud segmentation for overlapping fruit-tree canopies using LiDAR to improve individual-tree data quality in precision orchards. IEEE JSTARS. — Reason: open orchard environment, outside the greenhouse domain filter. [[paper](https://ieeexplore.ieee.org/abstract/document/11399749)].
  
  6. Lin, F., Liu, Z., Meng, T., Lu, L., Xue, Q., & Ren, K. (2026). Physical Adversarial Example Attacks towards LiDAR Perception via Electromagnetic Injection. IEEE Transactions on Mobile Computing. — Reason: LiDAR-security/adversarial-attack study, unrelated to crop detection. [[paper](https://ieeexplore.ieee.org/abstract/document/11603440)].
  
  7. Tu, J., Ren, D., Shi, F., Jia, Z., Ren, Y., Qin, J., & He, F. (2025). Minkowski-MambaNet: A Point Cloud Framework with Selective State Space Models for Forest Biomass Quantification. arXiv preprint arXiv:2510.09367. — Reason: forestry-biomass application, outside the greenhouse robotics domain. [[paper](https://arxiv.org/abs/2510.09367)].
  
  8. Guaragnella, G., Cardellicchio, A., Patruno, C., Nitti, M., Pedrocchi, N., & Renò, V. (2026). Artificial Intelligence in Autonomous Mobile Robot Navigation: From Classical Approaches to Intelligent Adaptation. Advanced Intelligent Systems, 8(5), e202501376. — Reason: broad robot-navigation survey, not a primary study. [[paper](https://advanced.onlinelibrary.wiley.com/doi/full/10.1002/aisy.202501376)].
  
  9. Valverde, M., Moutinho, A., & Zacchi, J. V. (2025). A Survey of Deep Learning-Based 3D Object Detection Methods for Autonomous Driving Across Different Sensor Modalities. Sensors, 25(17), 5264. — Reason: autonomous-driving survey, not agriculture-related. [[paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC12431044/)].
  
  10. Werner, H., Delea, C., Zantopp, N., Au, C. N., & Tiedemann, T. (2025). Advancing Maritime Perception: PV-RCNN for 3D LiDAR Object Detection. Journal of Physics: Conference Series, Vol. 3123, No. 1, 012026. — Reason: maritime-domain application, unrelated to agricultural greenhouse robotics. [[paper](https://iopscience.iop.org/article/10.1088/1742-6596/3123/1/012026/meta)].
  
  11. Lielamurs, E., Sayed, I., Cvetkovs, A., Novickis, R., Zencovs, A., Celitans, M., Bizums, A., Dimitrakopoulos, G., Kaszzescha, J., & Ozols, K. (2025). A distributed time-of-flight sensor system for autonomous vehicles: architecture, sensor fusion, and spiking neural network perception. Electronics, 14(7), 1375. — Reason: autonomous-vehicle sensor system, unrelated to agricultural greenhouse robotics. [[paper](https://www.mdpi.com/2079-9292/14/7/1375)].
  
  12. Xie, P., Fang, L., He, Y., & Cen, H. (2025). Temporal semantic multispectral point cloud generation and feature fusion pipeline for comprehensive trait estimation in greenhouse tomatoes. Computers and Electronics in Agriculture, 237, 110748. — Reason: trait-estimation/generation-scope pipeline, not referenced by a Detection citation key. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925008543)].
  
  13. Fang, W., Bi, C., Zhou, J., Yu, H., & Zhao, M. (2025). 3D LiDAR-based crop row detection for soybean at maturity under different planting densities. Computers and Electronics in Agriculture, 239, 111046. — Reason: open-field soybean row detection, outside the greenhouse domain filter. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925011524)].
  
  14. Zhang, D., Gajardo, J., Medic, T., Katircioglu, I., Boss, M., Kirchgessner, N., Walter, A., & Roth, L. (2025). Wheat3dgs: In-field 3D reconstruction, instance segmentation and phenotyping of wheat heads with gaussian splatting. Proc. CVPR 2025 Workshops, pp. 5360-5370. — Reason: open-field wheat phenotyping via Gaussian splatting, not referenced by a Detection citation key. [[paper](https://openaccess.thecvf.com/content/CVPR2025W/V4A/html/Zhang_Wheat3DGS_In-field_3D_Reconstruction_Instance_Segmentation_and_Phenotyping_of_Wheat_CVPRW_2025_paper.html)].
  
  15. González-Muñoz, A., Wu, D. J., Perera-Rodríguez, A. B., Rekik, M., Giancola, S., Wulff, B. B., & Gardener, C. (2025). A high-throughput pipeline for phenotyping, object detection and quantification of leaf trichomes. Theoretical and Applied Genetics, 138(8), 188. — Reason: leaf-trichome phenotyping, not referenced by a Detection citation key. [[paper](https://link.springer.com/article/10.1007/s00122-025-04967-z)].

</details>

</details>

<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------- Segmentaction ------------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->

<details>
<summary><strong>Segmentation</strong></summary>
  
<details>
  <summary><strong>1. Articles on mathematical foundations</strong></summary>

  1. Vitagliano, G., Gühne, O., & Tóth, G. (2025). "SqueezeSeg" and many-body entanglement geometry in finite-dimensional systems. Quantum, 9, 1844. [[paper](https://quantum-journal.org/papers/q-2025-09-03-1844/)]

  2. Cheng, B., Chen, L. C., Wei, Y., Zhu, Y., Huang, Z., Xiong, J., Huang, T.S., Hwu, W.H. & Shi, H. (2019). Spgnet: Semantic prediction guidance for scene parsing. In Proceedings of the IEEE/CVF international conference on computer vision (pp. 5218-5228). [[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Cheng_SPGNet_Semantic_Prediction_Guidance_for_Scene_Parsing_ICCV_2019_paper.pdf)]

  3. Thomas, H., Qi, C. R., Deschaud, J. E., Marcotegui, B., Goulette, F., & Guibas, L. J. (2019). Kpconv: Flexible and deformable convolution for point clouds. In Proceedings of the IEEE/CVF international conference on computer vision (pp. 6411-6420). [[paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Thomas_KPConv_Flexible_and_Deformable_Convolution_for_Point_Clouds_ICCV_2019_paper.html)]

  4. Hu, Q., Yang, B., Xie, L., Rosa, S., Guo, Y., Wang, Z., Trigon, N., & Markham, A. (2020). Randla-net: Efficient semantic segmentation of large-scale point clouds. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 11108-11117). [[paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Hu_RandLA-Net_Efficient_Semantic_Segmentation_of_Large-Scale_Point_Clouds_CVPR_2020_paper.html)]

  5. Zhou, H., Zhu, X., Song, X., Ma, Y., Wang, Z., Li, H., & Lin, D. (2020). Cylinder3d: An effective 3d framework for driving-scene lidar semantic segmentation. arXiv preprint arXiv:2008.01550. [[paper](https://arxiv.org/abs/2008.01550)]

  6. Cortinhal, T., Tzelepis, G., & Erdal Aksoy, E. (2020, October). Salsanext: Fast, uncertainty-aware semantic segmentation of lidar point clouds. In International Symposium on Visual Computing (pp. 207-222). Cham: Springer International Publishing. [[paper](https://link.springer.com/chapter/10.1007/978-3-030-64559-5_16)]

  7. Wang, Y., Sun, Y., Liu, Z., Sarma, S. E., Bronstein, M. M., & Solomon, J. M. (2019). Dynamic graph cnn for learning on point clouds. ACM Transactions on Graphics (tog), 38(5), 1-12. [[paper](https://dl.acm.org/doi/abs/10.1145/3326362)]

</details>

<details>
  <summary><strong>2. Articles on greenhouse farming</strong></summary>


  1. Gilson, A., Meyer, L., Scholz, O., & Schmid, U. (2025). OmniPlantSeg: Species Agnostic 3D Point Cloud Organ Segmentation for High-Resolution Plant Phenotyping Across Modalities. arXiv preprint arXiv:2509.21038. [[paper](https://arxiv.org/abs/2509.21038)].
  
  2. Cañadas-Aránega, F., Moreno, J. C., & Blanco-Claraco, J. L. (2026). GreenSeg: Ground Segmentation Algorithm for Agricultural Robots in Mediterranean Greenhouses using RGB-D Point Clouds. arXiv preprint arXiv:2605.25279. [[paper](https://arxiv.org/abs/2605.25279)].
  
  3. Tan, H., Wang, Z., Fu, H., Zhao, X., Zhang, Y., Yang, M., & Zhai, C. (2026). Precision pesticide application in greenhouse asparagus: A semantic segmentation approach for canopy-adapted variable-rate spraying. Smart Agricultural Technology, 102297. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526005228)].
  
  4. Li, D., Huang, J., Zhao, B., & Wen, W. (2025). Organ3DNet: A deep network for segmenting organ semantics and instances from dense plant point clouds. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000911)].

  5. Murcia, H., & Lacroix, S. (2026). A simulation-to-real framework for architectural characterisation of orchard trees using mobile LiDAR. Precision Agriculture, 27(4), 105. [[paper](https://link.springer.com/article/10.1007/s11119-026-10373-2)]

  6. Wang, Y., & Wu, Q. (2025). Three-Dimensional Reconstruction Method of Nanguo Pear Fruit Based on SfM and Improved Neural Radiance Field. IAENG International Journal of Computer Science, 52(9). [[paper](https://www.iaeng.org/IJCS/issues_v52/issue_9/IJCS_52_9_50.pdf)]

 <!-- ----------------- Cylinder3D -------------------- -->


 <!-- ----------------- SalsaNext -------------------- -->

 7. De Silva, R., Nazari, K., Moraru, I., Li, D., Sklar, E. I., Pearson, S., & Coutts, S. (2026). AgSentry: LiDAR reflectivity based obstacle detection for safety in agricultural environments. Smart Agricultural Technology, 102014. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526002376)]

</details>

<details>
  <summary><strong>3. Entries excluded based on PRISMA</strong></summary>

1. Cañadas-Aránega, F., Blanco-Claraco, J. L., Moreno, J. C., & Rodriguez-Diaz, F. (2024). Multimodal mobile robotic dataset for a typical mediterranean greenhouse: The greenbot dataset. Sensors, 24(6), 1874. — Reason: dataset paper, not a segmentation-algorithm study referenced by any citation key. [[paper](https://www.mdpi.com/1424-8220/24/6/1874)].

2. Wang, W., Li, C., Xi, Y., Gu, J., Zhang, X., Zhou, M., & Peng, Y. (2025). Research progress and development trend of visual detection methods for selective fruit harvesting robots. Agronomy, 15(8), 1926. — Reason: survey/review article, not a primary study. [[paper](https://www.mdpi.com/2073-4395/15/8/1926)].

3. Ma, B., Du, J., Wang, L., Jiang, H., & Zhou, M. (2024). Automatic branch detection of jujube trees based on 3D reconstruction for dormant pruning using the deep learning-based method. Computers and Electronics in Agriculture, 190, 106484. — Reason: open orchard tree-branch detection/reconstruction study, outside the greenhouse domain filter. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169921005019)].

4. Wang, H., Shan, Y., Chen, L., Liu, M., Wang, L., & Meng, Z. (2025). Multi-scale feature learning for 3D semantic mapping of agricultural fields using UAV point clouds. International Journal of Applied Earth Observation and Geoinformation, 141, 104626. — Reason: UAV/open-field study, outside the greenhouse robotics domain. [[paper](https://www.sciencedirect.com/science/article/pii/S1569843225002730)].

5. Murcia, H., & Lacroix, S. (2026). A simulation-to-real framework for architectural characterisation of orchard trees using mobile LiDAR. Precision Agriculture, 27(4), 105. — Reason: open orchard-tree study, outside the greenhouse domain filter. [[paper](https://link.springer.com/article/10.1007/s11119-026-10373-2)].

6. Wang, Y., & Wu, Q. (2025). Three-Dimensional Reconstruction Method of Nanguo Pear Fruit Based on SfM and Improved Neural Radiance Field. IAENG International Journal of Computer Science, 52(9). — Reason: reconstruction/generation-scope study, not referenced by a Segmentation citation key. [[paper](https://www.iaeng.org/IJCS/issues_v52/issue_9/IJCS_52_9_50.pdf)].

7. De Silva, R., Nazari, K., Moraru, I., Li, D., Sklar, E. I., Pearson, S., & Coutts, S. (2026). AgSentry: LiDAR reflectivity based obstacle detection for safety in agricultural environments. Smart Agricultural Technology, 102014. — Reason: already documented under the Classification scope; not referenced by a Segmentation citation key. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526002376)].

</details>

</details>

<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------- Generative ------------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->

<details>
<summary><strong>Generative</strong></summary>
  
<details>
  <summary><strong>1. Articles on mathematical foundations</strong></summary>

  1. Sarraf, A., & Nie, Y. (2021). RGAN: Rényi generative adversarial network. SN Computer Science, 2(1), 17. [[paper](https://link.springer.com/article/10.1007/s42979-020-00403-9)]

  2. Yuan, W., Khot, T., Held, D., Mertz, C., & Hebert, M. (2018, September). Pcn: Point completion network. In 2018 international conference on 3D vision (3DV) (pp. 728-737). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/8491026)]

  3. Zhou, L., Du, Y., & Wu, J. (2021). 3d shape generation and completion through point-voxel diffusion. In Proceedings of the IEEE/CVF international conference on computer vision (pp. 5826-5835). [[paper](https://openaccess.thecvf.com/content/ICCV2021/html/Zhou_3D_Shape_Generation_and_Completion_Through_Point-Voxel_Diffusion_ICCV_2021_paper.html?ref=https://githubhelp.com)]

  4. Yu, X., Rao, Y., Wang, Z., Liu, Z., Lu, J., & Zhou, J. (2021). Pointr: Diverse point cloud completion with geometry-aware transformers. In Proceedings of the IEEE/CVF international conference on computer vision (pp. 12498-12507). [[paper](https://openaccess.thecvf.com/content/ICCV2021/html/Yu_PoinTr_Diverse_Point_Cloud_Completion_With_Geometry-Aware_Transformers_ICCV_2021_paper.html)]

  5. Zyrianov, V., Zhu, X., & Wang, S. (2022, October). Learning to generate realistic lidar point clouds. In European Conference on Computer Vision (pp. 17-35). Cham: Springer Nature Switzerland. [[paper](https://link.springer.com/chapter/10.1007/978-3-031-20050-2_2)]

</details>



<details>
  <summary><strong>2. Articles on greenhouse farming</strong></summary>

 <!-- ----------------- rGAN (Generación) -------------------- -->

1. Guo, Z., Yang, X., Shen, Y., Zhu, Y., Jiang, L., & Cen, H. (2026). A novel point cloud completion model for three-dimensional reconstruction of complex, dynamic population-level crop canopy architecture. Plant Communications, 7(3). [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925008543)].

2. Quan, T., Luo, J., Xie, S., Ren, X., & Miao, Y. (2025). Real-Time Semantic Reconstruction and Semantically Constrained Path Planning for Agricultural Robots in Greenhouses. Agronomy, 15(12), 2696. [[paper](https://www.mdpi.com/2073-4395/15/12/2696)].

3. Li, X., Li, F., Qi, Y., & Li, Z. (2025). Plantformer: plant point cloud completion based on local–global feature aggregation and spatial context-aware transformer. Neural Computing and Applications, 37(4), 2747-2762. [[paper](https://link.springer.com/article/10.1007/s00521-024-10659-4)].

4. Zhou, L., Xu, Y., Zhang, C., Zhang, X., Wu, Q., Bian, L., Elsherbiny, O., & Zhang, H. (2026). From pixels to points: An AI framework with weaker-and-fewer-labels for lightweight 3D phenotyping using 2D-3D coordinate mapping and VLMs. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000139)].

5. Huang, Z., Yang, N., Cao, R., Li, Z., He, Y., & Feng, X. (2025). Autonomous navigation system in various greenhouse scenarios based on improved FAST-LIO2. Computers and Electronics in Agriculture, 234, 110279. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925003850)].

6. Lielamurs, E., Sayed, I., Cvetkovs, A., Novickis, R., Zencovs, A., Celitans, M., Bizums, A., Dimitrakopoulos, G., Kaszzescha, J., & Ozols, K. (2025). A distributed time-of-flight sensor system for autonomous vehicles: architecture, sensor fusion, and spiking neural network perception. Electronics, 14(7), 1375. [[paper](https://www.mdpi.com/2079-9292/14/7/1375)].

7. Yuan, M., Wang, D., Lin, J., Yang, S., & Ning, J. (2025). SSP-MambaNet: An automated system for detection and counting of missing seedlings in glass greenhouse-grown virus-free strawberry. Plant Phenomics, 7(2), 100043. [[paper](https://www.sciencedirect.com/science/article/pii/S2643651525000494)].


</details>

<details>
  <summary><strong>3. Entries excluded based on PRISMA</strong></summary>

1. Li, S., Cui, Z., Yang, J., & Wang, B. (2025). A review of optical-based three-dimensional reconstruction and multi-source fusion for plant phenotyping. Sensors, 25(11), 3401. — Reason: survey/review article, not a primary study. [[paper](https://www.mdpi.com/2076-3417/15/14/7663)].

2. Lin, J., Bai, X., Yuan, M., Wang, D., Yang, S., & Ning, J. (2025). A greenhouse strawberry seedbed image stitching method based on seedbed plane alignment and efficient point-line matching. Computers and Electronics in Agriculture, 236, 110416. — Reason: not referenced in the final Generation table. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925005228)].

3. Timprae, W., Sagawa, T., Baar, S., Kondo, S., Okada, Y., Sato, K., et al. (2025). Tomato Growth Monitoring and Phenological Analysis Using Deep Learning-Based Instance Segmentation and 3D Point Cloud Reconstruction. Sustainability, 17(22), 10120. — Reason: not referenced in the final Generation table. [[paper](https://www.mdpi.com/2071-1050/17/22/10120)].

4. Shafik, W., Tufail, A., Namoun, A., De Silva, L. C., & Apong, R. A. A. H. M. (2023). A systematic literature review on plant disease detection: motivations, classification techniques, datasets, challenges, and future trends. IEEE Access, 11, 59174-59203. — Reason: survey/review article, not a primary study. [[paper](https://ieeexplore.ieee.org/abstract/document/10147225)].

5. Li, K., Sha, Z., Xue, W., Chen, X., Mao, H., & Tan, G. (2020). A fast modeling and optimization scheme for greenhouse environmental system using proper orthogonal decomposition and multi-objective genetic algorithm. Computers and Electronics in Agriculture, 168, 105096. — Reason: environmental-control modeling study, not a vision/LiDAR ML paper and outside the review's 2024-onward search window. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169919309172)].

</details>


</details>

