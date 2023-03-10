# Bibliography on Object SLAM

## Literature review of point-plane-object SLAM systems.
|   | Sensor | Point | Plane | Object | Data Association | Link |
|:---|:---|:---|:---|:---|:---|:---|
\cite{davison2007monoslam} | RGB | image patch |   |  | patch search | [[d01]](#d01-monoslam-real-time-single-camera-slam) |
\cite{klein2007parallel} | RGB | FAST |  |  | patch search |[[d02]](#d02-parallel-tracking-and-mapping-for-small-ar-workspaces) |
\cite{mur2015orb} | RGB | ORB |  |  | descriptor matching |[[d03]](#d03-orb-slam-a-versatile-and-accurate-monocular-slam-system) |
\cite{hsiao2017keyframe} | RGB-D |  | plane |  | normal, distance, residual |[[d04]](#d04-keyframe-based-dense-planar-slam) |
\cite{zhang2019point} | RGB-D |  | plane |  | normal, distance, boundary | [[d05]](#d05-point-plane-slam-using-supposed-planes-for-indoor-environments) |
\cite{yang2016pop} | RGB | ORB | plane |  | normal, distance, polygon | [[d06]](#d06-pop-up-slam-semantic-monocular-plane-slam-for-low-texture-environments) |
\cite{li2021rgb} | RGB-D | ORB | plane |  | normal, distance | [[d07]](#d07-rgb-d-slam-with-structural-regularities) |
\cite{hosseinzadeh2017sparse} | RGB-D | ORB | plane |  | normal, distance |[[d08]](#d08-sparse-point-plane-slam) |
\cite{salas2013slam++} | RGB-D |  |  | 3D model | feature matching |[[d09]](#d09-slam-simultaneous-localisation-and-mapping-at-the-level-of-objects) |
\cite{nicholson2018quadricslam} | RGB |  |  | quadric | not mentioned |[[d10]](#d10-quadricslam-dual-quadrics-from-object-detections-as-landmarks-in-object-oriented-slam) |
\cite{liao2020rgb} | RGB-D |  |  | quadric | not mentioned |[[d17]](#d17-rgb-d-object-slam-using-quadrics-for-indoor-environments) |
\cite{liao2022so} | RGB-D |  |  | quadric | not mentioned |[[d11]](#d11-so-slam-semantic-object-slam-with-scale-proportional-and-symmetrical-texture-constraints) |
\cite{yang2019cubeslam} | RGB | ORB |  | cuboid | in-object points |[[d12]](#d12-cubeslam-monocular-3-d-object-slam) |
\cite{li2020view} | RGB |  |  | cuboid | geometric features | [[d13]](#d13-view-invariant-loop-closure-with-oriented-semantic-landmarks) |
\cite{lin2021topology} | RGB |  |  | cuboid | geometric features, graph matching | [[d14]](#d14-topology-aware-object-level-semantic-mapping-towards-more-robust-loop-closure) |
\cite{yang2019monocular} | RGB | ORB | plane | cuboid | plane-object: spatial relationship |[[d15]](#d15-monocular-object-and-plane-slam-in-structured-environments) |
\cite{hosseinzadeh2019structure} | RGB-D | ORB | plane | quadric | plane-object: supporting relationship | [[d16]](#d16-structure-aware-slam-using-quadrics-and-planes) |


## Reference on point-plane-object SLAM
### [d01] [MonoSLAM: Real-time single camera SLAM](https://ieeexplore.ieee.org/abstract/document/4160954/)
### [d02] [Parallel tracking and mapping for small AR workspaces](https://ieeexplore.ieee.org/abstract/document/4538852)
### [d03] [ORB-SLAM: a versatile and accurate monocular SLAM system](https://ieeexplore.ieee.org/abstract/document/7219438)
### [d04] [Keyframe-based dense planar SLAM](https://ieeexplore.ieee.org/abstract/document/7989597)
### [d05] [Point-plane slam using supposed planes for indoor environments](https://www.mdpi.com/1424-8220/19/17/3795?ref=https://githubhelp.com)
### [d06] [Pop-up slam: Semantic monocular plane slam for low-texture environments](https://ieeexplore.ieee.org/abstract/document/7759204)
### [d07] [RGB-D SLAM with structural regularities](https://ieeexplore.ieee.org/abstract/document/9561560)
### [d08] [Sparse point-plane SLAM](https://www.araa.asn.au/acra/acra2017/papers/pap170s1-file1.pdf)
### [d09] [Slam++: Simultaneous localisation and mapping at the level of objects](https://openaccess.thecvf.com/content_cvpr_2013/html/Salas-Moreno_SLAM_Simultaneous_Localisation_2013_CVPR_paper.html)
### [d10] [Quadricslam: Dual quadrics from object detections as landmarks in object-oriented slam](https://ieeexplore.ieee.org/abstract/document/8440105)
### [d11] [So-slam: Semantic object slam with scale proportional and symmetrical texture constraints](https://ieeexplore.ieee.org/abstract/document/9705562/)
### [d12] [Cubeslam: Monocular 3-d object slam](https://ieeexplore.ieee.org/abstract/document/8708251)
### [d13] [View-invariant loop closure with oriented semantic landmarks](https://ieeexplore.ieee.org/abstract/document/9196886/)
### [d14] [Topology aware object-level semantic mapping towards more robust loop closure](https://ieeexplore.ieee.org/abstract/document/9484819)
### [d15] [Monocular object and plane slam in structured environments](https://ieeexplore.ieee.org/abstract/document/8744612/)
### [d16] [Structure aware SLAM using quadrics and planes](https://link.springer.com/chapter/10.1007/978-3-030-20893-6_26)
### [d17] [RGB-D Object SLAM Using Quadrics for Indoor Environments](https://www.mdpi.com/1424-8220/20/18/5150)
### [d18] [Real-Time Monocular Object-Model Aware Sparse SLAM ](https://ieeexplore.ieee.org/abstract/document/8793728)
### [d19] [Constructing Category-Specific Models for Monocular Object-SLAM](https://ieeexplore.ieee.org/abstract/document/8460816)
### [d20] [EAO-SLAM: Monocular Semi-Dense Object SLAM Based on Ensemble Data Association ](https://ieeexplore.ieee.org/abstract/document/9341757)

## Quadric Estimation
### [f1] [Structure from Motion with Objects](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Crocco_Structure_From_Motion_CVPR_2016_paper.html)

### [f2] [Probabilistic Structure from Motion with Objects (PSfMO)](https://openaccess.thecvf.com/content_iccv_2017/html/Gay_Probabilistic_Structure_From_ICCV_2017_paper.html)

### [f3] [Visual Graphs from Motion (VGfM): Scene understanding with object geometry reasoning](https://link.springer.com/chapter/10.1007/978-3-030-20893-6_21)

### [f4] [Robust Dual Quadric Initialization for Forward-Translating Camera Movements](https://ieeexplore.ieee.org/abstract/document/9384189)

### [f5] [Accurate and Robust Object-oriented SLAM with 3D Quadric Landmark Construction in Outdoor Environment](https://arxiv.org/abs/2110.08977)