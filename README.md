# Hi, I'm Omar Elalaily

Robotics and computer vision engineer finishing my **M.S. in Mechanical Engineering at the University of North Dakota (December 2026)**. My thesis is an autonomous ground vehicle (UGV) that drives between GPS waypoints through pedestrian areas, using ROS 2, a LiDAR, a stereo camera, GNSS and an IMU, with perception models running on NVIDIA Jetson. Before graduate school I spent four years as a project engineer on infrastructure projects.

**Focus:** robot perception, autonomous navigation, deploying models on real hardware.

---

### Projects

| Project | What it does | Key result |
| --- | --- | --- |
| [UGV Sidewalk & Crosswalk Segmentation](https://github.com/OmarElalaily/UGV-Sidewalk-Crosswalk-Segmentation) | DeepLabV3+ / ResNet-50 drivable-area segmentation on Mapillary Vistas (first version; final UGV uses pretrained Mask2Former) | 0.98 pixel accuracy, 0.65 mIoU |
| [UGV Pedestrian Signal Detection](https://github.com/OmarElalaily/UGV-Pedestrian-Traffic-Sign-Detection) | YOLOv8 WALK / DON'T WALK detection for crosswalk decisions; trained from scratch on 4 GPUs | test mAP@50 0.98 |
| [UGV Vehicle Traffic Light Detection](https://github.com/OmarElalaily/UGV-Vehicle-Traffic_light) | YOLOv8 red / yellow / green / off on the Bosch Small Traffic Lights dataset | mAP@50 0.75, precision 0.89 |
| [UGV Traffic Sign Detection](https://github.com/OmarElalaily/UGV-Traffic-Signs-Detection) | YOLOv8 on 226 US sign classes remapped from Mapillary | long-tail 226-class benchmark |
| [Autonomous Indoor Inventory Verification](https://github.com/OmarElalaily/Autonomous-Indoor-Inventory-Verification) | ROS 2 Jazzy + Nav2 robot that patrols shelves and audits products with ArUco markers | end-to-end autonomous audit with CSV report |
| [Feature Extraction Benchmark](https://github.com/OmarElalaily/Feature-Extraction-Benchmark-SIFT-ORB-ResNet50) | SIFT vs ORB vs ResNet-50 features with Logistic Regression / XGBoost on 14,306 images | 98.8% accuracy (ResNet-50); ORB 36x faster |

### Skills
**Robotics:** ROS 2, Nav2, AMCL, TF/URDF, rosbag, sensor integration (LiDAR, ZED 2 stereo, GNSS, IMU), NVIDIA Jetson  
**ML / CV:** PyTorch, Ultralytics YOLO, segmentation_models_pytorch, Keras/TensorFlow, OpenCV, XGBoost, scikit-learn, multi-GPU training  
**Languages:** Python, C++  
**Engineering:** robot kinematics (FK/IK, Jacobians, trajectories), field testing and root-cause analysis, Lean Six Sigma Yellow Belt

### Contact
omar.elalaily94@gmail.com · [LinkedIn](https://www.linkedin.com/in/omar-elalaily-785b53189)
