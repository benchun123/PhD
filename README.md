# Introduction

Welcome! My name is Benchun Zhou, Here are some research works and projects during my PhD studies, if you want to know more details of these projects, please click the external link to see the PDFs, or contact me (benchunzhou@gmail.com). I really appreciate your visit and suggestions, I hope you can get what you want. 

PS: For more projects during my master studies, please click here: [MasterToPhD](https://github.com/benchun123/MasterToPhD)

# Research Interests

*   Robotics
*   3D Object Detection
*   Visual Localization and Mapping 

# Overview
* Research
	* **`Doctoral Thesis`** [Visual Localization and Mapping with Objects in Logistic Environments](#1-doctoral-thesis-visual-localization-and-mapping-with-objects-in-logistic-environments)
	* **`Under Submission 2023`**		  [Efficient Object-Level Semantic Mapping with RGB-D Cameras](#2-under-submission-2023-efficient-object-level-semantic-mapping-with-rgb-d-cameras)
	* **`Under Submission 2023`**		  [Towards Autonomous Navigation for Agile Production System](#3-under-submission-2023-towards-autonomous-navigation-for-agile-production-system)
	* **`Advanced Robotics 2022`**		  [Structure SLAM with points plane and objects](#4-advanced-robotics-2022-structure-slam-with-points-plane-and-objects)
	* **`CASE 2022`**		  [Object-based Loop Closure with Oriented Histgram Descriptor](#6-case-2022-object-based-loop-closure-with-oriented-histgram-descriptor)
	* **`MFI2021`**   	  [Object-based Localization and Mapping with Bbox Constraints](#7-mfi-2021-object-based-localization-and-mapping-with-bbox-constraints)

*  Projects
	* **`Agiprobot`** 	  [Towards Autonomous Navigation for Agile Production System](#3-under-submission-2023-towards-autonomous-navigation-for-agile-production-system)
	* **`SDM4FZI`** 	  [Digital Twin Implementation in Logistic Environments](#5-sdm4fzi-digital-twin-implementation-in-logistic-environments)
	* **`ACDU`** 		  [Automatic Connection Device Underbody](#8-acdu-automatic-connection-device-underbody)

*  Paper Survey
	* **`Object Detection`** 	  [Paper Survey Object Detection](#paper-survey-on-object-detection)
	* **`Object Association`** 	  [Paper Survey Object Association](#paper-survey-on-object-association)
	* **`Object SLAM`** 		  [Paper Survey Object SLAM](#paper-survey-on-object-slam)
	* **`Object Mapping`** 		  [Paper Survey Object Mapping](#paper-survey-on-object-mapping)
	* **`Visual SLAM`** 		  [Paper Survey Visual SLAM](#paper-survey-on-visual-slam)
	* **`Plane SLAM`** 		  [Paper Survey Plane SLAM](#paper-survey-on-plane-slam)

# Details
## 1. `Doctoral Thesis` [Visual Localization and Mapping with Objects in Logistic Environments]()

TBD

## 2. `Under Submission 2023` [Efficient Object-Level Semantic Mapping with RGB-D Cameras](./R2_Efficient%20Object-Level%20Semantic%20Mapping%20with%20RGB-D%20Cameras.pdf)

To autonomously navigate in real-world environments, mobile robots need to understand the scene completely, this requires the robots to not only perceive and map the world, but also recognize and interact with the surroundings, such as individual object instances.  In this paper, we present a semantic mapping system aiming to build a volumetric object-level map efficiently. Firstly, a frame-wise object segmentation scheme is proposed to segment 3D objects from RGB-D images. Then, the frame-segmented objects will be matched to the existing objects in the global map with an object association strategy to track and update object information. Finally, a voxel-based mapping system is extended to incorporate objects and create an object-level volumetric map. Experiments on indoor and logistic environment show that the proposed system achieves a better object segmentation performance than other object-level mapping methods while reducing the computational cost. 

<div align=center><img src="./README_Picture/R2_Mapping_Framework.png"/></div>
<div align=center><img src="./README_Picture/R2_Mapping_Result.png"/></div>


## 3. `Under Submission 2023` [Towards Autonomous Navigation for Agile Production System](./R3_Agiprobot_Towards%20Autonomous%20Navigation%20for%20Agile%20Production%20System.pdf)

Mobile robots in intra-logistic environments are tasked to deliver items from one place to another, this requires the robots to not only recognize and locate the items, but also design a collision-free path to transfer them. Therefore, a better understanding of the environment and a flexible navigation strategy is expected to promote industrial efficiency. In this paper, we extend the current 2D mapping and navigation framework with object segmentation and a fine position navigation strategy to achieve better performance on task-level navigation. Firstly, we create and maintain a hypermap to better represent the environment, where semantic objects are recognized and integrated into the existing 2D occupancy map. Then, a coarse-to-fine navigation strategy is proposed to drive mobile robots to accomplish the task and reach the goal precisely. A field experiment demonstrates that the proposed system can achieve high performance on autonomous navigation in an intra-logistic environment. 

<div align=center><img src="./README_Picture/R3_Navigation_Sim.png"/></div>
<div align=center><img src="./README_Picture/R3_Navigation_Result.png"/></div>


## 4. `Advanced Robotics 2022` [Structure SLAM with points plane and objects](./R4_Advance%20Robotics_Structure%20SLAM%20with%20points%20plane%20and%20objects.pdf)

Simultaneous localization and mapping (SLAM) is a fundamental problem for indoor mobile robots operating in unknown environments. While visual SLAM systems often use geometry features, the reconstructed maps lack semantic information. In this paper, we present a structure SLAM system with feature points, geometry planes, and semantic objects. Unlike other systems modelling planes and objects as collections of points, we choose a parametric representation for these landmarks. For every single frame, we start by generating cuboid candidates of detected objects with varying dimensions and orientations, then use 2D-3D fitting constraints to calculate the cuboid's translation, and finally introduce 3D spatial and 2D image constraints to select the best cuboid candidate. For SLAM optimization, the detected planes and objects can provide geometry constraints to improve the localization result, and act as landmarks to reconstruct a semantic map. Experiments on the ICL NUIM RGB-D dataset show that the proposed point-plane-object SLAM system can slightly improve localization accuracy, and is able to build a semantic map of the environment.

<div align=center><img src="./README_Picture/R4_SLAM_Object.png"/></div>
<div align=center><img src="./README_Picture/R4_SLAM_Result.png"/></div>

## 5. `SDM4FZI` [Digital Twin Implementation in Logistic Environments](./R5_Digital%20Twin%20Implementation%20in%20Logistic%20Environments.pdf)

The trend towards heterogeneous, decentral systems in intralogistics results in the need for a concept to describe and virtualize assets to enable their interaction. The multi-layer concept of Cyber-Physical Intralogistics Systems (CPIS) is introduced. The system description (descriptive layer) defines the structure of the digital twins and the communication (virtual layer) of physical (robots, periphery) and logical assets (control systems, simulations). To implement this concept, an experimental environment was developed at the Institute for Material Handling and Logistics and the Karlsruhe Institute of Technology. It consists of physical components, such as models of mobile robots or manipulators, and further periphery, such as racks and charging stations. The environment is supplemented by simulations and control software.

<div align=center><img src="./README_Picture/R5_Digital_Twin.png"/></div>

## 6. `CASE 2022` [Object-based Loop Closure with Oriented Histgram Descriptor](./R6_CASE2022_Object-based%20Loop%20Closure%20with%20Oriented%20Histgram%20Descriptor.pdf)

## 7. `MFI 2021` [Object-based Localization and Mapping with Bbox Constraints](./R7_MFI2021_Object-based%20Localization%20and%20Mapping%20with%20Bbox%20Constraints.pdf)

## 8. `ACDU` [Automatic Connection Device Underbody](./R8_ACDU_Automatic%20Connection%20Device%20Underbody.pdf)


# Bibliography

## * [Paper Survey on Object Detection](./Paper%20Survey%20on%20Object%20Detection.md)
## * [Paper Survey on Object Association](./Paper%20Survey%20on%20Object%20Association.md)
## * [Paper Survey on Object SLAM](./Paper%20Survey%20on%20Object%20SLAM.md)
## * [Paper Survey on Object Mapping](Paper%20Survey%20on%20Object%20Mapping.md)
## * [Paper Survey on Visual SLAM](./Paper%20Survey%20on%20Visual%20SLAM.md)
## * [Paper Survey on Plane SLAM](./Paper%20Survey%20on%20Plane%20SLAM.md)