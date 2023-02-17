# Bibliography on Object SLAM

# Survey

## SLAM Survey

## Object-based SLAM (objects)
|   | Year | Sensor | Landmark | Geometry | Data Association | Map |Features | Link |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
SLAM ++ | 2013 | RGB | Object | 3D model | Model match | Sparse  | First object-oriented SLAM  | [[e1]](#e1-slam-simultaneous-localisation-and-mapping-at-the-level-of-objects) |
CAD SLAM | 2018 | RGB | Object | 3D model | Model match | Sparse  | category-specific model  | [[e2]](#e2-constructing-category-specific-models-for-monocular-object-slam) |
Cube SLAM | 2019 | RGB | Object, Point | Cuboid | Feature points matching | Sparse | Single frame cuboid detection | [[e3]](#e3-cubeslam-monocular-3-d-object-slam)
Cube + Pop SLAM | 2019 | RGB | Object, Plane, Point | Cuboid, Plane  | Feature points matching | sparse | Cuboid plane association | [[e4]](#e4-monocular-object-and-plane-slam-in-structured-environments)
EAO SLAM | 2020 | RGB | Object, Point | Cuboid, Points | Feature points matching | Sparse | Cluster ORB features as cuboid | [[e5]](#e5-eao-slam-monocular-semi-dense-object-slam-based-on-ensemble-data-association)
Quadric SLAM | 2018 | RGB | Object | Quadrics | Feature points matching | Sparse  | plane envelopes >> dual quadrics | [[e6]](#e6-quadricslam-dual-quadrics-from-object-detections-as-landmarks-in-object-oriented-slam)|
Quadric + plane SLAM | 2019 | RGBD | Object, Plane, Point | Quadrics, Plane  | Feature points matching | Sparse  | Depth-based plane estimation | [[e7]](#e7-structure-aware-slam-using-quadrics-and-planes)
Quadric + plane SLAM 2 | 2019 | RGB | Object, Plane, Point | Quadrics, Plane  | Feature points matching | Sparse  | CNN-based RGB plane estimation | [[e8]](#e8-real-time-monocular-object-model-aware-sparse-slam)
Symmetry object SLAM | 2020 | RGBD | Object, Point | Quadrics  | Feature points matching | Sparse | Quadrics symmetry | [[e9]](#e9-object-oriented-slam-using-quadrics-and-symmetry-properties-for-indoor-environments)
Liao et al | 2020 | RGBD | Object, Point | Quadrics  | Feature points matching | Sparse | Plane for quadrics rotation | [[e10]](#e10-rgb-d-object-slam-using-quadrics-for-indoor-environments)
SO-SLAM | 2022 | RGB | Object, points | Quadrics  |  | Sparse | Scale proportional and symmetrical texture constraints | [[e11]](#e11-so-slam-semantic-object-slam-with-scale-proportional-and-symmetrical-texture-constraints)



## Reference

### [a1] [Past Present, and Future of Simultaneous Localization and Mapping Toward the Robust-Perception Age ](https://ieeexplore.ieee.org/abstract/document/7747236)

### [a2] [Review of vision-based Simultaneous Localization and Mapping ](https://ieeexplore.ieee.org/abstract/document/8729285)

### [a3] [A Survey of Simultaneous Localization and Mapping ](https://whubaichuan.github.io/data/v3.pdf)

### [a4] [Semantics for Robotic Mapping, Perception and Interaction A Survey](https://www.nowpublishers.com/article/Details/ROB-059)

### [a5] [A survey of image semantics-based visual simultaneous localization and mapping](https://journals.sagepub.com/doi/full/10.1177/1729881420919185)


## Reference on Object SLAM
### [e1] [SLAM++ simultaneous localisation and mapping at the level of objects](https://openaccess.thecvf.com/content_cvpr_2013/html/Salas-Moreno_SLAM_Simultaneous_Localisation_2013_CVPR_paper.html)

### [e2] [Constructing Category-Specific Models for Monocular Object-SLAM](https://ieeexplore.ieee.org/abstract/document/8460816)

### [e3] [CubeSLAM: Monocular 3-D Object SLAM ](https://ieeexplore.ieee.org/abstract/document/8708251)

### [e4] [Monocular Object and Plane SLAM in Structured Environments ](https://ieeexplore.ieee.org/abstract/document/8744612)

### [e5] [EAO-SLAM: Monocular Semi-Dense Object SLAM Based on Ensemble Data Association ](https://ieeexplore.ieee.org/abstract/document/9341757)

### [e6] [QuadricSLAM: Dual Quadrics from Object Detections as Landmarks in Object-oriented SLAM ](https://ieeexplore.ieee.org/abstract/document/8440105)

### [e7] [Structure Aware SLAM using Quadrics and Planes](https://link.springer.com/chapter/10.1007/978-3-030-20893-6_26)

### [e8] [Real-Time Monocular Object-Model Aware Sparse SLAM ](https://ieeexplore.ieee.org/abstract/document/8793728)

### [e9] [Object-oriented SLAM using Quadrics and Symmetry Properties for Indoor Environments ](https://arxiv.org/abs/2004.05303)

### [e10] [RGB-D Object SLAM Using Quadrics for Indoor Environments](https://www.mdpi.com/1424-8220/20/18/5150)

### [e11] [SO-SLAM: Semantic Object SLAM With Scale Proportional and Symmetrical Texture Constraints](https://ieeexplore.ieee.org/abstract/document/9705562)

## Quadric Estimation
### [f1] [Structure from Motion with Objects](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Crocco_Structure_From_Motion_CVPR_2016_paper.html)

### [f2] [Probabilistic Structure from Motion with Objects (PSfMO)](https://openaccess.thecvf.com/content_iccv_2017/html/Gay_Probabilistic_Structure_From_ICCV_2017_paper.html)

### [f3] [Visual Graphs from Motion (VGfM): Scene understanding with object geometry reasoning](https://link.springer.com/chapter/10.1007/978-3-030-20893-6_21)

### [f4] [Robust Dual Quadric Initialization for Forward-Translating Camera Movements](https://ieeexplore.ieee.org/abstract/document/9384189)

### [f5] [Accurate and Robust Object-oriented SLAM with 3D Quadric Landmark Construction in Outdoor Environment](https://arxiv.org/abs/2110.08977)