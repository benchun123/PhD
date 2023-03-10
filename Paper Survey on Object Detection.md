# Bibliography on Object Detection

## Literature review of 2D Object Detection 
|   | Year | Scene | Sensor | Method | Features | Link |
|:---|:---|:---|:---|:---|:---|:---|
|Jiao et al (Review) | 2019 |  |  |  | A Survey of Deep Learning-based Object Detection | [[a1]](#a1-a-survey-of-deep-learning-based-object-detection)|
|He et al (Mask R-CNN) | 2017 | General | RGB | Mask R-CNN | Two-stage, accurate, generate pixel-wise masks | [[a2]](#a2-mask-r-cnn) |
|Redmon et al (YOLOv2) | 2017 | General | RGB | YOLOv2 | One-stage, efficient, predict object-wise bounding boxes | [[a3]](#a3-yolov2)|

## Literature review of 3D object detection with geometry methods.
|    | Scene | Sensor | Method | Model | Features | Link |
|:---|:---|:---|:---|:---|:---|:---|
parkhiya2018constructing | indoor | RGB | geometry | points | model matching | [[b01]](#b01-constructing-category-specific-models-for-monocular-object-slam) |
grinvald2019volumetric | indoor | RGB-D | geometry | points | mask segmentation | [[b02]](#b02-volumetric-instance-aware-semantic-mapping-and-3d-object-discovery) |
rubino20173d | indoor | RGB | geometry | quadric | 2D ellipse, multi-view optimization | [[b03]](#b03-3d-object-localisation-from-multi-view-image-detections) |
nicholson2018quadricslam | indoor | RGB | geometry | quadric | 2D box to 3D enveloping planes |[[b04]](#b04-quadricslam-dual-quadrics-from-object-detections-as-landmarks-in-object-oriented-slam) |
liao2020object | indoor | RGB-D | geometry | quadric | symmetric planes |[[b05]](#b05-object-oriented-slam-using-quadrics-and-symmetry-properties-for-indoor-environments) |
gupta2010estimating | indoor | RGB | geometry | cuboid | line segmentation | [[b06]](#b06-estimating-spatial-layout-of-rooms-using-volumetric-reasoning-about-objects-and-surfaces) |
xiao2012localizing | indoor | RGB | geometry | cuboid | corner detection | [[b07]](#b07-localizing-3d-cuboids-in-single-view-images) |
yang2019cubeslam | indoor | RGB | geometry | cuboid | vanishing lines |[[b08]](#b08-cubeslam-monocular-3-d-object-slam) |
jiang2013linear | indoor | RGB-D | geometry | cuboid | minimal cuboid |[[b09]](#b09-a-linear-approach-to-matching-cuboids-in-rgbd-images) |
mishima2019incremental | indoor | RGB-D | geometry | cuboid | three perpendicular planes |[[b10]](#b10-incremental-3d-cuboid-modeling-with-drift-compensation) |
lin2021topology | indoor | RGB-D | geometry | cuboid | projecting onto ground |[[b11]](#b11-topology-aware-object-level-semantic-mapping-towards-more-robust-loop-closure) |

## Literature review of 3D object detection with deep learning methods.
|    | Scene | Sensor | Method | Model | Features | Link |
|:---|:---|:---|:---|:---|:---|:---|
dwibedi2016deep | indoor | RGB | network | cuboid | corner regression | [[c01]](#c01-deep-cuboid-detection-beyond-2d-bounding-boxes) |
huang2019perspectivenet | indoor | RGB | network | cuboid | perspective points | [[c02]](#c02-perspectivenet-3d-object-detection-from-a-single-rgb-image-via-perspective-points) |
huang2018cooperative | indoor | RGB | network | cuboid | size, rotation, distance regression, cooperative training | [[c03]](#c03-cooperative-holistic-scene-understanding-unifying-3d-object-layout-and-camera-pose-estimation) |
nie2020total3dunderstanding | indoor | RGB | network | cuboid | relationship with surrounding | [[c04]](#c04-total3dunderstanding-joint-layout-object-pose-and-mesh-reconstruction-for-indoor-scenes-from-a-single-image) |
qi2017pointnet | indoor | RGB-D | network | points | interesting points selection | [[c05]](#c05-pointnet-deep-learning-on-point-sets-for-3d-classification-and-segmentation) |
qi2017pointnet++ | indoor | RGB-D | network | points | geometric structure with neighbourhoods | [[c06]](#c06-pointnet-deep-hierarchical-feature-learning-on-point-sets-in-a-metric-space) |
qi2019deep | indoor | RGB-D | network | points | object center voting and geometry constraints | [[c07]](#c07-deep-hough-voting-for-3d-object-detection-in-point-clouds) |
qi2020imvotenet | indoor | RGB-D | network | points | 2D-3D consistency, voting schedule | [[c08]](#c08-imvotenet-boosting-3d-object-detection-in-point-clouds-with-image-votes) |

### Others
|    | Scene | Sensor | Method | Model | Features | Link |
|:---|:---|:---|:---|:---|:---|:---|
|lee2009geometric | indoor | RGB | geometry |  cuboid | vanishing line, Hypotheses, 2d to 3d | [[b12]](#b12-geometric-reasoning-for-single-image-structure-recovery) |
|hedau2010thinking | indoor | RGB | geometry | cuboid | GC+HoG, Vanishing line, feature, cuboid model | [[b13]](#b13-thinking-inside-the-box-using-appearance-models-and-context-based-on-room-geometry) |
|lee2010estimating | indoor | RGB | geometry | cuboid | OM. vanishing lines, orientation map, volumetric constraints | [[b14]](#b14-estimating-spatial-layout-of-rooms-using-volumetric-reasoning-about-objects-and-surfaces) |
|schwing2013box | indoor | RGB | geometry | cuboid | GC+OM + DM, Vanishing lines, orientation map, geometric context, branch and bound | [[b15]](#b15-box-in-the-box-joint-3d-layout-and-object-reasoning-from-single-images) |
|pillai2015monocular | indoor | RGB | geometry | cuboid | Feature points (SIFT), multi-view, Object Evidence Aggregation | [[b16]](#b16-monocular-slam-supported-object-recognition) |
|Li2020view | indoor  | RGB | geometry | cuboid | Feature points, Matching, inlier, line | [[b17]](#b17-view-invariant-loop-closure-with-oriented-semantic-landmarks) |
|wu2020eao | indoor | RGB | geometry | cuboid | Feature points, Non-parametric test, single-sample test, Ensemble Data Association | [[b18]](#b18-eao-slam-monocular-semi-dense-object-slam-based-on-ensemble-data-association) |
|lin2013holistic | indoor | RGBD | geometry | cuboid | Cluster, Point cloud, multi-view optimization, surface plane estimation | [[b19]](#b19-holistic-scene-understanding-for-3d-object-detection-with-rgbd-cameras)|




## Reference
### [a1] [A Survey of Deep Learning-based Object Detection](https://ieeexplore.ieee.org/abstract/document/8825470)

### [a2] [Mask R-CNN](https://openaccess.thecvf.com/content_iccv_2017/html/He_Mask_R-CNN_ICCV_2017_paper.html)

### [a3] [YOLOv2](https://openaccess.thecvf.com/content_cvpr_2017/html/Redmon_YOLO9000_Better_Faster_CVPR_2017_paper.html)

### [b01] [Constructing category-specific models for monocular object-slam](https://ieeexplore.ieee.org/abstract/document/8460816/)

### [b02] [Volumetric instance-aware semantic mapping and 3D object discovery](https://ieeexplore.ieee.org/abstract/document/8741085)

### [b03] [3d object localisation from multi-view image detections](https://ieeexplore.ieee.org/abstract/document/7919240)

### [b04] [Quadricslam: Dual quadrics from object detections as landmarks in object-oriented slam](https://ieeexplore.ieee.org/abstract/document/8440105)

### [b05] [Object-oriented slam using quadrics and symmetry properties for indoor environments](https://arxiv.org/abs/2004.05303)

### [b06] [Estimating spatial layout of rooms using volumetric reasoning about objects and surfaces](https://proceedings.neurips.cc/paper/2010/hash/076a0c97d09cf1a0ec3e19c7f2529f2b-Abstract.html)

### [b07] [Localizing 3D cuboids in single-view images](https://proceedings.neurips.cc/paper/2012/hash/58238e9ae2dd305d79c2ebc8c1883422-Abstract.html)

### [b08] [Cubeslam: Monocular 3-d object slam](https://ieeexplore.ieee.org/abstract/document/8708251)

### [b09] [A linear approach to matching cuboids in RGBD images](https://openaccess.thecvf.com/content_cvpr_2013/html/Jiang_A_Linear_Approach_2013_CVPR_paper.html)
### [b10] [Incremental 3d cuboid modeling with drift compensation](https://www.mdpi.com/1424-8220/19/1/178)
### [b11] [Topology aware object-level semantic mapping towards more robust loop closure](https://ieeexplore.ieee.org/abstract/document/9484819/)

### [b12] [Geometric reasoning for single image structure recovery](https://ieeexplore.ieee.org/document/5206872)

### [b13] [Thinking inside the box: Using appearance models and context based on room geometry](https://link.springer.com/chapter/10.1007/978-3-642-15567-3_17)

### [b14] [Estimating spatial layout of rooms using volumetric reasoning about objects and surfaces](https://proceedings.neurips.cc/paper/2010/hash/076a0c97d09cf1a0ec3e19c7f2529f2b-Abstract.html )

### [b15] [Box in the box: Joint 3d layout and object reasoning from single images](https://www.cv-foundation.org/openaccess/content_iccv_2013/html/Schwing_Box_in_the_2013_ICCV_paper.html)

### [b16] [Monocular slam supported object recognition](https://arxiv.org/abs/1506.01732)

### [b17] [View-invariant loop closure with oriented semantic landmarks](https://ieeexplore.ieee.org/abstract/document/9196886)


### [b18] [Eao-slam: Monocular semi-dense object slam based on ensemble data association](https://ieeexplore.ieee.org/abstract/document/9341757)

### [b19] [Holistic scene understanding for 3d object detection with rgbd cameras](https://openaccess.thecvf.com/content_iccv_2013/html/Lin_Holistic_Scene_Understanding_2013_ICCV_paper.html)





### [c01] [Deep cuboid detection: Beyond 2d bounding boxes](https://arxiv.org/abs/1611.10010)

### [c02] [Perspectivenet: 3d object detection from a single rgb image via perspective points](https://proceedings.neurips.cc/paper/2019/hash/b87517992f7dce71b674976b280257d2-Abstract.html)

### [c03] [Cooperative holistic scene understanding: Unifying 3d object, layout, and camera pose estimation](https://proceedings.neurips.cc/paper/2018/hash/82161242827b703e6acf9c726942a1e4-Abstract.html)

### [c04] [Total3dunderstanding: Joint layout, object pose and mesh reconstruction for indoor scenes from a single image](https://openaccess.thecvf.com/content_CVPR_2020/html/Nie_Total3DUnderstanding_Joint_Layout_Object_Pose_and_Mesh_Reconstruction_for_Indoor_CVPR_2020_paper.html)

### [c05] [Pointnet: Deep learning on point sets for 3d classification and segmentation](https://openaccess.thecvf.com/content_cvpr_2017/html/Qi_PointNet_Deep_Learning_CVPR_2017_paper.html)

### [c06] [Pointnet++: Deep hierarchical feature learning on point sets in a metric space](https://proceedings.neurips.cc/paper/2017/hash/d8bf84be3800d12f74d8b05e9b89836f-Abstract.html)

### [c07] [Deep hough voting for 3d object detection in point clouds](https://openaccess.thecvf.com/content_ICCV_2019/html/Qi_Deep_Hough_Voting_for_3D_Object_Detection_in_Point_Clouds_ICCV_2019_paper.html)

### [c08] [Imvotenet: Boosting 3d object detection in point clouds with image votes](https://openaccess.thecvf.com/content_CVPR_2020/html/Qi_ImVoteNet_Boosting_3D_Object_Detection_in_Point_Clouds_With_Image_CVPR_2020_paper.html)

### [c09] [MobilePose: Real-Time Pose Estimation for Unseen Objects with Weak Shape Supervision](https://arxiv.org/abs/2003.03522)







