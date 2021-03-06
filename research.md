---
layout: page
title: Research
permalink: /research/
---

## Current Research

##### 6-DOF Localization of UAVs in very cluttered and GPS-denied environments

ToDo.

***

##### 3D object detection via multi-modal sensor fusion from autonomous UAVs
I am currently working on 3D object detection on an embedded platform, which is intended to reside on a UAV. The project has 3 parts; 1) object detection using 3D information (depth image, point cloud etc.), 2) fusion of multi-modal sensor information, and 3) building a framework that runs on a UAV real-time.

<img alt="Voxelgrid of a bedroom scene" src="/images/project_imgs/bedroom_croped.png" title="Voxelgrid of a bedroom scene" height="160">
<img alt="Voxelgrid of the bed in the bedroom scene" src="/images/project_imgs/bed_croped.png" title="Voxelgrid of the bed in the bedroom scene" height="160">
<img alt="Voxelgrid of a chair object that we captured with Google Tango tablet" src="/images/project_imgs/chair3.png" title="Voxelgrid of a chair object that we captured with Google Tango tablet" height="160">

<img alt="ConvNet architecture for 3D object detection" src="/images/convnet_detector.png" title="ConvNet architecture for 3D object detection">

Above architecture does not represent the updated method, which works similar to SSD.


***

##### 3D vision based autonomous drone guidance framework
I am building a vision based autonomous UAV guidance framework. This project consists of the indoor control of a UAV and integrating various computer vision algorithms to the guidance scheme of the UAV for higher level autonomous mission execution.

<iframe width="560" height="315" src="https://www.youtube.com/embed/8WUousk9y-Y" frameborder="0" allowfullscreen></iframe>


***

##### Heat Mapping Drones
The efficiency of thermal insulation of buildings has direct impact on power consumption for heating and ventilation. Thermal leaks are critical defects on building insulation. IR
sensitive handheld thermal cameras are commonly used to perform manual inspection of buildings to detect thermal leaks by human experts. In this project, we are building a framework that autonomously detect heat leakages from thermal images of building structures, captured either from inside or outside. We are using an actual drone captures in our experiments.

<img alt="Heat mapping drone" src="/images/project_imgs/thermal/drone.jpg" title="Heat mapping drone" height="120">
<img alt="Color image" src="/images/project_imgs/thermal/722_p.jpg" title="Color image" height="120">
<img alt="Thermal image" src="/images/project_imgs/thermal/722_i.jpg" title="Thermal image" height="120">
<img alt="Detected leakage region" src="/images/project_imgs/thermal/722_l.jpg" title="Detected leakage region" height="120">



## Conference Papers

##### Obstacle Detection and Identification with Portable Uncalibrated Structured Light (2018)
M.L. Scalzo, Y. Zheng, **B. Kakillioglu**, S. Velipasalar (Under Review)

***

##### Autonomous altitude measurement and landing area detection for indoor UAV applications (2016) [[paper]](http://ieeexplore.ieee.org/abstract/document/7738069) [code]

Fully autonomous navigation of unmanned vehicles, without relying on pre-installed tags or markers, still remains a challenge especially for GPS-denied areas and complex indoor environments. Robust altitude control and safe landing zone detection are two important tasks for indoor unmanned aerial vehicle (UAV) applications. In this paper, a novel approach is proposed for indoor UAVs to control their altitudes, and autonomously detect safe landing zones without relying on any markers, special setups, or assuming that the environment is known. The proposed method employs both depth data and RGB images to detect and also track the safe landing zones.

<img alt="Distance vectors to segmented planes" src="/images/resimgs/vectors.png" height="90" title="Distance vectors to segmented planes: Vector to the ground is the altitude vector"> <img alt="Landing zone detection on cluttered surefaces" src="/images/resimgs/cluttered3.png" height="90" title="Landing zone detection on cluttered surefaces"> <img alt="Landing zone detection on multiple levels" src="/images/resimgs/4.png" height="90" title="Landing zone detection on multiple levels">

```
@inproceedings{kakillioglu2016autonomous,
  title={Autonomous altitude measurement and landing area detection for indoor UAV applications},
  author={Kakillioglu, Burak and Velipasalar, Senem},
  booktitle={Advanced Video and Signal Based Surveillance (AVSS), 2016 13th IEEE International Conference on},
  pages={166--172},
  year={2016},
  organization={IEEE}
}
```

***

##### Doorway detection for autonomous indoor navigation of unmanned vehicles (2016) [[paper]](http://ieeexplore.ieee.org/abstract/document/7533078) [code]
Fully autonomous navigation of unmanned vehicles, without relying on pre-installed tags or markers, still remains a challenge for GPS-denied areas and complex indoor environments. Doors are important for navigation as the entry/exit points. A novel approach is proposed to autonomously detect™ doorways by using the Project Tango platform. We first detect the candidate door openings from the 3D point cloud, and then use a pre-trained detector on corresponding RGB image regions to verify if these openings are indeed doors. We employ Aggregate Channel Features for detection, which are computationally efficient for real-time applications. Since detection is only performed on candidate regions, the system is more robust against false positives. The approach can be generalized to recognize windows, some architectural structures and obstacles. Experiments show that the proposed method can detect open doors in a robust and efficient manner.

<img alt="The observed scene" src="/images/resimgs/detected_door_visual.png" height="110" title="The observed scene"> <img alt="Detected candidate" src="/images/resimgs/fig2b.jpg" height="110" title="Detected candidate opening displayed in red"> <img alt="Doorway detection example" src="/images/resimgs/pos2.jpg" height="110" title="Doorway detection example. Blue, red and green boxes represent the candidate region, its padded version and the detected door, respectively.">

```
@inproceedings{kakillioglu2016doorway,
  title={Doorway detection for autonomous indoor navigation of unmanned vehicles},
  author={Kakillioglu, Burak and Ozcan, Koray and Velipasalar, Senem},
  booktitle={Image Processing (ICIP), 2016 IEEE International Conference on},
  pages={3837--3841},
  year={2016},
  organization={IEEE}
}
```
