# Vision and LiDAR-Based Machine Learning in Greenhouse Mobile Robotics: A systematic review 🌱 🤖
A repository providing a state-of-the-art overview of the most important algorithms as a basis for their use in greenhouse agriculture. It focuses on computer vision algorithms using cameras and LiDARs, amongst other sensors.

<div align="center"> 
  <img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/fb4ad2c5-85ff-45f7-a888-cdcfb2e47ac8" />
</div>

*Author: Fernando Cañadas Aránega, PhD student in Agricultural Robotics at the University of Almería, Spain.*

*Gmail: fernando.ca@ual.es*

*Website: https://linktr.ee/FerCanAra*

<!-- Algoritmo de visión que utilizan -->

## Vision algorithms for robotics

The foundational articles underpinning the most significant advances in vision technology are available for subsequent application in agriculture, specifically in greenhouses.

<div align="center">
  <img width="500" height="423" alt="image" src="https://github.com/user-attachments/assets/f28ec83f-27d0-4b56-ac4e-cbc57965b4b6" />
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
  <summary><strong>2. Articles on greenhouse farming</strong></summary>

<!-- -----------------AlexNet -------------------- -->

  1. Tang, R., Aridas, N. K., Talip, M. S. A., Yang, J., & Tang, J. (2025). _High-precision pest and disease detection in greenhouses using the novel IM-AlexNet framework_. npj Science of Food, 9(1), 68. [[paper](https://www.nature.com/articles/s41538-025-00426-7)]].

  2. Ragavee, U., Oviya, R., & KR, N. (2025). _Renewable Energy-Driven IoT System for Automated Greenhouse Monitoring_. In 2025 International Conference On Emerging Computation and Information Technologies (ICECIT) (pp. 1-6). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11450958)]

  3. Zimmermann, G. B., Pellenz, M. E., Costa, Y. M., & Britto Jr, A. D. S. (2025). _Enhancing Disease and Pest Detection in Greenhouse Tomato Cultivation Using Advanced Machine Learning on New Dataset of Images_. Journal of the Brazilian Computer Society, 31(1). [[paper](https://openurl.ebsco.com/EPDB%3Agcd%3A16%3A20183152/detailv2?sid=ebsco%3Aplink%3Ascholar-a&id=ebsco%3Agcd%3A184589193&crl=c&jrnl=01046500&id_token_hint=eyJraWQiOiIxNzY5MTEwMjQ0MDQ3IiwiYWxnIjoiUlMyNTYifQ.eyJzdWIiOiJzNTYwMjQ3OC5tYWluIiwiZGV2aWNlX2lkIjoiMzc2MDRkNWQtNmI2OS00N2NkLTkxMWQtNTlmZTMzM2Q4MzVkIiwiYW1yIjpbImlwIl0sImlzcyI6Imh0dHBzOi8vYXV0aC5lYnNjby56b25lL2FwaS9kaXNwYXRjaGVyIiwiY2xpZW50X2lkIjoiYXdneWNJeDU3TXJ3bkRRNWg0VWU2eUNWRVAwcjVNdDkiLCJhdWQiOlsiaHR0cHM6Ly9hdXRoLmVic2NvLnpvbmUvYXBpL2Rpc3BhdGNoZXIiLCJodHRwOi8vYXV0aC1jeHQtbWdyLmVob3N0LWxpdmUuZWtzLmVob3N0LWxpdmUuZWlzbHouY29tIiwiaHR0cDovL3hmZi1wcm9jZXNzb3ItamF2YS5laG9zdC1kZXYuZWtzLmVob3N0LWRldnFhLmVpc2x6LmNvbS9zd2FnZ2VyLXVpL2luZGV4Lmh0bWwiLCJodHRwczovL2FjY2Vzcy1hcGkuZWJzY28uY29tIiwiYXdneWNJeDU3TXJ3bkRRNWg0VWU2eUNWRVAwcjVNdDkiXSwiYXpwIjoiYXdneWNJeDU3TXJ3bkRRNWg0VWU2eUNWRVAwcjVNdDkiLCJpZHQiOiJpbnN0aXR1dGlvbmFsIiwiZXhwIjoxNzg0MjAzMzEzLCJpYXQiOjE3ODQxOTk3MTMsImNsaWVudF9uYW1lIjoiV2ViYXV0aCAtIE5ldyBFRFMgaWRfdG9rZW4iLCJqdGkiOiI5YWRlNmY3Yy03ZTU2LTQ2MmUtYTg5Mi05NGJkOGRjYjIwNmIiLCJ1c2VybmFtZSI6Ikluc3RpdHV0aW9uYWxVc2VyIn0.Mybbsd6X8tswrXUO3Z3Pn5vsFqaTCu3Tfm86nwa6H6D6WbqS5QxxObyWJLXZfy6F2Zj4Po2cVisazLGBywtHGOFxGnREa5jsfWvWoCbr4qoxb1F17eMXu_wQjBF-rRkvzZHHyPnAjIJ6CKaY1We8yImKti2li3g_B0L1GeGLa8oT031X6R6PQjULKgWoD-K_xJsSYl4ol3A211GlVLE16bx07MNni3T3jLgKmNHRw_IDKTP_0JXCblq21oc1hX1LfBjYenLWrKc5U6HgA3xEHUK5kwcYyqs-jf_mtoRxyd7MZ0llVRXvsNHZ5Ah2E8NhMdUJIajUmAT2Q-qfDWuxgQ&link_origin=scholar.google.es)]

  4. Bhaskar, C. G., Krishnan, C. A., & Manimekala, B. (2026). _Automated tomato leaf disease diagnosis with improved Alex Net model_. In AIP Conference Proceedings (Vol. 3427, No. 1, p. 020015). AIP Publishing LLC. [[paper](https://pubs.aip.org/aip/acp/article-abstract/3427/1/020015/3392439/Automated-tomato-leaf-disease-diagnosis-with)]

  5. Rao, S. T., Dulla, T. C., Kolla, V. K., Kurakula, G. S., Suneetha, M., Moturi, S., & Reddy, D. V. (2025, March). _Deeplearning-based tomato leaf disease identification: Enhancing classification with alexnet_. In 2025 IEEE International Conference on Interdisciplinary Approaches in Technology and Management for Social Innovation (IATMSI) (Vol. 3, pp. 1-6). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/10984969)]

  6. Parvez, S., Uddin, M. A., Islam, M. M., Bharman, P., & Talukder, M. A. (2025). _Tomato leaf disease detection using convolutional neural network_. In Applied Intelligence for Healthcare Informatics (pp. 42-55). CRC Press. [[paper](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003583363-4/tomato-leaf-disease-detection-using-convolutional-neural-network-shamima-parvez-md-ashraf-uddin-md-manowarul-islam-pallab-bharman-md-alamin-talukder)]

  7. Kiran, K., Gopal, L., Agarwal, V., Bansal, V., & Gupta, R. (2026, April). CNN-Based Tomato Leaf Disease Detection for Sustainable Agriculture. In 2026 13th International Conference on Computing for Sustainable Global Development (INDIACom) (pp. 1-6). IEEE. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11526549)]

  8. Xiang, J., Ge, J., Fu, C., Huang, J., Lu, M., Zhang, Z., Yihong, S., & Yan, S. (2026). An environment-guided visual–temporal deep learning framework for early disease detection in greenhouse horticultural crops. Frontiers in Plant Science, 17, 1796407. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1796407/full)]].
     
  9. Antony, A. J., & Murugan, R. (2026, April). Transforming Agriculture with AI: Insights into Computer Vision Applications for Sustainable Farming. In 2026 International Conference on AI-Driven Innovations & Applications (IC-AIDA) (pp. 1-12). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11564160)]
      
  10. Upadhyay, A., Chandel, N. S., Singh, K. P., Chakraborty, S. K., Nandede, B. M., Kumar, M., Subbesh, A., Upendar, K., Salem, A., & Elbeltagi, A. (2025). _Deep learning and computer vision in plant disease detection: a comprehensive review of techniques, models, and trends in precision agriculture._ Artificial Intelligence Review, 58(3), 92. [[paper](https://link.springer.com/article/10.1007/s10462-024-11100-x)]

<!-- -----------------ResNet -------------------- -->

  11. Swamy, L. N., Parande, P. V., Kumar, H. M., Rakshitha, V., Thimmaraju, S. N., & Yogesha, T. (2026). Convolutional Neural Network Architectures for Enhanced Tomato Leaf Disease Classification using ResNet-152 and VGGNet Model. Indian Journal of Agricultural Research, 60(1), 130-134. [[paper](https://indianjournals.com/article/ijar2-60-1-019)]
     
  12. Jain, E., Kukreja, V., Kaushik, P., Ahuja, V., & Bansal, A. (2025). Hybrid ViT-ResNet: A High-Accuracy AI Model for Automated Strawberry Ripeness Classification in Precision Agriculture. Applied Fruit Science, 67(5), 368. [[paper](https://link.springer.com/article/10.1007/s10341-025-01576-4)]
     
  13. Jiang, N. (2025, November). Crop disease detection for greenhouses: a lightweight solution combining ResNet and Inception. In International Conference on Advanced Algorithms and Image Processing Technologies (IC-AAIP 2025) (Vol. 13933, pp. 50-56). SPIE. [[paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13933/1393309/Crop-disease-detection-for-greenhouses--a-lightweight-solution-combining/10.1117/12.3090705.short)]
     
  14. Muthaiah, U., Reddy, Y. N., & Roy, R. V. (2026, January). RESNET Based Crop Disease Detection Models Using Convolutional Neural Networks. In Operations Research and Data Analytics: Current Trends and Future Perspectives: Selected Papers from International Conference on Industrial Engineering and Analytics (ICONIEA) 2024 (pp. 365-386). Singapore: Springer Nature Singapore. [[paper](https://link.springer.com/chapter/10.1007/978-981-96-8327-7_20)]

  15. Zhang, K., Chai, Q., Gao, R., Shen, A., Liu, X., Yang, L., Pang, G., Wang, Y., Liu, X., & Sun, J. (2026). Deep learning-powered diagnosis of greenhouse tomato growth using time-series RGB images. Computers and Electronics in Agriculture, 245, 111566. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169926001614)]

  16. Yusof, M. I., Yasin, F. N. M., Risangtuni, A. G., Putra, N. K., Samseh, S. H., Zainal, A., & Sani, M. A. A. (2026). Enhancing Greenhouse Pollination with CNN-Based Micro-UAV for Real-Time Flower Detection. [[paper](https://www.preprints.org/manuscript/202602.2026)]

  17. Xue, X., Thakur, V., Dhumras, H., Jhaveri, R. H., & Gadekallu, T. R. (2025). Real-Time Pest Detection Using ResNet-50 and Vision Transformer: An IoT-Enabled Mobile Application for Smart Agriculture. IEEE Transactions on Consumer Electronics. [[paper](https://ieeexplore.ieee.org/abstract/document/11127220)]

  18. Wang, L., Li, Y., Lin, H., Tong, J., Sun, L., Wang, X., & Jiang, J. (2025). RTR-CNN: Rotated tray region selection and young seedling health status detection by CNN in greenhouse seedbed. Computers and Electronics in Agriculture, 229, 109723. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169924011141)]

  19. Zhang, L., Li, X., Yang, Z., Yang, B., Yu, S., Zhao, S., ... & Yang, M. (2025). Tomato seedling stem and leaf segmentation method based on an improved ResNet architecture. Frontiers in Plant Science, 16, 1571445. [paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1571445/full)]

  20. Cohen, A., Muriki, H., Sun, Y., Qin, Z., Gan, L., & Chen, Y. (2025). A Proof-of-Concept for Non-Destructive Lettuce Nutrient Assessment Using Vision Transformers and Residual Networks on Raw Hyperspectral Imagery. Smart Agricultural Technology, 101501.[[paper](https://www.sciencedirect.com/science/article/pii/S2772375525007324)]
      
<!-- -----------------DenseNet -------------------- -->

  21. Jain, S., & Rajpoot, R. (2025). Real-Time Monitoring and Disease Detection in Greenhouses Using IoT and Deep Learning. In Computational Intelligence Techniques for 5G Enabled IoT Networks (pp. 213-235). Cham: Springer Nature Switzerland. [paper](https://link.springer.com/chapter/10.1007/978-3-031-82733-4_14)]

  22. Jain, S., & Rajpoot, R. (2025). Real-Time Monitoring and Disease Detection in Greenhouses Using IoT and Deep Learning. In Computational Intelligence Techniques for 5G Enabled IoT Networks (pp. 213-235). Cham: Springer Nature Switzerland. [[paper](https://link.springer.com/chapter/10.1007/978-3-031-82733-4_14)]].

  23. Kavitha, K. (2025, October). Deep Learning-Driven Computer Vision Techniques for Advancing Smart Greenhouse Agriculture. In 2025 International Conference on Sustainable Communication Networks and Application (ICSCN) (pp. 24-30). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11308643)]

  24. Liang, L., Chen, J., Tian, Y., Wang, H., Cai, Y., Zhong, F., Wang, A., Hou, M., & Lu, J. (2026). DenseNet-BiFPN-ECA Fusion Network: An Enhanced Transfer Learning Approach for Tomato Leaf Disease Recognition. Horticulturae, 12(4), 423. [paper](https://www.mdpi.com/2311-7524/12/4/423)]

  25. Pounambal, M., & Vellingiri, J. (2025). Advancing agricultural sustainability with gradient weighted Densenet-201 model for accurate detection of plant leaf diseases. Environment, Development and Sustainability, 1-27. [[paper](https://link.springer.com/article/10.1007/s10668-025-06314-0)]

  26. Alam, M. S., Ali, M. R., & Rahman, A. (2025). Detection and Localization of Ripe Tomato in Greenhouse Environment Using Keras-Based Deep Learning Models. Journal of Agriculture and Food Research, 102182. [[paper](https://www.sciencedirect.com/science/article/pii/S2666154325005538)]

  27. Santoso, H. A., Fandhi Safsalta, B., Febrianto, N., Wilujeng Saraswati, G., & Haw, S. C. (2026). Comparative analysis of convolutional neural network and DenseNet121 transfer learning in agriculture focusing on crop leaf disease identification. Applied Computing and Informatics, 22(3-4), 316-328. [[paper](https://www.emerald.com/aci/article/22/3-4/316/1248414)]

  28. Shi, D., Liang, L., Chen, X., Yang, X., Li, M., & Diao, M. (2025). DTM-Unet: A Deep Learning Framework Incorporating DenseNet and Transformer for Precise Identification and Quantitative Segmentation of Cucumber Leaf Disease. Smart Agricultural Technology, 101659. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525008901)]

  29. Huang, Y., Huang, T., Du, J., Qiu, J., Liu, C., Wan, F., ... & Wang, L. (2026). DenseNet-CSL: An Enhanced Network for Multi-Class Recognition of Agricultural Pests, Weeds, and Crop Diseases. Agriculture, 16(4), 394. [[paper](https://www.mdpi.com/2077-0472/16/4/394)]

  40. Saxena, A., Agarwal, A., Nagrath, B., Jayavanth, C. S., Thulasidoss, S., Maheswari, S., & Sasikumar, P. (2025). Deep learning-driven IoT solution for smart tomato farming. Scientific Reports, 15(1), 31092. [[paper](https://www.nature.com/articles/s41598-025-15615-)]

<!-- ----------------- VGG -------------------- -->

  41. Paymode, A. S., & Malode, V. B. (2022). _Transfer learning for multi-crop leaf disease image classification using convolutional neural network VGG_. Artificial Intelligence in Agriculture, 6, 23-33. [[link](https://www.sciencedirect.com/science/article/pii/S2589721721000416)]].

  42. Sajid, S., Li, P., Zhang, L., Jie, C., Ali, A., & Ullah, F. (2025). Leveraging VGG-19 for automated fruit classification in smart agriculture. PeerJ Computer Science, 11, e3391. [[paper](https://peerj.com/articles/cs-3391/)]

  43. Xiang, J., Ge, J., Fu, C., Huang, J., Lu, M., Zhang, Z., ... & Yan, S. (2026). An environment-guided visual–temporal deep learning framework for early disease detection in greenhouse horticultural crops. Frontiers in Plant Science, 17, 1796407.[[paper](https://link.springer.com/article/10.1186/s13007-025-01456-8)]

  44. Ram, B. G., Howatt, K., Mettler, J., & Sun, X. (2025). Addressing computation resource exhaustion associated with deep learning training of three-dimensional hyperspectral images using multiclass weed classification. Artificial Intelligence in Agriculture, 15(2), 131-146. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000248)]

  45. Siva, V., & Ponnusamy, V. (2025, September). Tomato Ripeness Evaluation Through Cutting-Edge Deep Learning Models. In World Conference on Information Systems for Business Management (pp. 413-423). Cham: Springer Nature Switzerland. [[paper](https://link.springer.com/chapter/10.1007/978-3-032-13006-8_40)]

  46. Xiang, J., Ge, J., Fu, C., Huang, J., Lu, M., Zhang, Z., Song, Y., & Yan, S. (2026). An environment-guided visual–temporal deep learning framework for early disease detection in greenhouse horticultural crops. Frontiers in Plant Science, 17, 1796407. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1796407/full)]

  47. Swapna, B., Kameswaran, S., & Ramakrishna, M. (2026). Deep Learning in Plant Pest Control. In Plant Genomic Prediction: AI-Enhanced Models for Plant Genomics and Crop Improvement (pp. 335-351). GB: CABI. [[paper](https://www.cabidigitallibrary.org/doi/full/10.1079/9781836991328.0017)]

  48. Islam, M. S., Rahman, N., Mahmud, M. T., Naidu, A., Toha, M. A., Yasar, S., ... & Jamil, S. U. (2026, April). An Automated Approach for Classifying The Severity of Cucumber Diseases Using Deep Learning and Transfer Learning. In 2026 IEEE 5th International Conference on Computing and Machine Intelligence (ICMI) (pp. 1-5). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11539878)]

  49. Duan, S., Huang, X., Wu, P., Zhang, C., Zhao, S., & Fan, J. (2026). Multimodal deep learning for identifying onshore natural gas facilities from GaoFen-2 imagery. International Journal of Digital Earth, 19(1), 2662059. [[paper](https://www.tandfonline.com/doi/full/10.1080/17538947.2026.2662059)]

  50. Sundaravadivel, P., Reyes-Ramirez, R., Sethurani, P. M., Brown, C., Borah, S. S., & Kousik, S. (2026). AI-Enabled Reconfigurable Edge Device for Plant Health Assessment in Greenhouse Environment. In The First International Workshop on AI in Agriculture. [[paper](https://openreview.net/forum?id=7GDdzjv6EZ)]

<!-- -----------------EfficientNet -------------------- -->

  51. Ray, R. K., Chakravarty, S., Dash, S., Ghosh, A., Mohanty, S. N., Chirra, V. R. R., ... & Khan, M. I. (2025). Precision pest management in agriculture using Inception V3 and EfficientNet B4: A deep learning approach for crop protection. Information Processing in Agriculture. [[link](https://pdf.sciencedirectassets.com/287278/1-s2.0-S2214317326X20017/1-s2.0-S2214317325000484/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLWVhc3QtMSJHMEUCIQDFNdaJIpMO8un2YREl7ZzcR%2Bqjy%2B64kSGwm7iKWvblCgIgTGxpVQRcxrsvVie1HRFhAaCOUxQWMd4wGsiRe%2BKB35AqsgUIQxAFGgwwNTkwMDM1NDY4NjUiDFEQNIwycl46KUiUjSqPBVXT4m3h9No4L6wVf3jWMgu5FI0PtsfwSTOrwkg3rNX8cTRZu435trwyQZOYerFMyZgDIwKumHZaJcv28ZM6Uz4mZWViw%2FpVxBsDjwpJGg%2FRS9D40ZMCEBXEOSrNi3hKn4BTmnzn5FeDhklkAZ9skAqXTO792oRz6OWckq1n3v%2F6%2F8t7Qg20H0r94o3P6DQO7IgU3hldKCCsWLEyRUCpAmcukvT87AF2XDoSbQfYKg6YNFqplAOufLWDwUN6yhGkXTTW5uiiqUpnRY03vJry7gkjwbJotBr9fL4nz6tZQy5u3XAXM4x1qyTbB4%2F4Dllv%2BjlQxDN27y4v1GJX3NYHJBv9enzw10D8eAXWfXVmToSxmIF6HnQnpeAsQCHubo69djXmmFAR6A0O8b%2B9PmCeXhH6SovYblgUu1oAlgT1ACuh4nXoiVjR21KwTN2k92d2EBDKa%2BR4BmgB0GY7ylbzt335QUTNZWYb0D%2B1ILQHuRx3Ci6fq2g6OlAVHDkA4gW1nmocuW3pz3y%2BOijdRSDWtAf1jPZ%2FR9YIQdzm2weeLLLG%2FW1oTsLfog2WcoHviwt3LZMx%2BarqPGN2zkMKLpO44fPQ1%2BgUq2KGdYj5YI1zCM8lt5QXn6yC%2FUJpaWUwMSh9%2Fm3aNX8viJGvLrJOWfXGRxGgEX2lnSTH32ekW8zDhKP8VDuZ8%2F1iqV%2FurDQWEGqxCo5HZod0qMUNPcMXAXhbzRlKwqRiMbEalwjwZ24dMwqFiXo%2FEMgM4aMVJRH%2BT%2B%2B7B0sd6UG6nlPpwi0dVLE4tYgbLp7h0dSSauq6BxM4tE6A04j0ymVQT2DHE4hvjhSEp%2F%2BdYyJI9cWsR6piODig6d2gTEKNbqn0xd5NwrCYCswwxtXi0gY6sQGe3ujjAKuegZHQRSUk7Vi1w%2FpZHgYPTlv62tVRXgM%2Fok8HX4zCxeKMHKPEUl6QODA924ByIH%2FDAONQdG30N4d7tVn2MZkz6V6kOf5CP6XA%2FqI%2F7V0u%2Btolph7GJI6l0Dig9mYwaYafmreYGtncwnfimJRZbkWvZ5rP5kuvk4MpBsfu%2BXa03Ngt9JsuePBTkKg91%2F1j9PVAwI6ZIi8dJMe1rM1a0x2w%2FfZhPeIlqUqESJA%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20260716T111024Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYTJI5SB7Z%2F20260716%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=873107445461b4ec7101384730bf87aebb64af29f4c69fe54d4edc04ca5d21c1&hash=ea9054ff413afe71d651615dee9f6078a7247775a319130cb7d6a9ed6eceb81c&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2214317325000484&tid=spdf-2d7597f6-9625-4fc0-a375-c6f88d9438a2&sid=cb3a75e7265cf54a489aeda19b8c87ea2832gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=0313045602515d01550d&rr=a1c08f6c28ddd665&cc=es)]

  52. Ni, L., Ye, F., Cui, X., Peng, X., Song, S., & Luo, W. (2026). Comparative Study of Lightweight Deep Learning Models for Greenhouse Tomato Leaf Disease Classification Using the Public TLID Dataset. Digital Intelligence in Agriculture, 2(1), 45-53. [[paper](https://www.icck.org/article/abs/dia.2026.103152)]

  53. Subhan, M., Rana, N., Qamar, F., Jeribi, F., Alhazmi, A. H., Tahir, A., & Shahzadi, R. (2026). Crop disease detection using EfficientNetB0 deep learning approach for precision agriculture. Discover Computing, 29(1), 25. [[paper](https://link.springer.com/article/10.1007/s10791-025-09881-y)]

  54. Sahu, S., & Verma, P. (2026). UAV-based real-time detection of corn earworm using EfficientNet and machine learning. Journal of Environmental Science and Health, Part B, 1-14. [[paper](https://www.tandfonline.com/doi/full/10.1080/03601234.2026.2660035?scroll=top&needAccess=true)]

  55. Yang, Q., Lao, D., Wu, Y., Liu, C., Zhang, Z., Li, Z., ... & Li, F. (2026). Leaf thermal infrared imaging and lightweight deep learning enable early detection of water stress in watermelon for precision irrigation. Agricultural Water Management, 329, 110344. [[paper](https://www.sciencedirect.com/science/article/pii/S0378377426002258)]

  56. Shanthini, S., & Dheeran, S. (2025, February). EfficientNet-Based Feature Extraction and Ensemble Learning for Tomato Quality Classification. In 2025 3rd International Conference on Intelligent Systems, Advanced Computing and Communication (ISACC) (pp. 589-595). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/10969232)]

  57. Kavitha, K. (2025, October). Deep Learning-Driven Computer Vision Techniques for Advancing Smart Greenhouse Agriculture. In 2025 International Conference on Sustainable Communication Networks and Application (ICSCN) (pp. 24-30). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11308643)]

  58. Ni, L., Ye, F., Cui, X., Peng, X., Song, S., & Luo, W. (2026). Comparative Study of Lightweight Deep Learning Models for Greenhouse Tomato Leaf Disease Classification Using the Public TLID Dataset. Digital Intelligence in Agriculture, 2(1), 45-53. [[paper](https://www.icck.org/article/abs/dia.2026.103152)]

  59. Wang, X. (2025, August). EfficientNet-SE: A Lightweight Attention-Enhanced CNN for Real-Time Crop Leaf Disease Detection in Precision Agriculture. In 2025 6th International Conference on Internet of Things, Artificial Intelligence and Mechanical Automation (IoTAIMA) (pp. 63-67). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11212650)]

  60. Nashrulloh, M. H., & Subarkah, A. (2025). Fruit Image Classification Using CNN With EfficientNet Architecture for Visual Education. Journal of Intelligent Systems Technology and Informatics, 1(2), 67-71. [[paper](https://journal.aptika.org/index.php/jistics/article/view/9)]

<!-- -----------------ViT -------------------- -->

  61. Rajendran, M., & Muruganantham, M. (2026). Tomato leaf disease classification using a vision transformer with cascaded group attention (ViT-CGA) for real-time decision support in precision agriculture. Journal of Plant Diseases and Protection, 133(3), 91. [[paper](https://link.springer.com/article/10.1007/s41348-026-01274-7)]

  62. Zeng, Z., Mahmood, T., Wang, Y., Rehman, A., & Mujahid, M. A. (2025). AI-driven smart agriculture using hybrid transformer-CNN for real time disease detection in sustainable farming. Scientific Reports, 15(1), 25408. [[paper](https://www.nature.com/articles/s41598-025-10537-6)]

  63. Verma, P. K., Gupta, N., Sharma, A. K., Rakesh, N., & Gulhane, M. (2025). ViTCon: a hybrid CNN-ViT model for improved plant leaf disease detection. Cogent Food & Agriculture, 11(1), 2562165. [[paper](https://www.tandfonline.com/doi/full/10.1080/23311932.2025.2562165)]

  64. Huo, Y., Liu, Y., He, P., Hu, L., Gao, W., & Gu, L. (2025). Identifying Tomato Growth Stages in Protected Agriculture with StyleGAN3–Synthetic Images and Vision Transformer. Agriculture, 15(2), 120. [[paper](https://www.mdpi.com/2077-0472/15/2/120)]

  65. Hasasneh, A., Ghannam, R., & Masri, S. (2025). WeedNet-ViT: A Vision Transformer Approach for Robust Weed Classification in Smart Farming. Geographies, 5(4), 64. [[paper](https://www.mdpi.com/2673-7086/5/4/64)]

  66. Guttikonda, B. S., Al-Khafaji, Z. A., Senthil, P., & Kavitha, P. (2025, June). Smart Agriculture Framework for Multi-Crop Disease Detection using IoT and Vision Transformer. In 2025 International Conference on Intelligent Computing and Knowledge Extraction (ICICKE) (pp. 1-7). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11136532)]

  67. ÖZDEN, C. (2026). Vision Transformer and CNN-Based Models for Image Analysis of Plant Diseases: An Approach for Agricultural Decision Support Systems. ISPEC Journal of Agricultural Sciences. [[paper](https://ispecjournal.com/index.php/ispecjas/article/view/915)]

  68. Lata, K., Kaur, N., & Singh, S. (2025). Satellite-Based Crop Recognition Using Vision Transformer Models for Smart Agriculture. Engineering Proceedings, 118(1), 34. [[paper](https://www.mdpi.com/2673-4591/118/1/34)]

  69. Cho, S. B., Choi, J. W., Hidayat, M. S., Cho, J. I., Lee, H., Cho, B. K., & Kim, G. (2025). Development of a CNN classifier with XAI to detect interpretable water stress in sweet potato using RGB images. Agricultural Water Management, 321, 109899. [[paper](https://www.sciencedirect.com/science/article/pii/S0378377425006134)]

  70. Venkatesh, K., Prasad, M., Kurikala, G., & Singh, L. K. (2026, February). Crop Health Identification by Exploiting CNN-ViT Synergy: Detecting Multi-Nutrient Deficiencies. In 2026 2nd International Conference on Advances in Intelligent Computing and Applications (AICAPS) (pp. 1-4). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11452925)]

<!-- ----------------- Swin tranformers -------------------- -->

  71. Iftee, I. K., Ahmed, F., Jobaier, M. H., Osama, A. U., & Aziz, N. H. A. (2025, October). Smart Agriculture: Cucurbit Leaf Disease Detection Using Swin Transformer. In 2025 International Conference on Engineering and Emerging Technologies (ICEET) (pp. 1-6). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11423931)]

  72. Liu, H., Gan, Y., Ren, X., Xu, J., Lin, P., & Chen, Y. (2026). Vision-based quantitative assessment of strawberry ripeness using a detail-aware perception transformer in complex agricultural environments. Journal of Food Measurement and Characterization, 20(4), 6418-6440. [[paper](https://link.springer.com/article/10.1007/s11694-026-04078-3)]

  73. Zhang, H., Gong, Z., Hu, C., Chen, C., Wang, Z., Yu, B., ... & Lv, C. (2025). A transformer-based detection network for precision cistanche pest and disease management in smart agriculture. Plants, 14(4), 499. [[paper](https://link.springer.com/chapter/10.1007/978-981-96-8796-1_19)]

  74. Haqiq, N., Zaim, M., Sbihi, M., El Alaoui, M., El Amraoui, K., El Kazini, Y., Roukhe, H., & Masmoudi, L. (2026). Lightweight Hybrid Deep Learning for Strawberry Disease Recognition and Edge Deployment Using Dynamic Multi-Scale CNN–Transformer Fusion. AgriEngineering, 8(2), 75. [[paper](https://www.mdpi.com/2624-7402/8/2/75)]

  75. Murugesan, S., Chinnadurai, J., Srinivasan, S., Mathivanan, S. K., Chandan, R. R., & Moorthy, U. (2025). Robust multiclass classification of crop leaf diseases using hybrid deep learning and Grad-CAM interpretability. Scientific Reports, 15(1), 29955. [[paper](https://www.nature.com/articles/s41598-025-14847-7)]

  76. Zhang, Q., Zhao, J., Cai, Y. L., Liu, K., & Li, Y. (2026). Toward smart agriculture: a hybrid mamba-transformer vision framework for plant disease detection. Frontiers in Plant Science, 17, 1846242. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1846242/full)]

<!-- ----------------- ConvNet -------------------- -->

  81. Mashamba, M. M., Telukdarie, A., Munien, I., Onkonkwo, U., & Vermeulen, A. (2024). _Detection of bacterial spot disease on tomato leaves using a Convolutional Neural Network (CNN)_. Procedia Computer Science, 237, 602-609. [[link](https://www.sciencedirect.com/science/article/pii/S187705092401161X)]

  82. Wu, Y., Dai, J., Zhu, Y., & Zhang, T. (2025). _Intelligent Agricultural Greenhouse Extraction Method Based on Multifeature Modeling: Fusion of Geometric, Spatial, and Spectral Characteristics_. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 18, 5568-5581. [[link](https://ieeexplore.ieee.org/abstract/document/10858674)]].

  83. Vanmathi, C., Mangayarkarasi, R., Agrawal, R., Sumalatha, L., & Shankar, V. (2026). Cross Disease Similarity Awareness Learning (CDSAL) with DenseNet–EfficientNet embedding fusion for high-precision tomato leaf pathology classification with Grad-CAM explainability. Scientific Reports. [[paper](https://www.nature.com/articles/s41598-026-48099-w)]

  84. Landolfo, M., Perotti, F., Pistillo, A., Pennisi, G., Gianquinto, G., & Orsini, F. (2025). Optimizing artificial lighting for convolutional neural network-based crop monitoring with low-cost RGB imaging in indoor cultivation. Smart Agricultural Technology, 101677. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525009086)]

  85. Xing, X., Gao, J., Qi, P., Wang, S., Wang, F., Peng, X., Fangyan, W., Hou, X., & Gao, J. (2026). A Lightweight Multi-View Detection and Counting Method for Real-Time Cherry Tomato Yield Estimation Using Greenhouse Inspection Robots. Smart Agricultural Technology, 102260. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526004843)]

  86. Bashir, A., Wang, Y., Ojo, M. O., & Zahid, A. (2025). A Vision System for Occluded Cutting Point Localization in Robotic Harvesting of Greenhouse Lettuce. IEEE Transactions on AgriFood Electronics. [[paper](https://ieeexplore.ieee.org/abstract/document/11219194)]

  87. Cardenas-Gallegos, J. S., Severns, P. M., Klimeš, P., Lacerda, L. N., Peduzzi, A., & Ferrarezi, R. S. (2025). Reliable plant segmentation under variable greenhouse illumination conditions. Computers and Electronics in Agriculture, 229, 109711. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169924011025)]

  88. Song, W., He, H., Dai, J., & Jia, G. (2025). Extraction of agricultural plastic greenhouses based on a U-Net convolutional neural network coupled with edge expansion and loss function improvement. Journal of the Air & Waste Management Association, 75(2), 109-120. [[paper](https://www.tandfonline.com/doi/full/10.1080/10962247.2024.2412708)]

  89. Amir, A., Giri, S., Giri, S., & Butt, M. (2025). An advanced approach to tomato apex head thickness measurement using lightweight YOLO variants, faster RCNN, and RGB-depth sensor. Smart Agricultural Technology, 101214. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525004459)]

  90. Guo, J., Zhang, B., Zhou, P., Xu, Y., Luo, S., Ji, J., Zhuo, Y., Xu, X., & Lin, L. (2026). A Digital Framework for Smart Greenhouse Tomato Cultivation. Smart Agricultural Technology, 101879. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526001036)]

<!-- ----------------- Revista de envio "Artificial Intelligence in Agriculture" -------------------- -->

  91. Das, A., Pathan, F., Jim, J. R., Kabir, M. M., & Mridha, M. F. (2025). Deep learning-based classification, detection, and segmentation of tomato leaf diseases: A state-of-the-art review. Artificial Intelligence in Agriculture, 15(2), 192-220. [[paper](https://www.sciencedirect.com/science/article/pii/S258972172500025X)]

  92. Cheng, T., Zhang, D., Zhang, G., Wang, T., Ren, W., Yuan, F., ... & Zhao, C. (2025). High-throughput phenotyping techniques for forage: Status, bottleneck, and challenges. Artificial Intelligence in Agriculture, 15(1), 98-115. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000029)]

  93. Gomez-Zamanillo, L., Bereciartua-Perez, A., Picon, A., Parra, L., Oldenbuerger, M., Navarra-Mestre, R., Kiukas, C., Eggers, T., & Echazarra, J. (2025). Digitalizing greenhouse trials: An automated approach for efficient and objective assessment of plant damage using deep learning. Artificial Intelligence in Agriculture, 15(2), 280-295. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000285)]

  94. Ram, B. G., Howatt, K., Mettler, J., & Sun, X. (2025). Addressing computation resource exhaustion associated with deep learning training of three-dimensional hyperspectral images using multiclass weed classification. Artificial Intelligence in Agriculture, 15(2), 131-146. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000248)]

  95. Yang, Y., Chen, L., Diao, Z., Gao, P., Zhang, B., & Zhao, C. (2026). Recent advances in crop pest detection, forecasting and early warning: A review. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000279)]

  96. Wiafe, E. K., Betitame, K., Ram, B. G., & Sun, X. (2025). Technical study on the efficiency and models of weed control methods using unmanned ground vehicles: A review. Artificial Intelligence in Agriculture, 15(4), 622-641. [[paper](https://www.sciencedirect.com/science/article/pii/S258972172500056X)]

  97. Ram, B. G., Howatt, K., Mettler, J., & Sun, X. (2025). Addressing computation resource exhaustion associated with deep learning training of three-dimensional hyperspectral images using multiclass weed classification. Artificial Intelligence in Agriculture, 15(2), 131-146. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721725000248)]

  
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

  8. Girshick, R., Donahue, J., Darrell, T., & Malik, J. (2014). _Rich feature hierarchies for accurate object detection and semantic segmentation (R-CNN)_. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 580-587). [[paper](https://openaccess.thecvf.com/content_cvpr_2014/html/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.html)].
  
  9. Girshick, R. (2015). _Fast r-cnn_. In Proceedings of the IEEE international conference on computer vision (pp. 1440-1448). [[paper](https://openaccess.thecvf.com/content_iccv_2015/html/Girshick_Fast_R-CNN_ICCV_2015_paper.html)].

  10. Ren, S., He, K., Girshick, R., & Sun, J. (2015). _Faster r-cnn: Towards real-time object detection with region proposal networks_. Advances in neural information processing systems, 28. [[paper](https://proceedings.neurips.cc/paper/2015/hash/14bfa6bb14875e45bba028a21ed38046-Abstract.html)].

  11. Redmon, J., Divvala, S., Girshick, R., & Farhadi, A. (2016). _You only look once: Unified, real-time object detection (YOLO)_. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 779-788). [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Redmon_You_Only_Look_CVPR_2016_paper.html)] 

  12. Liu, W., Anguelov, D., Erhan, D., Szegedy, C., Reed, S., Fu, C. Y., & Berg, A. C. (2016). SSD: Single shot multibox detector. In European conference on computer vision (pp. 21-37). Cham: Springer International Publishing. [[paper](https://link.springer.com/chapter/10.1007/978-3-319-46448-0_2)].

 13. Lin, T. Y., Goyal, P., Girshick, R., He, K., & Dollár, P. (2017). _Focal loss for dense object detection (RetinaNet)_. In Proceedings of the IEEE international conference on computer vision (pp. 2980-2988). [[paper](https://openaccess.thecvf.com/content_iccv_2017/html/Lin_Focal_Loss_for_ICCV_2017_paper.html)].

  14. Carion, N., Massa, F., Synnaeve, G., Usunier, N., Kirillov, A., & Zagoruyko, S. (2020). _End-to-end object detection with transformers (DETR)_. In European conference on computer vision (pp. 213-229). Cham: Springer International Publishing. [[paper](https://link.springer.com/chapter/10.1007/978-3-030-58452-8_13)].

  15. He, K., Gkioxari, G., Dollár, P., & Girshick, R. (2017). _Mask R-CNN_. In Proceedings of the IEEE international conference on computer vision (pp. 2961-2969). [[paper](https://openaccess.thecvf.com/content_iccv_2017/html/He_Mask_R-CNN_ICCV_2017_paper.html)].

</details>
<details>
  <summary><strong>2. Articles on greenhouse farming</strong></summary>

<!-- ----------------- R-CNN -------------------- -->

  100. Ghantasala, G. P., Dasari, S., Kumar, P. P., Suman, B., Kumar, A. R., Reddy, A., & Vidyullatha, P. (2026). DEEP LEARNING FRAMEWORK FOR MULTI-CLASS TOMATO LEAF DISEASE DETECTION FROM SEGMENTED IMAGES. Genetics and Molecular Research. [[paper](https://geneticsmr.com/index.php/gmr/article/view/1672)]

  102. Gao, Y., Yin, F., Hong, C., Chen, X., Deng, H., Liu, Y., Li, Y., & Yao, Q. (2025). Intelligent field monitoring system for cruciferous vegetable pests using yellow sticky board images and an improved Cascade R-CNN. Journal of Integrative Agriculture, 24(1), 220-234. [[paper](https://www.sciencedirect.com/science/article/pii/S2095311924002405)]

  103. Kavitha, K. (2025, October). Deep Learning-Driven Computer Vision Techniques for Advancing Smart Greenhouse Agriculture. In 2025 International Conference on Sustainable Communication Networks and Application (ICSCN) (pp. 24-30). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11308643)]

  104. Ahmad, A., Lloret, J., Parra, L., Sendra, S., & Di Gioia, F. (2026). Comparative Analysis of R-CNN and YOLOv8 Segmentation Features for Tomato Ripening Stage Classification and Quality Estimation. Horticulturae, 12(2), 127. [[paper](https://www.mdpi.com/2311-7524/12/2/127)]

  105. Xu, S. S. D., Wedajew, G. N., Ku, C. M., Chiu, C. C., & Yusuf, S. H. (2026). An Improved Sparse R-CNN Approach for Strawberry Disease Detection. Digital Signal Processing, 106212. [[paper](https://www.sciencedirect.com/science/article/pii/S1051200426003313)]

  106. Tamrakar, N., Paudel, B., Karki, S., Deb, N. C., Arulmozhi, E., Kook, J. H., ... & Kim, H. T. (2025). Peduncle Detection of Ripe Strawberry to Localize Picking Point Using DF-Mask R-CNN and Monocular Depth. IEEE Access. [[paper](https://ieeexplore.ieee.org/abstract/document/10976681)]

  107. Donohoe, S. P., Alege, F. P., & Delhom, C. D. (2026). Toward multi-class detection and localization of contamination in cotton fields: Comparing EfficientDet, Faster R-CNN ResNet50, SSD MobileNet V2, and YOLOv11. Computers and Electronics in Agriculture, 247, 111690. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169926002851)]

  108. Huang, L., Li, H., Yang, H., Fu, C., Zhang, Y., & Chang, F. (2026). Research on real-time target detection algorithm for strawberry-picking robot based on improved YOLOv5. Journal of Food Measurement and Characterization, 20(1), 847-868. [[paper](https://link.springer.com/article/10.1007/s11694-025-03703-x)]

  109. Rajagopal, S., & Venkatasubramaniam, K. (2025, February). Freshness Grading of Tomato Using Fast R-CNN. In 2025 International Conference on Innovative Trends in Information Technology (ICITIIT) (pp. 1-6). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11041523)]

  110. Amir, A., Giri, S., Giri, S., & Butt, M. (2025). An advanced approach to tomato apex head thickness measurement using lightweight YOLO variants, faster RCNN, and RGB-depth sensor. Smart Agricultural Technology, 101214. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525004459)]

  111. Xu, S. S. D., Wedajew, G. N., Ku, C. M., Chiu, C. C., & Yusuf, S. H. (2026). An Improved Sparse R-CNN Approach for Strawberry Disease Detection. Digital Signal Processing, 106212. [[paper](https://www.sciencedirect.com/science/article/pii/S1051200426003313)]

<!-- ----------------- Fast R-CNN -------------------- -->

  112. Bashir, A., Wang, Y., Ojo, M. O., & Zahid, A. (2025). A Vision System for Occluded Cutting Point Localization in Robotic Harvesting of Greenhouse Lettuce. IEEE Transactions on AgriFood Electronics. [[paper](https://ieeexplore.ieee.org/abstract/document/11219194)]

  113. Nan, Y., Zhang, H., Zheng, J., & Yang, K. (2025). Pitaya detection using an improved lightweight Faster R-CNN based on MobileNetV3 in densely planted pitaya orchards. Journal of Agricultural Engineering, 56(4). [[paper](https://www.agroengineering.org/jae/article/view/1886)]

  114. Bilal, M., Shah, A. A., Abbas, S., & Khan, M. A. (2025). High‐Performance Deep Learning for Instant Pest and Disease Detection in Precision Agriculture. Food Science & Nutrition, 13(9), e70963. [[paper](https://onlinelibrary.wiley.com/doi/full/10.1002/fsn3.70963)]

  115. Alfred, R., Leo, J., & Kaijage, S. F. (2025). Detectron2-enhanced mask R-CNN for precise instance segmentation of rice blast disease in Tanzania: Supporting timely intervention and data-driven severity assessment. Smart Agricultural Technology, 101301. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525005325)]

  116. Daraghmi, Y. A., Naser, W., Daraghmi, E. Y., & Fouchal, H. (2025). Drone-Assisted Plant Stress Detection Using Deep Learning: A Comparative Study of YOLOv8, RetinaNet, and Faster R-CNN. AgriEngineering, 7(8), 257. [[paper](https://www.mdpi.com/2624-7402/7/8/257)]

<!-- ----------------- Faster R-CNN -------------------- -->

  117. Arik, K., & Ağgül, B. (2026). Reproducible Benchmarking of Tomato Detection in Greenhouse: Comparing Attention-Augmented and Baseline Detectors. AgriEngineering. [[paper](https://www.researchgate.net/profile/Burak-Agguel/publication/408501666_Reproducible_Benchmarking_of_Tomato_Detection_in_Greenhouse_Comparing_Attention-Augmented_and_Baseline_Detectors/links/6a4ce65a1681584dea2d5b7c/Reproducible-Benchmarking-of-Tomato-Detection-in-Greenhouse-Comparing-Attention-Augmented-and-Baseline-Detectors.pdf)]

  118. Restrepo-Arias, J. F., Montoya-Castaño, M. J., Moreno-De La Espriella, M. F., & Branch-Bedoya, J. W. (2025). An Application of Deep Learning Models for the Detection of Cocoa Pods at Different Ripening Stages: An Approach with Faster R-CNN and Mask R-CNN. Computation, 13(7), 159. [[paper](https://www.mdpi.com/2079-3197/13/7/159)]

<!-- ----------------- YOLO -------------------- -->

  119. Zhang, J., Guo, J., Zhao, C., Li, W., & Yuan, T. (2026). LeafRemoval-YOLO-K: A hybrid visual recognition network for stem-petiole segmentation and cutting point localization in tomato plants. Computers and Electronics in Agriculture, 246, 111485. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169926000803)]

  120. Ali, A. S., Narayan, J., Shukla, A., & Shree, R. (2026). Enhancing precision farming with YOLO models for real-time growth detection of basil plants. Environmental Sustainability, 1-11. [[paper](https://link.springer.com/article/10.1007/s42398-026-00454-3)]

  121. Jia, W., Lin, S., Wei, Z., Tian, B., Meng, X., & Zhang, Y. (2026). Research on Intelligent Identification Method for Nitrogen Content in Greenhouse Cucumber Leaves Integrating YOLOv11n Segmentation and Machine Learning. Agriculture, 16(13), 1376. [[paper](https://www.mdpi.com/2077-0472/16/13/1376)]

  122. Singh, R., Kaur, M., Alirezaee, S., & Hussain, I. (2026). YOLO26-RipeLoc Lite: A lightweight architecture for tomato ripeness detection and picking point localization in greenhouse robotic harvesting. arXiv preprint arXiv:2605.27129. [[paper](https://arxiv.org/abs/2605.27129)]

  123. Moni, M. A., Chaitee, A. S., Tanvir, K. M., Rahman, M. A., Banik, S., & Habib, M. T. (2026, January). Machine vision-based pepper breed classification Using yolov10 and transfer learning models. In 2026 6th International Conference on Image Processing and Capsule Networks (ICIPCN) (pp. 544-549). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11438307)] 
  
  124. Liu, Y., Wang, H., Wu, H., Xu, M., Yuan, G., Yan, R., & Zou, J. A Hybrid YOLO–EfficientNet Architecture for Multi-Task Recognition of Pests and Diseases in Greenhouse Crops. Available at SSRN 5939218. [[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5939218)]

  125. Zhao, B., Zheng, D., Yang, C., Jomartova, S., Sonza, R., Mansurova, M., & Liu, H. (2026). DTBi-YOLOv8-seg: A dual-backbone deep learning framework for automated tomato ripeness detection in greenhouse environments. Scientia Horticulturae, 361, 114855. [[paper](https://www.sciencedirect.com/science/article/pii/S0304423826002487)]

  126. Kuang, M., Wang, Y., Li, X., Zou, X., Liu, D., Xiang, Y., Bader, S., Cie, F., Zhang, Y., & Li, X. (2026). GCP-YOLO: high-precision detection of tiny chili flowers in complex greenhouse scenes. Frontiers in Plant Science, 17, 1879612. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1879612/full)]

  127. Cañadas-Aránega, F., Moreno, J. C., Blanco-Claraco, J. L., Giménez, A., Rodríguez, F., & Sánchez-Hermosilla, J. (2024). Autonomous collaborative mobile robot for greenhouses: Design, development, and validation tests. Smart Agricultural Technology, 9, 100606. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375524002119)]

  128. Su, Y., Zhang, P., Li, H., Kang, F., Zhao, P., & Wang, L. (2026). YOLO-FLBM: a lightweight and high-performance model for tomato ripeness detection in complex greenhouse environments. Frontiers in Plant Science, 17, 1824558. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1824558/full)]

  129. Chen, M., Ma, K., Geng, X., Hu, D., Fei, S., He, S., Du, X., Shu, S., Zhang, R., & Ma, Y. (2026). MS-R outperforms RGB: Lightweight CYOLO-BiCNet enables efficient detection and storage optimization of cotton flowers. Precision Agriculture, 27(4), 92. [[paper](https://link.springer.com/article/10.1007/s11119-026-10396-9)]

  130. Zhang, X., Zhang, G., Wang, J., Yang, J., Ge, Q., Zhao, R., & Yang, W. (2025). Efficient instance segmentation for strawberry in greenhouses using YOLOv8n-MCP on edge devices. Information Processing in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2214317325000344)]

  131. Carbone, G., Gurtatta, A. S., & Malyshev, D. (2025). Development and implementation of a hybrid visual prediction algorithm for robotic smart tomato harvesting. Engineering Applications of Artificial Intelligence, 161, 112261. [[paper](https://www.sciencedirect.com/science/article/pii/S0952197625022699)]

  132. Weng, W., Lai, Z., Cui, Z., Chen, Z., Chen, H., Lin, T., Wang, J., Zheng, S., & Chen, G. (2025). GCD-YOLO: A deep learning network for accurate tomato fruit stalks identification in unstructured environments. Smart Agricultural Technology, 101465. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525006963)]

  133. Zoubek, T., Bumbálek, R., Ufitikirezi, J. D. D. M., Strob, M., Filip, M., Špalek, F., Hermanek, A., & Bartoš, P. (2025). Advancing precision agriculture with computer vision: A comparative study of YOLO models for weed and crop recognition. Crop Protection, 190, 107076. [[paper](https://www.sciencedirect.com/science/article/pii/S0261219424005040)]

  134. Liu, X., Teng, W., Yu, H., Yao, Z., Wang, C., Peng, Y., Han, X., & Liu, J. (2025). GAE-YOLO: a lightweight multimodal detection framework for tomato smart agriculture with edge computing. Frontiers in Plant Science, 16, 1712432. [[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2025.1712432/full)]

  135. Cañadas-Aránega, F., Muñoz, M., Moreno, J. C., & Blanco-Claraco, J. L. (2026). Integrated cloud-based architecture for robot-robot and human-robot collaboration using ROS 2-MQTT in Mediterranean Greenhouses. arXiv preprint arXiv:2606.22682. [[paper](https://arxiv.org/abs/2606.22682)]

  136. Cañadas-Aránega, F., Mañas-Álvarez, F. J., Moreno, J. C., & Blanco-Claraco, J. L. (2026). A ROS2 Benchmarking Framework for Hierarchical Control Strategies in Mobile Robots for Mediterranean Greenhouses. arXiv preprint arXiv:2602.15162. [[paper](https://arxiv.org/abs/2602.15162)]

  137. Aranega, F. C., Border, R., Claraco, J. L. B., & Úbeda, J. C. M. (2025). NBV Planning for the detection of hidden tomatoes in greenhouses with AgriSEE. Jornadas de Automática, (46). [[paper](https://revistas.udc.es/index.php/JA_CEA/article/view/12234)]

<!-- ----------------- SSD -------------------- -->

  138. Singh, R., Gadade, A. M., & Hussain, I. (2025). Robust real-time strawberry maturity detection using UAV-mounted deep learning for precision agriculture. BMC Plant Biology, 25(1), 1367. [[paper](https://link.springer.com/article/10.1186/s12870-025-07246-7)]

  139. Yuan, M., Wang, D., Lin, J., Yang, S., & Ning, J. (2025). SSP-MambaNet: An automated system for detection and counting of missing seedlings in glass greenhouse-grown virus-free strawberry. Plant Phenomics, 7(2), 100043. [[paper](https://www.sciencedirect.com/science/article/pii/S2643651525000494)]

  140. Kamat, P., Gite, S., Chandekar, H., Dlima, L., & Pradhan, B. (2025). Multi-class fruit ripeness detection using YOLO and SSD object detection models. Discover Applied Sciences, 7(9), 931. [[paper](https://link.springer.com/article/10.1007/s42452-025-07617-7)]

  141. Tarasiuk, K., Mystkowski, A., Ostaszewski, M., Kwaśniewski, K. K., Majka, A., & Czarnigowski, J. (2026). Agriculture surrounding monitoring and object identification based on optimized you only look once and single shot multibox detector setups using combined vision and thermal images. Scientific Reports. [[paper](https://www.nature.com/articles/s41598-026-36181-2)]

  142. Rezgui, J., & Ly, W. (2025, October). AI-based Plant Disease Detection: Development and Deployment of YOLO Models for Agricultural Innovation. In 2025 International Symposium on Networks, Computers and Communications (ISNCC) (pp. 1-6). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11250413)]


<!-- ----------------- RetineNet -------------------- -->

 143. Ibrahim, E., Hamdy, M., El-Fishawy, A. S., A Eldolil, S., & El-Hoseny, H. (2025). Comprehensive survey on residual neural networks improvements in agricultural applications. Neural Computing and Applications, 1-42. [[paper](https://link.springer.com/article/10.1007/s00521-025-11682-9)]

 144. Ruhad, F. M., Fahim, M., Hossain, M. S., Monir, M. F., Islam, A., & Amin, M. A. (2025). Beyond Classification: Benchmarking Object Detection Models for Efficient Tomato Leaf Disease Identification on a Real-World Dataset. Smart Agricultural Technology, 101336. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375525005672)]

 145. Arif, T., Riaz, S., Shafiq, Z., & Khan, G. M. (2025, June). Computer Vision-Based Plant Growth Stages Analysis for Optimizing Crop Yield. In IFIP International Conference on Artificial Intelligence Applications and Innovations (pp. 283-296). Cham: Springer Nature Switzerland. [[paper](https://link.springer.com/chapter/10.1007/978-3-031-97313-0_22)]

 146. Khan, Z., Liu, H., Shen, Y., Yang, Z., Zhang, L., & Yang, F. (2025). Optimizing precision agriculture: A real-time detection approach for grape vineyard unhealthy leaves using deep learning improved YOLOv7 with feature extraction capabilities. Computers and Electronics in Agriculture, 231, 109969. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925000754)]

 147. Yilmaz, E., Bocekci, S. C., Safak, C., & Yildiz, K. (2025). Advancements in smart agriculture: A systematic literature review on state‐of‐the‐art plant disease detection with computer vision. IET Computer Vision, 19(1), e70004. [[paper](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cvi2.70004)]

 148. Li, X., Lin, Z., Liang, Z., Wang, G., & Zou, X. (2026). Research on tomato object all-day detection and occlusion scenario analysis methods. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000498)]

<!-- ----------------- DETR -------------------- -->

  149. Fan, X. R., Cai, D., Wang, X., & Kang, M. (2026). SGS-DETR: A Lightweight Transformer for Real-Time Strawberry Growth Stage Detection in Smart Agriculture Systems. Smart Agricultural Technology, 102118. [[paper](https://www.sciencedirect.com/science/article/pii/S2772375526003382)]

  150. Sapkota, R., Cheppally, R. H., Sharda, A., & Karkee, M. (2025). Rf-detr object detection vs yolov12: A study of transformer-based and cnn-based architectures for single-class and multi-class greenfruit detection in complex orchard environments under label ambiguity. arXiv preprint arXiv:2504.13099. [[paper](https://arxiv.org/abs/2504.13099)]

  151. Shuai, Y., Shi, J., Li, Y., Zhou, S., Zhang, L., & Mu, J. (2025). YOLO-SW: A Real-Time Weed Detection Model for Soybean Fields Using Swin Transformer and RT-DETR. Agronomy, 15(7), 1712. [[paper](https://www.mdpi.com/2073-4395/15/7/1712)]

  152. Kuang, M., Li, X., Wu, B., Liu, D., Xiang, Y., Liu, F., ... & Li, X. (2026). CF-DETR: a robust transformer-based framework for small-scale chili flower detection in industrial chili production systems. Frontiers in Plant Science, 17, 1824412.[[paper](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2026.1824412/full)]

  153. Tang, Z., Fang, L., Sun, S., Gong, Y., & Li, Q. (2025). ML-DETR: Multiscale-Lite Detection Transformer for identification of mature cherry tomatoes. IEEE Transactions on Instrumentation and Measurement. [[paper](https://ieeexplore.ieee.org/abstract/document/11156100)]

  154. Rong, Z., Wang, G., Sun, Q., Sun, J., Li, R., Xu, Y., & Yang, L. (2025). A Lightweight and Efficient Model for Safety Protection Equipment Detection Based on Improved RT-DETR. IEEE Access, 14, 5510-5521. [[paper](https://ieeexplore.ieee.org/abstract/document/11230344)]

  155. Guo, J., Liu, Z., Zhang, X., Wang, R., Ma, X., & Li, W. (2026). SlimTom-DETR: A Lightweight and Real-Time Tomato Detection Model for Plant Factories With Complex Lighting Conditions. IEEE Access. [[paper](https://ieeexplore.ieee.org/abstract/document/11428165)]

  156. Karahan, F. E., Celikel, T., & Ozcan, G. (2026). An End-to-End Deep Learning Framework for Crop Type and Phenological Stage Identification. IEEE Access. [[paper](https://ieeexplore.ieee.org/abstract/document/11577148)]

  157. Xu, J., Zhang, X., Wang, X., Song, H., & Wang, Y. (2026). ELSF-DETR: an efficient lightweight network for detecting strawberry flowers pollination status in non-structured greenhouse environments. Computers and Electronics in Agriculture, 243, 111398. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925015042)]

  158. Ren, W., Qian, T., Li, G., & Li, X. (2025, March). RT-DETR-MC: A Novel Fusion of Multi-Scale Features and Gating Mechanism for Lettuce Disease Detection. In Proceedings of the 2025 6th International Conference on Computer Information and Big Data Applications (pp. 196-202). [[paper](https://dl.acm.org/doi/full/10.1145/3746709.3746745)]

<!-- ----------------- Mask R-CNN -------------------- -->

  159. Lyu, D. Y., Li, X. C., Wang, W. D., Wu, B. R., Shi, S. H., & Shen, H. Y. (2025). A melon fruit diameter measurement method based on an improved Mask R-CNN. [[paper](https://api.inmateh.eu/public/uploads/77-09-N1707-Deyang-LYUe919c8af-e304-45eb-aa86-023ae6e02762.pdf)]

  160. Chen, Y., Liu, H., Wang, L., Chen, C., Li, S., Zhong, B., Qiao, J., Ye, R., & Li, T. (2025). Research on Instance Segmentation Algorithm for Caged Chickens in Infrared Images Based on Improved Mask R-CNN. Sensors, 25(19), 6237. [[paper](https://www.mdpi.com/1424-8220/25/19/6237)]

  161. Montilla, J. C. A., Aniceto, M. J. C., & Caya, M. V. C. (2025, August). Eggplant Size Acquisition using Mask R-CNN. In 2025 IEEE International Conference on Artificial Intelligence in Engineering and Technology (IICAIET) (pp. 210-214). IEEE. [[paper](https://ieeexplore.ieee.org/abstract/document/11265158)]

  162. Grbović, Ž., Panić, M., Filipović, V., Brdar, S., De Villiers, H., Mensink, M., & Chauhan, A. (2025). An efficient encoding spectral information in hyperspectral images for transfer learning of Mask R-CNN for instance segmentation of tomato sepals. IEEE Access. [[paper](https://ieeexplore.ieee.org/abstract/document/11000115)]

  163. Sahu, K., Tiwari, S., Singh, M. K., Pahareeya, J., Shakya, H. K., Kumar, G., & Selvarajan, S. (2025). Plant disease detection using a hybrid dilated CNN with attention mechanisms and optimized mask RCNN segmentation. Scientific Reports. [[paper](https://www.nature.com/articles/s41598-025-26192-w)]

  164. Jiang, R., Guo, T., Liu, G., & Jia, W. (2026). GHD Net: Overlapping Green Tomato Instance Segmentation Under Facility Environments. IEEE Transactions on AgriFood Electronics. [[paper](https://ieeexplore.ieee.org/abstract/document/11390666)]

  165. Sun, P., & Wu, W. (2026). Improved mask R-CNN-based instance segmentation model for coal gangue. International Journal of Coal Preparation and Utilization, 46(6), 1601-1619. [[paper](https://www.tandfonline.com/doi/full/10.1080/19392699.2025.2505448?scroll=top&needAccess=true)]

  166. Deepika, P., & Arthi, B. (2026). Enhancing the severity classification of tomato plant epidemic pathogens using adaptive segmentation of mask RCNN and multiscale recurrent MobileNet. Scientific Reports. [[paper](https://www.nature.com/articles/s41598-026-42675-w)]

  167. Wang, X., Burusa, A. K., Rapado-Rincón, D., Versmissen, T. A., van Henten, E. J., & Kootstra, G. (2025). Multiple object tracking with multi-view active vision to effectively find plant nodes in a cluttered tomato greenhouse. Computers and Electronics in Agriculture, 234, 110266. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169925003722)]


</details>
</details>


<!-- ----------------- Revista de envio "Artificial Intelligence in Agriculture" -------------------- -->

  168. Gao, L., Li, Y., Wu, J., Feng, Q., Chen, L., Shen, C., ... & Zhao, C. (2026). YOLO-GPP: End-to-end prediction of the grasp position and pose on tomato peduncle for robotic harvesting. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000206)]

  169. Gao, R., Cao, W., Zhang, Z., Cheng, X., Ji, Z., Kong, Q., & Su, Z. (2026). YOLOSc-SAM: An acceptable extraction method for farmland regions in remote sensing images using SAM. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000176)]

 200. Afzaal, H., Farooque, A. A., Randhawa, G. S., Schumann, A. W., Krouglicof, N., Gill, Y. S., & Zaman, Q. U. (2026). Zero-shot crop segmentation via 3D depth-aware vision pipeline using unsupervised clustering. Artificial Intelligence in Agriculture. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721726000462)]

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

 7. Cañadas-Aránega, F., Moreno, J. C., & Blanco-Claraco, J. L. (2026). GreenSeg: Ground Segmentation Algorithm for Agricultural Robots in Mediterranean Greenhouses using RGB-D Point Clouds. arXiv preprint arXiv:2605.25279. [[paper](https://arxiv.org/abs/2605.25279)]

</details>

<details>
  <summary><strong>2. Articles on greenhouse farming</strong></summary>





2. Semantic Segmentation Layer [[paper](https://github.com/kiwicampus/semantic_segmentation_layer)]: A custom nav2 costmap layer plugin inspired on stvl, that integrates semantic segmentation data into the navigation costmap. INCLUDE A NAV2 IMPLEMENTATION.
<div align="center">
  <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/11f2e4c5-60df-4b37-9eda-10eb8547b120" />
</div>

3. Pointclouds GroundSegmentation Intel RealSense [[paper](https://github.com/open-edge-platform/edge-ai-suites/tree/main/robotics-ai-suite/components/groundfloor/pointcloud_groundfloor_segmentation)]: This repository contains a realization of an efficient groundfloor segmentation approach for 3D pointclouds. The application comes with three default use cases: standalone use with RealSense camera (or other depth cameras), integration with the Wandering demo on Aaeon robot, and direct use with 3D pointcloud input.
<div align="center">
  <img width="470" height="270" alt="image" src="https://github.com/user-attachments/assets/07c7ba4f-6241-48e4-b74d-a2368ee5c689" />
</div>


</details>
</details>

<!-- ---------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------- Generative ------------------------------------------------------------- -->
<!-- ---------------------------------------------------------------------------------------------------------------------------- -->

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

  1. Rajakannu, A., Vishnupriyan, S., & Abubacker, K. M. (2026). CNN-Assisted Growth Monitoring and Stress Management of Cucumber in Semi-Transparent PV Greenhouses for Agrivoltaics. [[paper](https://www.sciencedirect.com/science/article/pii/S016816992500688X)]


</details>

</details>









## LiDAR algorithms for robotics
<div align="center">
  <img width="500" height="432" alt="image" src="https://github.com/user-attachments/assets/55cb1db4-f464-4f9b-a0f3-fdebc508851b" />
</div>

1. Sánchez-Molina, J. A., Rodríguez, F., Moreno, J. C., Sánchez-Hermosilla, J., & Giménez, A. (2024). Robotics in greenhouses. Scoping review. Computers and Electronics in Agriculture, 219, 108750. [[paper](https://www.sciencedirect.com/science/article/pii/S0168169924001418)]

2. Xu, J., Gu, B., & Tian, G. (2022). Review of agricultural IoT technology. Artificial Intelligence in Agriculture, 6, 10-22. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721722000010)]

3. Hossain, M. E., Kabir, M. A., Zheng, L., Swain, D. L., McGrath, S., & Medway, J. (2022). A systematic review of machine learning techniques for cattle identification: Datasets, methods and future directions. Artificial Intelligence in Agriculture, 6, 138-155. [[paper](https://www.sciencedirect.com/science/article/pii/S2589721722000125)]



5. Cañadas-Aránega, F., Blanco-Claraco, J. L., Moreno, J. C., & Rodriguez-Diaz, F. (2024). Multimodal mobile robotic dataset for a typical mediterranean greenhouse: The greenbot dataset. Sensors, 24(6), 1874. [[paper](https://www.mdpi.com/1424-8220/24/6/1874)]

<details>
<summary>Vision algorithms for robotics</summary>


1. Ground Segmentation ROS 2 Node (GSeg3D) [[paper](https://github.com/dfki-ric/ground_segmentation_ros2?tab=readme-ov-file)]: This package implements a ROS 2 node that wraps the GSeg3D ground segmentation algorithm and exposes it as a real-time perception component for robotic systems. The node subscribes to LiDAR point clouds (optionally synchronized with IMU data), performs two-phase grid-based ground segmentation, and publishes ground and obstacle point clouds for downstream navigation and perception modules. INCLUDE A NAV2 IMPLEMENTATION.
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




