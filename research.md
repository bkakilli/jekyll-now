---
layout: page
title: Research
permalink: /research/
---

## Conference Papers

##### Heat Leakage Detection from Thermal Images for Autonomous Aerial Building Inspection (2017)
(Under Revision)

##### Autonomous altitude measurement and landing area detection for indoor UAV applications (2016) [[paper]](http://ieeexplore.ieee.org/abstract/document/7738069) [code]

Fully autonomous navigation of unmanned vehicles, without relying on pre-installed tags or markers, still remains a challenge especially for GPS-denied areas and complex indoor environments. Robust altitude control and safe landing zone detection are two important tasks for indoor unmanned aerial vehicle (UAV) applications. In this paper, a novel approach is proposed for indoor UAVs to control their altitudes, and autonomously detect safe landing zones without relying on any markers, special setups, or assuming that the environment is known. The proposed method employs both depth data and RGB images to detect and also track the safe landing zones.
![Distance vectors to segmented planes](/images/resimgs/vectors.png "Distance vectors to segmented planes: Vector to the ground is the altitude vector.")
![Landing zone detection on cluttered surefaces](/images/resimgs/cluttered3.png "Landing zone detection on cluttered surefaces")
![Landing zone detection on multiple levels](/images/resimgs/4.png "Landing zone detection on multiple levels")

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

##### Doorway detection for autonomous indoor navigation of unmanned vehicles (2016) [[paper]](http://ieeexplore.ieee.org/abstract/document/7533078) [code]
Fully autonomous navigation of unmanned vehicles, without relying on pre-installed tags or markers, still remains a challenge for GPS-denied areas and complex indoor environments. Doors are important for navigation as the entry/exit points. A novel approach is proposed to autonomously detect™ doorways by using the Project Tango platform. We first detect the candidate door openings from the 3D point cloud, and then use a pre-trained detector on corresponding RGB image regions to verify if these openings are indeed doors. We employ Aggregate Channel Features for detection, which are computationally efficient for real-time applications. Since detection is only performed on candidate regions, the system is more robust against false positives. The approach can be generalized to recognize windows, some architectural structures and obstacles. Experiments show that the proposed method can detect open doors in a robust and efficient manner.
![The observed scene](/images/resimgs/detected_door_visual.png "The observed scene")
![Detected candidate](/images/resimgs/fig2b.jpg "Detected candidate opening displayed in red")
![Doorway detection example](/images/resimgs/pos2.jpg "Doorway detection example. Blue, red and green boxes represent the candidate region, its padded version and the detected door, respectively.")

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
