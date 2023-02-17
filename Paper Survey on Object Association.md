# Bibliography on Object Associaiton and Loop Closure

## Data Association and Loop Closure
|   | Year | Keywords | Object detection | Object association | Loop closure detection | Final optimization | Link| 
|:---|:---|:---|:---|:---|:---|:---|:---|
Probabilistic DA | 2017 | Data association | 2D bbox + model | EM | / | Semantic factor, Geometric factor, Inertial factor | [[b1]](#b1-probabilistic-data-association-for-semantic-slam)
Topology Aware | 2021 | Loop closure | Voxel model -> cuoid | Size, color, descriptor | Graph matching | 3D Object SE3 error | [[b2]](#b2-topology-aware-object-level-semantic-mapping-towards-more-robust-loop-closure)
Global Localization | 2019 | Loop closure and localization | PSP Net -> points and sphere | Random walk descriptor | Graph matching | Point cloud alignment, Sample Consensus initial alignment | [[b3]](#b3-global-localization-with-object-level-semantics-and-topology)
X-View | 2018 | Loop closure |  | Random walk descriptor | Graph matching |  | [[b4]](#b4-x-view-graph-based-semantic-multi-view-localization)
Semantic Histogram | 2021 | Localization |  | Semantic histogram based descriptor | Graph matching | Pose Estimation | [[b5]](#b5-semantic-histogram-based-graph-matching-for-real-time-multi-robot-global-localization-in-large-scale-environment)
Wide-Disparity | 2021 | Re-localization | DNN -> cuboid | Spatial distance | Graph matching | ICP and Object | [[b6]](#b6-object-augmented-rgb-d-slam-for-wide-disparity-relocalisation)
View-Invariant Relocalization | 2019 | Re-localization | Cuboid: triangular top center, align with axis … | Hungarian with spatial distance |  | Metropolis-Hastings MCMC | [[b8]](#b8-semantic-mapping-for-view-invariant-relocalization)
View-Invariant Loop Closure | 2020 | Loop closure | Cuboid: similar to above | EM | Geometric loop verification  | Feature point and object pose | [[b9]](#b9-view-invariant-loop-closure-with-oriented-semantic-landmarks)
Large Viewpoint Changes | 2018 | Localization  | Cuboid: point cloud inliers, align with vanishing lines, … | Hungarian with spatial distance | / | Metropolis-Hastings MCMC | [[b10]](#b10-semantic-scene-models-for-visual-localization-under-large-viewpoint-changes)
Qian et al | 2020 | Object mapping | Quadrics: 2D bbox + BoW vector + planes | Geometric check, appearance score | / | Object update: initialize when planes are enough, compute conic projection error | [[b11]](#b11-semantic-slam-with-autonomous-object-level-data-association)
Covisibility Graphs | 2022 | loop closure | YOLOv3+ORB | Co-visibility Graph | Graph matching |  | [[b12]](#b12-towards-accurate-loop-closure-detection-in-semantic-slam-with-3d-semantic-covisibility-graphs)
SVG-Loop | 2021 | loop closure | ORB features (add semantic info)-> BoW construction | clockwise descriptor | jointly similarity |  | [[b13]](#b13-svg-loop-semantic–visual–geometric-information-based-loop-closure-detection)
Nonparametric pose graph | 2016 | Data association |  | Nonparametric, Dirichlet process |  |  | [[b14]](#b14-slam-with-objects-using-a-nonparametric-pose-graph)
Nonparametric Statistics | 2018 | Data association |  | Nonparametric Statistics |  |  | [[b15]](#b15-localization-of-classified-objects-in-slam-using-nonparametric-statistics-and-clustering)
Iqbal et al | 2020 | Data association |  | Nonparametric Statistics |  |  | [[b16]](#b16-data-association-and-localization-of-classified-objects-in-visual-slam)
Mixture Models | 2019 | Data association | MobileNet-SSD | Non-Gaussian (max-mixture, multiple hypothesis) |  |  | [[b17]](#b17-probabilistic-data-association-via-mixture-models-for-robust-semantic-slam)
multimodal | 2020 | Data association | MobileNet-SSD | multimodal (non-Gaussian) |  |  | [[b18]](#b18-multimodal-semantic-slam-with-probabilistic-data-association)
EAO | 2020 | Data association | 2D bbox + features | ensemble data association: nonparametric test |  |  | [[b19]](#b19-eao-slam-monocular-semi-dense-object-slam-based-on-ensemble-data-association)



## Refenrence
### [b1] [Probabilistic Data Association for Semantic SLAM](https://ieeexplore.ieee.org/abstract/document/7989203/)

### [b2] [Topology Aware Object-Level Semantic Mapping Towards More Robust Loop Closure](https://ieeexplore.ieee.org/abstract/document/9484819)

### [b3] [Global Localization with Object-Level Semantics and Topology ](https://ieeexplore.ieee.org/abstract/document/8794475/)

### [b4] [X-View: Graph-Based Semantic Multi-View Localization](https://ieeexplore.ieee.org/abstract/document/8281068)

### [b5] [Semantic Histogram Based Graph Matching for Real-Time Multi-Robot Global Localization in Large Scale Environment](https://ieeexplore.ieee.org/abstract/document/9353207)


### [b6] [Object-Augmented RGB-D SLAM for Wide-Disparity Relocalisation](https://ieeexplore.ieee.org/abstract/document/9636034)

### [b7] [Lightweight Object-level Topological Semantic Mapping and Long-term Global Localization based on Graph Matching](https://arxiv.org/abs/2201.05977)

### [b8] [Semantic Mapping for View-Invariant Relocalization](https://ieeexplore.ieee.org/abstract/document/8793624)


### [b9] [View-Invariant Loop Closure with Oriented Semantic Landmarks](https://ieeexplore.ieee.org/abstract/document/9196886)

### [b10] [Semantic Scene Models for Visual Localization Under Large Viewpoint Changes](https://ieeexplore.ieee.org/abstract/document/8575751)

### [b11] [Semantic SLAM with Autonomous Object-Level Data Association](https://ieeexplore.ieee.org/abstract/document/9561532)

### [b12] [Towards Accurate Loop Closure Detection in Semantic SLAM With 3D Semantic Covisibility Graphs](https://ieeexplore.ieee.org/abstract/document/9691853)

### [b13] [SVG-Loop: Semantic–Visual–Geometric Information-Based Loop Closure Detection](https://www.mdpi.com/2072-4292/13/17/3520)

### [b14] [SLAM with Objects using a Nonparametric Pose Graph ](https://ieeexplore.ieee.org/abstract/document/7759677/)

### [b15] [Localization of Classified Objects in SLAM using Nonparametric Statistics and Clustering ](https://ieeexplore.ieee.org/abstract/document/8593541)

### [b16] [Data Association and Localization of Classified Objects in Visual SLAM](https://link.springer.com/article/10.1007/s10846-020-01189-x)

### [b17] [Probabilistic Data Association via Mixture Models for Robust Semantic SLAM](https://ieeexplore.ieee.org/abstract/document/9197382)


### [b18] [Multimodal Semantic SLAM with Probabilistic Data Association](https://ieeexplore.ieee.org/abstract/document/8794244)

### [b19] [EAO-SLAM: Monocular Semi-Dense Object SLAM Based on Ensemble Data Association](https://ieeexplore.ieee.org/abstract/document/9341757)

### [b20] [SymbioLCD: Ensemble-Based Loop Closure Detection using CNN-Extracted Objects and Visual Bag-of-Words](https://ieeexplore.ieee.org/abstract/document/9636622)

### [b21] [GOSMatch: Graph-of-Semantics Matching for Detecting Loop Closures in 3D LiDAR data](https://ieeexplore.ieee.org/abstract/document/9341299)
