# Bibliography on Object Detection

# Survey

## 2D Object Detection 
|   | Year | Scene | Sensor | Method | Features | Link|
|:---|:---|:---|:---|:---|:---|:---|
|Jiao et al (Review) | 2019 |  |  |  | A Survey of Deep Learning-based Object Detection | [[a1]](#a1-a-survey-of-deep-learning-based-object-detection)|
|He et al (Mask R-CNN) | 2017 | General | RGB | Mask R-CNN | Two-stage, accurate, generate pixel-wise masks | [[a2]](#a2-mask-r-cnn) |
|Redmon et al (YOLOv2) | 2017 | General | RGB | YOLOv2 | One-stage, efficient, predict object-wise bounding boxes | [[a3]](#a3-yolov2)|


## 3D Object Detection 
|   | Year | Scene | Sensor | CNN | Method | Features | Link|
|:---|:---|:---|:---|:---|:---|:---|:---|
|Lee et al Geometric Reasoning (OM) | 2009 | Indoor | RGB | Geo | OM | Vanishing line, Hypotheses, 2d to 3d | [[b1]](#b1-geometric-reasoning-for-single-image-structure-recovery) |
|Hedau et al Thinking Inside the Box (GC+HOG) | 2010 | Indoor | RGB | Geo | GC+HoG | Vanishing line, feature, cuboid model | [[b2]](#b2-thinking-inside-the-box-using-appearance-models-and-context-based-on-room-geometry) |
|Lee et al Volumetric Reasoning (OM) | 2010 | Indoor | RGB | Geo | OM | Vanishing lines, orientation map, volumetric constraints | [[b3]](#b3-estimating-spatial-layout-of-rooms-using-volumetric-reasoning-about-objects-and-surfaces) |
|Schwing et al Box In the Box (GC+OM+DM) | 2013 | Indoor | RGB | Geo | GC+OM + DM | Vanishing lines, orientation map, geometric context, branch and bound | [[b4]](#b4-box-in-the-box-joint-3d-layout-and-object-reasoning-from-single-images) |
|Xiao et al SUN Primitive | 2012 | Indoor | RGB | Geo | HoG + SVM | Corner, SVM, HoG, displacement | [[b5]](#b5-localizing-3d-cuboids-in-single-view-images) |
|Yang et al Cube SLAM (sample) | 2019 | Indoor | RGB | Geo | Sample | Vanishing lines, Sample, 2d 3d consistency| [[b6]](#b6-cubeslam-monocular-3-d-object-slam)|
|Pillai et al SLAM for Object | 2015 | Indoor | RGB | Geo | Feature points | Feature points (SIFT), multi-view, Object Evidence Aggregation | [[b7]](#b7-monocular-slam-supported-object-recognition) |
|Li et al View-invariant | 2020 | Indoor  | RGB | Geo | Feature points | Matching, inlier, line | [[b8]](#b8-view-invariant-loop-closure-with-oriented-semantic-landmarks) |
|Wu et al EAO | 2020 | Indoor | RGB | Geo | Feature points | Non-parametric test, single-sample test, Ensemble Data Association | [[b9]](#b9-eao-slam-monocular-semi-dense-object-slam-based-on-ensemble-data-association) |
|Jiao et al | 2013 | Indoor  | RGBD | Geo | Cluster | Two planes, form mulitple cuboid matching as mixed integer linear program | [[b10]](#b10-a-linear-approach-to-matching-cuboids-in-rgbd-images) |
|Lin et al Holistic Scene Understanding | 2013 | Indoor | RGBD | Geo | Cluster | Point cloud, multi-view optimization, surface plane estimation | [[b11]](#b11-holistic-scene-understanding-for-3d-object-detection-with-rgbd-cameras)|
 |  |  |  |  |  | 
 |  |  |  |  |  | 
|Dwibedi et al Deep Cuboid Detection | 2016 | Indoor | RGB | CNN | Keypoint | Corner, CNN, RPN, ROI, RCNN regressor. | [[c1]](#c1-deep-cuboid-detection-beyond-2d-bounding-boxes)|
|Perspective Net | 2019 | Indoor | RGB | CNN | Keypoint | Perspective points (corner), 2D-3D consistency | [[c2]](#c2-perspectivenet-3d-object-detection-from-a-single-rgb-image-via-perspective-points)|
|Mobile Pose | 2020 | Indoor | RGB | CNN | 2D-3D | Heat map, Shape, EPnP, 2D-3D consistency| [[c3]](#c3-mobilepose-real-time-pose-estimation-for-unseen-objects-with-weak-shape-supervision)|
|Cooperative Holistic Scene | 2018 | Indoor | RGBD | CNN | Depth | global geometry network, local object network, 2D-3D consistency | [[c4]](#c4-cooperative-holistic-scene-understanding-unifying-3d-object-layout-and-camera-pose-estimation)|
|Total 3D understanding | 2020 | Indoor | RGB | CNN | Depth | Layout estimation network, object detection network, mesh generation network, 2D-3D consistency | [[c5]](#c5-total3dunderstanding-joint-layout-object-pose-and-mesh-reconstruction-for-indoor-scenes-from-a-single-image)|
|Qi et al VoteNet | 2019 | Indoor | RGBD | CNN | vote | Deep hough voting, sampling, grouping, clusterring | [[c6]](#c6-deep-hough-voting-for-3d-object-detection-in-point-clouds)|
|Qi et al ImVoteNet | 2020 | Indoor | RGBD | CNN | vote | Geometry cues, texture cues, semantic cues, feature fusion| [[c7]](#c7-imvotenet-boosting-3d-object-detection-in-point-clouds-with-image-votes)|


## Reference
### [a1] [A Survey of Deep Learning-based Object Detection](https://ieeexplore.ieee.org/abstract/document/8825470)

### [a2] [Mask R-CNN](https://openaccess.thecvf.com/content_iccv_2017/html/He_Mask_R-CNN_ICCV_2017_paper.html)

### [a3] [YOLOv2](https://openaccess.thecvf.com/content_cvpr_2017/html/Redmon_YOLO9000_Better_Faster_CVPR_2017_paper.html)

### [b1] [Geometric Reasoning for Single Image Structure Recovery](https://ieeexplore.ieee.org/document/5206872)

### [b2] [Thinking Inside the Box: Using Appearance Models and Context Based on Room Geometry](https://link.springer.com/chapter/10.1007/978-3-642-15567-3_17)

### [b3] [Estimating Spatial Layout of Rooms using Volumetric Reasoning about Objects and Surfaces](https://proceedings.neurips.cc/paper/2010/hash/076a0c97d09cf1a0ec3e19c7f2529f2b-Abstract.html )

### [b4] [Box in the Box: Joint 3D Layout and Object Reasoning from Single Images](https://www.cv-foundation.org/openaccess/content_iccv_2013/html/Schwing_Box_in_the_2013_ICCV_paper.html)

### [b5] [Localizing 3D cuboids in single-view images](https://proceedings.neurips.cc/paper/2012/hash/58238e9ae2dd305d79c2ebc8c1883422-Abstract.html)

### [b6] [CubeSLAM: Monocular 3-D Object SLAM](https://ieeexplore.ieee.org/abstract/document/8708251)

### [b7] [Monocular SLAM Supported Object Recognition](https://arxiv.org/abs/1506.01732)

### [b8] [View-Invariant Loop Closure with Oriented Semantic Landmarks](https://ieeexplore.ieee.org/abstract/document/9196886)


### [b9] [EAO-SLAM: Monocular Semi-Dense Object SLAM Based on Ensemble Data Association](https://ieeexplore.ieee.org/abstract/document/9341757)

### [b10] [A Linear Approach to Matching Cuboids in RGBD Images](https://openaccess.thecvf.com/content_cvpr_2013/html/Jiang_A_Linear_Approach_2013_CVPR_paper.html)

### [b11] [Holistic Scene Understanding for 3D Object Detection with RGBD cameras](https://openaccess.thecvf.com/content_iccv_2013/html/Lin_Holistic_Scene_Understanding_2013_ICCV_paper.html)

### [c1] [Deep Cuboid Detection: Beyond 2D Bounding Boxes](https://arxiv.org/abs/1611.10010)

### [c2] [PerspectiveNet: 3D Object Detection from a Single RGB Image via Perspective Points](https://proceedings.neurips.cc/paper/2019/hash/b87517992f7dce71b674976b280257d2-Abstract.html)

### [c3] [MobilePose: Real-Time Pose Estimation for Unseen Objects with Weak Shape Supervision](https://arxiv.org/abs/2003.03522)

### [c4] [Cooperative Holistic Scene Understanding: Unifying 3D Object, Layout, and Camera Pose Estimation](https://proceedings.neurips.cc/paper/2018/hash/82161242827b703e6acf9c726942a1e4-Abstract.html)

### [c5] [Total3DUnderstanding: Joint Layout, Object Pose and Mesh Reconstruction for Indoor Scenes From a Single Image](https://openaccess.thecvf.com/content_CVPR_2020/html/Nie_Total3DUnderstanding_Joint_Layout_Object_Pose_and_Mesh_Reconstruction_for_Indoor_CVPR_2020_paper.html)

### [c6] [Deep Hough Voting for 3D Object Detection in Point Clouds](https://openaccess.thecvf.com/content_ICCV_2019/html/Qi_Deep_Hough_Voting_for_3D_Object_Detection_in_Point_Clouds_ICCV_2019_paper.html)

### [c7] [ImVoteNet: Boosting 3D Object Detection in Point Clouds With Image Votes](https://openaccess.thecvf.com/content_CVPR_2020/html/Qi_ImVoteNet_Boosting_3D_Object_Detection_in_Point_Clouds_With_Image_CVPR_2020_paper.html)


