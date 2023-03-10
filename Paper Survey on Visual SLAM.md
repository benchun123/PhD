# Bibliography on Visual SLAM

## Survey

### [a1] [Past Present, and Future of Simultaneous Localization and Mapping Toward the Robust-Perception Age ](https://ieeexplore.ieee.org/abstract/document/7747236)

### [a2] [Review of vision-based Simultaneous Localization and Mapping ](https://ieeexplore.ieee.org/abstract/document/8729285)

### [a3] [A Survey of Simultaneous Localization and Mapping ](https://whubaichuan.github.io/data/v3.pdf)

### [a4] [Semantics for Robotic Mapping, Perception and Interaction A Survey](https://www.nowpublishers.com/article/Details/ROB-059)

### [a5] [A survey of image semantics-based visual simultaneous localization and mapping](https://journals.sagepub.com/doi/full/10.1177/1729881420919185)

### [a6] [Simultaneous localization and mapping in the epoch of semantics: a survey](https://link.springer.com/article/10.1007/s12555-018-0130-x)



## SLAM Survey

## Classic Feature Points SLAM
|   | Year | Sensor | Map | Data Association | Loop Closure | Keywrods | Link| 
|:---|:---|:---|:---|:---|:---|:---|:---|
|PTAM | 2007 | RGB | Sparse | Feature matching | No | | [[b1]](#b1-parallel-tracking-and-mapping-for-small-ar-workspaces)|
DTAM | 2011 | RGB | Dense | Direct | No |  | [[b2]](#b2-dtam-dense-tracking-and-mapping-in-real-time)|
ORB SLAM | 2013 | RGB, Stereo, Depth | Sparse | Feature matching | Yes | ORB features, Bag of words | [[b3]](#b3-orb-slam-a-versatile-and-accurate-monocular-slam-system) [[b4]](#b4-orb-slam2-an-open-source-slam-system-for-monocular-stereo-and-rgb-d-cameras)[[b5]](#b5-bags-of-binary-words-for-fast-place-recognition-in-image-sequences)|
RGB-D SLAM | 2014 | RGBD | Sparse | Feature matching | Yes | Octomap | [[b6]](#b6-rgb-d-slam-3d-mapping-with-an-rgb-d-camera)|
RTAB Map | 2013 | RGBD | Dense | feature matching | Yes | online loop closure memory management model | [[b7]](#b7-rtab-map-appearance-based-loop-closure-detection-for-online-large-scale-and-long-term-operation) [[b8]](#b8-rtab-map-online-global-loop-closure-detection-for-large-scale-multi-session)|
SVO | 2014 | RGB | Sparse | Semi-direct | No | monocular, semi-direct, visual odometry | [[b9]](#b9-svo-fast-semi-direct-monocular-visual-odometry) |
LSD-SLAM | 2014 | RGB | Semi-dense | Direct | No | direct (feature-less) monocular SLAM , direct tracking method probabilistic solution | [[b10]](#b10-lsd-slam-large-scale-direct-monocular-slamy) |
DSO | 2014 | RGB | Sparse | Direct | No | feature-less, windowed optimization  | [[b11]](#b11-direct-sparse-odometry) |
DVO | 2013 | RGBD | Dense | ICP | No | entropy-based similarity measure for keyframe selection | [[b12]](#b12-dvo-dense-visual-slam-for-rgb-d-cameras)
Kinect Fusion | 2014 | RGBD | Dense | Feature matching | No | dense volumetric reconstruction, surface measurement | [[b13]](#b13-kinectfusion-real-time-dense-surface-mapping-and-tracking) |
Elastic Fusion | 2014 | RGBD | Dense | Surface based matching | Yes | dense frame-to-model tracking and windowed surfel-based fusion | [[b14]](#b14-elasticfusion-dense-slam-without-a-pose-graph)
OpenVSLAM | 2019 | RGBD | Sparse | Feature matching | Yes | design visual slam as libraries | [[b16]](#b16-openvslam-a-versatile-visual-slam-framework)


## Geometry SLAM (lines, planes)
|   | Year | Sensor | Landmark | Map | Data Association | Link
|:---|:---|:---|:---|:---|:---|:---|

1. PL-SLAM: Real-Time Monocular Visual SLAM with Points and Lines
2. Direct Monocular Odometry Using Points and Lines
3. Structure-aware SLAM with planes and lines in man-made environment
4. Structure-SLAM: Low-Drift Monocular SLAM in Indoor Environments
5. A real-time semantic visual SLAM approach with points and objects

## Semantic SLAM 
continue ...



## Refenrence on Classic SLAM
### [b1] [Parallel Tracking and Mapping for Small AR Workspaces](https://ieeexplore.ieee.org/abstract/document/4538852)

### [b2] [DTAM: Dense Tracking and Mapping in Real-Time](https://ieeexplore.ieee.org/abstract/document/6126513)

### [b3] [ORB-SLAM: A Versatile and Accurate Monocular SLAM System](https://ieeexplore.ieee.org/abstract/document/7219438)

### [b4] [ORB-SLAM2: an Open-Source SLAM System for Monocular, Stereo and RGB-D Cameras ](https://ieeexplore.ieee.org/abstract/document/7946260)

### [b5] [Bags of Binary Words for Fast Place Recognition in Image Sequences](https://ieeexplore.ieee.org/abstract/document/6202705/)

### [b6] [RGB-D SLAM: 3D Mapping with an RGB-D Camera](https://ieeexplore.ieee.org/abstract/document/6594910)

### [b7] [RTAB MAP: Appearance-Based Loop Closure Detection for Online Large-Scale and Long-Term Operation](https://ieeexplore.ieee.org/abstract/document/6594910)

### [b8] [RTAB MAP: Online Global Loop Closure Detection for Large-Scale Multi-Session](https://ieeexplore.ieee.org/abstract/document/6942926)

### [b9] [SVO: Fast semi-direct monocular visual odometry](https://ieeexplore.ieee.org/abstract/document/6906584)

### [b10] [LSD-SLAM Large-Scale Direct Monocular SLAM](https://link.springer.com/chapter/10.1007/978-3-319-10605-2_54)

### [b11] [Direct Sparse Odometry](https://ieeexplore.ieee.org/abstract/document/7898369/)

### [b12] [DVO: Dense Visual SLAM for RGB-D Cameras](https://ieeexplore.ieee.org/abstract/document/6696650)

### [b13] [KinectFusion: Real-Time Dense Surface Mapping and Tracking](https://ieeexplore.ieee.org/abstract/document/6162880/)

### [b14] [ElasticFusion: dense slam without a pose graph](https://spiral.imperial.ac.uk/bitstream/10044/1/23438/2/whelan2015rss.pdf)

### [b15] [SemanticFusion: Dense 3D semantic mapping with convolutional neural networks](https://ieeexplore.ieee.org/abstract/document/7989538)

### [b16] [OpenVSLAM: A Versatile Visual SLAM Framework](https://dl.acm.org/doi/abs/10.1145/3343031.3350539)


