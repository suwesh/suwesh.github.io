---
title: "RACECAR LiDAR Datasets"
excerpt: "Extraction and Pre-processing of LiDAR sensor data from a large open-source Multi-modal sensor dataset<br/><img src='/images/racecar-dataset-cover.png'>"
collection: portfolio
---

RACECAR multislow_poli
===
This dataset contains the 4D point cloud data from LiDAR sensors collected from fully autonomous and self-driving Indy race cars which raced in the Indy autonomous challenge. The dataset is in nuScenes format and is divided into 7,150 sweeps and 1,199 samples which contain fused sensor data from 3 LiDARs equipped by the vehicle. This dataset's scenario is PoliMove team’s Multi-Agent Slow on LVMS racetrack. Each .pcd file contains 4 dimensional data: (x,y,z) coordinates of the 3D space and intensity value for each point. Dataset is available at [huggingface](https://huggingface.co/datasets/suwesh/RACECAR-multislow_poli) and [kaggle](https://www.kaggle.com/datasets/suwesh/multislow-poli).

RACECAR LiDAR to BEV Map image labeled
===
Converted lidar point clouds(3D) into RGB bird's eye view images(2D) of the Racecar Dataset's multi-slow-poli race scenario. With labels for object (other racecars on the track) detection and trajectory generation/planning. The images are segmented scenes along space-time dimensions with each segmentation covering a scene history of 15 frames. Dataset is available at [huggingface](https://huggingface.co/datasets/suwesh/RACECAR-lidar-to-bev-image-labeled) and [kaggle](https://www.kaggle.com/datasets/suwesh/train-im-labeled).
