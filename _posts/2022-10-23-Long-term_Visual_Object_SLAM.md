---
title: 'ObVi-SLAM: Long-Term Object-Visual SLAM'
layout: post
banner: /images/chairs_estimation.png
category: project
excerpt: Long-term SLAM using objects and visual features
--- 

Accepted to IEEE Robotics and Automation Letters. 

Links: [[paper](https://arxiv.org/abs/2309.15268)], [[video](https://youtu.be/quJOgnEdaZ0)] [[github](https://github.com/ut-amrl/ObVi-SLAM)]

Collaborators: Amanda Adkins, Taijing Chen, [Joydeep Biswas](https://www.joydeepb.com)

Robots responsible for tasks over long time scales must be able to localize consistently and scalably amid geometric, viewpoint, and appearance changes. Existing visual SLAM approaches rely on low-level feature descriptors that are not robust to such environmental changes and result in large map sizes that scale poorly over long-term deployments. In contrast, object detections are robust to environmental variations and lead to more compact representations, but most object-based SLAM systems target short-term indoor deployments with close objects. In this paper, we introduce ObVi-SLAM to overcome these challenges by leveraging the best of both approaches. ObVi-SLAM uses low-level visual features for high-quality short-term visual odometry; and to ensure global, long-term consistency, ObVi-SLAM builds an uncertainty-aware long-term map of persistent objects and updates it after every deployment. By evaluating ObVi-SLAM on data from 16 deployment sessions spanning different weather and lighting conditions, we empirically show that ObVi-SLAM generates accurate localization estimates consistent over long-time scales in spite of varying appearance conditions. 

![ObVi-SLAM](/images/chairs_estimation.png) 

Please contact me if you're interested in learning more or using our work!

