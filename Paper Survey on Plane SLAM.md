# Bibliography on Plane SLAM

## Plane Estimation

|   | Year | Scene | Sensor | Method | Link |
|:--|:--|:--|:--|:--|:--|
RANSAC | 2010 | RGBD | Indoor | Plane detection in point cloud data |
Point Cloud Segmentation | 2011 | RGBD | Indoor | Clustered, segmented, Classified | [[a1]](#a1-real-time-plane-segmentation-using-rgb-d-cameras)
PEAC (AHC) | 2014 | RGBD | Indoor | Agglomerative Hierarchical Clustering, Organized Point Cloud | [[a2]](#a2-fast-plane-extraction-in-organized-point-clouds-using-agglomerative-hierarchical-clustering)
Conditional Random Field (CRF) | 2016 | RGBD | Indoor | Plane Optimization | [[a3]](#a3-real-time-3d-scene-layout-from-a-single-image-using-convolutional-neural-networks)
Markov Random Field (MRF) | 2018 | RGBD | Indoor | Plane Optimization | [[a4]](#a4-plane-based-optimization-of-geometry-and-texture-for-rgb-d-reconstruction-of-indoor-scenes)
PlaneNet | 2018 | RGB | Indoor | Depth prediction | [[a5]](#a5-planenet-piece-wise-planar-reconstruction-from-a-single-rgb-image)
PlaneRecover | 2018 | RGB | Indoor | New Plane Structure-Induced Loss | [[a6]](#a6-planercnn-3d-plane-detection-and-reconstruction-from-a-single-image)
PlaneRCNN | 2019 | RGB | Indoor | Mask, normal | [[a7]](#a7-recovering-3d-planes-from-a-single-image-via-convolutional-neural-networks)
PlaneRecostruction | 2019 | RGB | Indoor | Two stage: plane segmentation + clustering | [[a8]](#a8-planerecostruction-single-image-piece-wise-planar-3d-reconstruction-via-associative-embedding)

## Plane-base SLAM

| | Year | Sensor | Detection | Association | Optimization | keywords | Link
|:--|:--|:--|:--|:--|:--|:--|:--|
Infinite Planes | 2015 | RGBD | Surface normal | Distance and angle | Log(qT, q) | Homogeneous plane parameter | [[b1]](#b1-simultaneous-localization-and-mapping-with-infinite-planes)
Pop-up SLAM | 2016 | RGB | Pop-up from edge | Normal, distance and polygon | Log(q(T*pi)-1* q(pi)) | Pop-up plane model | [[b2]](#b2-pop-up-slam-semantic-monocular-plane-slam-for-low-texture-environments)
Dense piecewise Planar | 2017 | RGBD | RANSAC | GIST |  | RANSAC, SIFT, GIST features, Plane | [[b3]](#b3-dense-piecewise-planar-rgb-d-slam-for-indoor-environments)
KDP (Keyframe Dense Plane) | 2017 | RGBD | Region normal | Normals, distance, points dist |  | Interactive Projective Plane, local depth map, global planar mapping | [[b4]](#b4-keyframe-based-dense-planar-slam-kdp-slam)
Sparse point + plane | 2017 | RGBD | RANSAC | Normals, distance, | E = ||n(x-x0)|| | point cloud segmentation, ORB feature points | [[b5]](#b5-sparse-point-plane-slam)
Geometric Primitives | 2018 | RGBD | AHC |  |  | AHC, ORB, Line | [[b6]](#b6-geometric-primitives-based-rgb-d-slam-for-low-texture-environment)
Point + supposed plane | 2019 |  | Multi-Plane | Normals, distance, points dist | F = ||q(pi)-q(T*pi)|| | Point cloud segmentation, Supposed perpendicular planes | [[b7]](#b7-point-plane-slam-using-supposed-planes-for-indoor-environments)
GPM (global plane map) | 2020 |  | PEAC | Normals, distance | E = (T*v1-T*v2) | PEAC, ICP tracking, plane-plane match, global plane map (GPM), Fusion reconstruction. | [[b8]](#b8-real-time-dense-3d-reconstruction-and-camera-tracking-via-embedded-planes-representation)
Points + in-plane points SLAM | 2020 | RGB | RANSAC+ SVD |  | Feature points | Normal and in-plane points | [[b9]](#b9-from-points-to-planes---adding-planar-constraints-to-monocular-slam-factor-graphs)
LPVO | 2018 |  |  |  |  | 
OPVO | 2019 |  |  |  |  | 
Structural Regularities | 2020 |  |  |  |  | 



## Reference
### [a1] [Real-Time Plane Segmentation using RGB-D Cameras ](https://link.springer.com/chapter/10.1007/978-3-642-32060-6_26)

### [a2] [Fast Plane Extraction in Organized Point Clouds Using Agglomerative Hierarchical Clustering ](https://ieeexplore.ieee.org/abstract/document/6907776)

### [a3] [Real-time 3D Scene Layout from a Single Image Using Convolutional Neural Networks ](https://ieeexplore.ieee.org/abstract/document/7487368)

### [a4] [Plane-Based Optimization of Geometry and Texture for RGB-D Reconstruction of Indoor Scenes](https://ieeexplore.ieee.org/abstract/document/8491005)

### [a5] [PlaneNet: Piece-wise Planar Reconstruction from a Single RGB Image](https://openaccess.thecvf.com/content_cvpr_2018/html/Liu_PlaneNet_Piece-Wise_Planar_CVPR_2018_paper.html)

### [a6] [PlaneRCNN: 3D Plane Detection and Reconstruction from a Single Image](https://openaccess.thecvf.com/content_CVPR_2019/html/Liu_PlaneRCNN_3D_Plane_Detection_and_Reconstruction_From_a_Single_Image_CVPR_2019_paper.html)

### [a7] [Recovering 3D Planes from a Single Image via Convolutional Neural Networks ](https://openaccess.thecvf.com/content_ECCV_2018/html/Fengting_Yang_Recovering_3D_Planes_ECCV_2018_paper.html)

### [a8] [PlaneRecostruction: Single-Image Piece-wise Planar 3D Reconstruction via Associative Embedding ](https://openaccess.thecvf.com/content_CVPR_2019/html/Yu_Single-Image_Piece-Wise_Planar_3D_Reconstruction_via_Associative_Embedding_CVPR_2019_paper)

Other work on Plane Estimation
1. Real-Time Plane Segmentation using RGB-D Cameras



### [b1] [Simultaneous Localization and Mapping with Infinite Planes ](https://ieeexplore.ieee.org/abstract/document/7139837/)

### [b2] [Pop-up SLAM: Semantic Monocular Plane SLAM for Low-texture Environments](https://ieeexplore.ieee.org/abstract/document/7759204)

### [b3] [Dense Piecewise Planar RGB-D SLAM for Indoor Environments ](https://ieeexplore.ieee.org/abstract/document/8206375)

### [b4] [Keyframe-based Dense Planar SLAM (KDP-SLAM) ](https://ieeexplore.ieee.org/abstract/document/7989597/)

### [b5] [Sparse Point-Plane SLAM ](https://www.araa.asn.au/acra/acra2017/papers/pap170s1-file1.pdf)

### [b6] [Geometric Primitives Based RGB-D SLAM for Low-texture Environment](https://dl.acm.org/doi/abs/10.1145/3205326.3205358)

### [b7] [Point-Plane SLAM Using Supposed Planes for Indoor Environments ](https://www.mdpi.com/1424-8220/19/17/3795/htm?ref=https://githubhelp.com/)

### [b8] [Real-time dense 3D reconstruction and camera tracking via embedded planes representation](https://link.springer.com/article/10.1007/s00371-020-01899-1)

### [b9] [From Points to Planes - Adding Planar Constraints to Monocular SLAM Factor Graphs](https://ieeexplore.ieee.org/abstract/document/9340805/)

Other work on Plane-based SLAM
1. Linear RGB-D SLAM for Planar Environments
2. Low-Drift Visual Odometry in Structured Environments by Decoupling Rotational and Translational Motion
3. Visual Odometry with Drift-Free Rotation Estimation Using Indoor Scene Regularities
4. Multi-planar Monocular Reconstruction of Manhattan Indoor Scenes
5. RGB-D SLAM Using Point–Plane Constraints for Indoor Environments
6. From Planes to Corners: Multi-Purpose Primitive Detection in Unorganized 3D Point Clouds
7. From Points to Planes - Adding Planar Constraints to Monocular SLAM Factor Graphs
8. RGB-D SLAM with Structural Regularities
9. VPS-SLAM: Visual Planar Semantic SLAM for Aerial Robotic Systems
