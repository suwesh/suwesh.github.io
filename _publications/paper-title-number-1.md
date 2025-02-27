---
title: "Parallel Neural Computing for Scene Understanding from LiDAR Perception in Autonomous Racing"
collection: research
permalink: /research/parallelneuralcomputing
excerpt: "Autonomous Racing, Computer Vision, Image Segmentation, Deep Learning, LiDAR Perception, Accelerated Computing<br/><img src='/images/ppn-cover.png'>"
date: 2024-12-21
venue: '12th International Conference on Intelligent Systems and Embedded Design'

paperurl: 'https://arxiv.org/abs/2412.18165'
citation: 'Suwesh Prasad Sah &quot;Parallel Neural Computing for Scene Understanding from LiDAR Perception in Autonomous Racing.&quot; <i>IEEE/ISED International Conference on Intelligent Systems and Embedded Design, 2024</i>'
---

Abstract: Autonomous driving in high-speed racing, as opposed to urban environments, presents significant challenges in scene understanding due to rapid changes in the track environment. Traditional sequential network approaches may struggle to meet the real-time knowledge and decision-making demands of an autonomous agent covering large displacements in a short time. This paper proposes a novel baseline architecture for developing sophisticated models capable of true hardware-enabled parallelism, achieving neural processing speeds that mirror the agent’s high velocity. The proposed model (Parallel Perception Network (PPN)) consists of two independent neural networks, segmentation and reconstruction networks, running parallelly on separate accelerated hardware. The model takes raw 3D point cloud data from the LiDAR sensor as input and converts it into a 2D Bird’s Eye View Map on both devices. Each network independently extracts its input features along space and time dimensions and produces outputs parallelly. The proposed method’s model is trained on a system with two NVIDIA T4 GPUs, using a combination of loss functions, including edge preservation, and demonstrates a 2x speedup in model inference time compared to a sequential configuration. Implementation is available at [github](https://github.com/suwesh/Parallel-Perception-Network). Learned parameters of the trained networks are provided at [huggingface](https://huggingface.co/suwesh/ParallelPerceptionNetwork).

