# Bibliography on Object Mapping

## Object Mapping
|   | Year | Sensor | Estimation | Geometry | Association | Map | Feature | Link |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
SLAM ++ | 2013 | RGBD | Match  | Object model | ICP | Point cloud + Object model | With SLAM | [[a1]](#a1-slam-simultaneous-localisation-and-mapping-at-the-level-of-objects)
SLAM with Object Discovery | 2014 | RGBD | Cluster | point cloud | IoU/ JCBB | Point cloud  | SLAM for object | [[a2]](#a2-slam-with-object-discovery-modeling-and-mapping)
Meaningful Map | 2017 | RGBD | Cluster | Point cloud | Euclidean distance | Point cloud  | Extract object from PCL | [[a3]](#a3-meaningful-maps-with-object-oriented-semantic-mapping)
Efficient  | 2018 | RGBD | Cluster  | Point cloud | IoU | Point cloud | Yolov2 efficient | [[a4]](#a4-efficient-object-oriented-semantic-mapping-with-object-detector)
Voxblox | 2017 | RGBD |  |  |  | ESDF/ TSDF | Semantic Mapping | [[a5]](#a5-voxblox-incremental-3d-euclidean-signed-distance-fields-for-on-board-mav-planning)
Voxblox ++ | 2019 | RGBD | Cluster | Voxel | IoU | ESDF/ TSDF | Add objects to voxblox | [[a6]](#a6-voxblox-volumetric-instance-aware-semantic-mapping-and-3d-object-discovery)
Voxblox fusion | 2022 | RGBD | Cluster | Voxel/TSDF | Label fusion | ESDF/ TSDF | Add objects to voxblox | [[a7]](#a7-volumetric-instance-level-semantic-mapping-via-multi-view-2d-to-3d-label-diffusion)
Incremental Instance 3D Mapping | 2020 | RGBD | Cluster | Point cloud /TSDF | Voxel based Bayesian  | ESDF/ TSDF | Add objects to voxblox | [[a8]](#a8-incremental-instance-oriented-3d-semantic-mapping-via-rgb-d-cameras-for-unknown-indoor-scene)
Hybrid Map | 2019 | RGBD | Cluster | Point cloud | IoU | Octomap | Project octomap to 2D map | [[a9]](#a9-hypermap-mapping-framework-and-its-application-to-autonomous-semantic-exploration)
Hypermap | 2019 | RGBD | Cluster | Point cloud | IoU | Hypermap occupancy | Multi-map integration | [[a10]](#a10-hypermap-mapping-framework-and-its-application-to-autonomous-semantic-exploration)
Online Object Updating | 2020 | RGBD | Cluster | projected polygon  | IoU/ H-dist/ distance | Hypermap occupancy  | Project object to 2D map | [[a11]](#a11-online-object-oriented-semantic-mapping-and-map-updating)
Augmented Object | 2021 | RGBD | Cluster | Geometry | Shape and model match | Hypermap / occupancy | Multi-map integration | [[a12]](#a12-augmented-environment-representations-with-complete-object-models)
Contextual Temporal  | 2018 | RGBD | Match  | Object model | Conditional Random Field | Hypermap / occupancy | belief estimation, CRF  | [[a13]](#a13-semantic-mapping-with-simultaneous-object-detection-and-localization)
Logistic Mapping | 2017 | RGBD | Project | Projected lines | Bayesian update | Hypermap / occupancy | RGBD with objects -> laser scan with label | [[a14]](#a14-online-semantic-mapping-of-logistic-environments-using-rgb-d-cameras)



## Reference

### [a1] [SLAM++: Simultaneous Localisation and Mapping at the Level of Objects ](http://openaccess.thecvf.com/content_cvpr_2013/html/Salas-Moreno_SLAM_Simultaneous_Localisation_2013_CVPR_paper.html)

### [a2] [SLAM with Object Discovery, Modeling and Mapping ](https://ieeexplore.ieee.org/abstract/document/6942683)

### [a3] [Meaningful Maps With Object-Oriented Semantic Mapping ](https://ieeexplore.ieee.org/abstract/document/8206392)

### [a4] [Efficient Object-Oriented Semantic Mapping With Object Detector](https://ieeexplore.ieee.org/abstract/document/8579143)

### [a5] [Voxblox: Incremental 3D Euclidean Signed Distance Fields for On-Board MAV Planning ](https://ieeexplore.ieee.org/abstract/document/8202315)

### [a6] [Voxblox++: Volumetric Instance-Aware Semantic Mapping and 3D Object Discovery ](https://ieeexplore.ieee.org/abstract/document/8741085)

### [a7] [Volumetric Instance-Level Semantic Mapping Via Multi-View 2D-to-3D Label Diffusion ](https://ieeexplore.ieee.org/abstract/document/9695168)

### [a8] [Incremental Instance-Oriented 3D Semantic Mapping via RGB-D Cameras for Unknown Indoor Scene ](https://www.hindawi.com/journals/ddns/2020/2528954/)

### [a9] [Object-Aware Hybrid Map for Indoor Robot Visual Semantic Navigation](https://ieeexplore.ieee.org/abstract/document/8961495/)

### [a10] [Hypermap Mapping Framework and its Application to Autonomous Semantic Exploration ](https://ieeexplore.ieee.org/abstract/document/9235231)

### [a11] [Online Object-Oriented Semantic Mapping and Map Updating](https://ieeexplore.ieee.org/abstract/document/9568817/)

### [a12] [Augmented Environment Representations with Complete Object Models ](https://ieeexplore.ieee.org/abstract/document/9900516)

### [a13] [Semantic Mapping with Simultaneous Object Detection and Localization ](https://ieeexplore.ieee.org/abstract/document/8594205)

### [a14] [Online semantic mapping of logistic environments using RGB-D cameras ](https://journals.sagepub.com/doi/full/10.1177/1729881417720781)

### [a3] [YOLOv2](https://openaccess.thecvf.com/content_cvpr_2017/html/Redmon_YOLO9000_Better_Faster_CVPR_2017_paper.html)
### [a3] [YOLOv2](https://openaccess.thecvf.com/content_cvpr_2017/html/Redmon_YOLO9000_Better_Faster_CVPR_2017_paper.html)
