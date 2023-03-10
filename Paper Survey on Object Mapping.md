# Bibliography on Object Mapping

## Literature review of semantic mapping systems.

|    | Sensor | Map Type | Objects | Features | Link |
|:---|:---|:---|:---|:---|:---| 
\cite{grisetti2007improved} | laser scanner | grid map | | 2D grid |[[b01]](#b01-improved-techniques-for-grid-mapping-with-rao-blackwellized-particle-filters)|
\cite{leigh2015person} | laser scanner | grid map | labelled points | hard-coded features | [[b02]](#b02-person-tracking-and-following-with-2d-laser-scanners)|
\cite{himstedt2017online} | RGB-D | grid map | visual objects | top-to-down projection | [[b03]](#b03-online-semantic-mapping-of-logistic-environments-using-rgb-d-cameras)|
\cite{pang2019efficient} | laser scanner, RGB | grid map | labelled points | back-projection | [[b04]](#b04-an-efficient-3d-pedestrian-detector-with-calibrated-rgb-camera-and-3d-lidar)|
\cite{zaenker2020hypermap} | laser scanner, RGB-D | grid map | polygon | multiple layers | [[b05]](#b05-hypermap-mapping-framework-and-its-application-to-autonomous-semantic-exploration)|
\cite{sivananda2022augmented} | laser scanner, RGB-D | grid map | object model | multiple layers | [[b06]](#b06-augmented-environment-representations-with-complete-object-models)|
\cite{newcombe2011kinectfusion} | RGB-D | point cloud map |  | dense map | [[b07]](#b07-kinectfusion-real-time-dense-surface-mapping-and-tracking)|
\cite{pham2015hierarchical} | RGB-D | point cloud map | object point | features and contextual information | [[b08]](#b08-hierarchical-higher-order-regression-forest-fields-an-application-to-3d-indoor-scene-labelling)|
\cite{sunderhauf2017meaningful} | RGB-D | point cloud map | object point | object segmentation | [[b09]](#b09-meaningful-maps-with-object-oriented-semantic-mapping))|
\cite{mccormac2017semanticfusion} | RGB-D | point cloud map | object point | object segmentation | [[b10]](#b10-semanticfusion-dense-3d-semantic-mapping-with-convolutional-neural-networks)|
\cite{hornung2013octomap} | RGB-D | voxel map |  | 3D occupancy octomap | [[b11]](#b11-octomap-an-efficient-probabilistic-3d-mapping-framework-based-on-octrees)|
\cite{oleynikova2017voxblox} | RGB-D | voxel map |  | 3D TSDF map | [[b12]](#b12-voxblox-incremental-3d-euclidean-signed-distance-fields-for-on-board-mav-planning)|
\cite{rosinol2020kimera} | RGB-D | voxel map | object mesh | semantic segmentation | [[b13]](#b13-kimera-an-open-source-library-for-real-time-metric-semantic-localization-and-mapping)|
\cite{pham2019real} | RGB-D | voxel map | object voxel | super-voxel clustering | [[b14]](#b14-real-time-progressive-3d-semantic-segmentation-for-indoor-scenes)|
\cite{grinvald2019volumetric} | RGB-D | voxel map | object voxel | volumetric map | [[b15]](#b15-volumetric-instance-aware-semantic-mapping-and-3d-object-discovery)|
\cite{li2020incremental} | RGB-D | voxel map | object voxel | Gaussian mixture model | [[b16]](#b16-incremental-instance-oriented-3d-semantic-mapping-via-rgb-d-cameras-for-unknown-indoor-scene)|
\cite{mascaro2022volumetric} | RGB-D | voxel map | object voxel | label fusion | [[b17]](#b17-volumetric-instance-level-semantic-mapping-via-multi-view-2d-to-3d-label-diffusion)|


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


### [b01] [Improved techniques for grid mapping with rao-blackwellized particle filters](https://ieeexplore.ieee.org/abstract/document/4084563)
### [b02] [Person tracking and following with 2d laser scanners](https://ieeexplore.ieee.org/abstract/document/7139259/)
### [b03] [Online semantic mapping of logistic environments using RGB-D cameras](https://journals.sagepub.com/doi/pdf/10.1177/1729881417720781)
### [b04] [An efficient 3D pedestrian detector with calibrated RGB camera and 3D LiDAR](https://journals.sagepub.com/doi/pdf/10.1177/1729881417720781)
### [b05] [Hypermap mapping framework and its application to autonomous semantic exploration](https://ieeexplore.ieee.org/abstract/document/9235231)
### [b06] [Augmented Environment Representations with Complete Object Models](https://ieeexplore.ieee.org/abstract/document/9900516)
### [b07] [Kinectfusion: Real-time dense surface mapping and tracking](https://ieeexplore.ieee.org/abstract/document/6162880/)
### [b08] [Hierarchical higher-order regression forest fields: An application to 3d indoor scene labelling](https://www.cv-foundation.org/openaccess/content_iccv_2015/html/Pham_Hierarchical_Higher-Order_Regression_ICCV_2015_paper.html)
### [b09] [Meaningful maps with object-oriented semantic mapping](https://ieeexplore.ieee.org/abstract/document/8206392)
### [b10] [Semanticfusion: Dense 3d semantic mapping with convolutional neural networks](https://ieeexplore.ieee.org/abstract/document/7989538)
### [b11] [OctoMap: An efficient probabilistic 3D mapping framework based on octrees](https://link.springer.com/article/10.1007/s10514-012-9321-0)
### [b12] [Voxblox: Incremental 3d euclidean signed distance fields for on-board mav planning](https://ieeexplore.ieee.org/abstract/document/8202315/)
### [b13] [Kimera: an open-source library for real-time metric-semantic localization and mapping](https://ieeexplore.ieee.org/abstract/document/9196885/)
### [b14] [Real-time progressive 3D semantic segmentation for indoor scenes](https://ieeexplore.ieee.org/abstract/document/8658744/)
### [b15] [Volumetric instance-aware semantic mapping and 3D object discovery](https://ieeexplore.ieee.org/abstract/document/8741085/)
### [b16] [Incremental instance-oriented 3D semantic mapping via RGB-D cameras for unknown indoor scene](https://www.hindawi.com/journals/ddns/2020/2528954/)
### [b17] [Volumetric Instance-Level Semantic Mapping Via Multi-View 2D-to-3D Label Diffusion](https://ieeexplore.ieee.org/abstract/document/9695168)

Survey
1. Simultaneous Localization and Mapping in the Epoch of Semantics: A Survey