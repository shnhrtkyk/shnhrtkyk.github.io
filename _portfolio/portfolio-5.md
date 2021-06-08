---
title: "Point2color: 3D Point Cloud Colorization Using a Conditional Generative Network and Differentiable Rendering for Airborne LiDAR
"
date: 2021-06-01
excerpt: "Point2color <br/><img src='/images/Point2color.png'>"
collection: portfolio
---

Airborne LiDAR observations are very effective for providing accurate 3D point clouds, and archived data are becoming available to the public.  
In many cases, only geometric information is available in the published 3D point cloud observed by airborne LiDAR (airborne 3D point cloud), and geometric information alone is not readable.  
Thus, it is important to colorize airborne 3D point clouds to improve visual readability.  
A scheme for 3D point cloud colorization using a conditional generative adversarial network (cGAN) was proposed, but it is difficult to apply to airborne LiDAR because the method is for artificial CAD models.  
Since airborne 3D point clouds are spread over a wider area than simple CAD models, it is important to evaluate them spatially in two-dimensional (2D) images.  
Currently, the differentiable renderer is the most reliable method to bridge 3D and 2D images.
In this paper, we propose an airborne 3D point cloud colorization scheme called point2color using cGAN with points and rendered images.  
To achieve airborne 3D point cloud colorization, we estimate the color of each point with PointNet++ and render the estimated colored airborne 3D point cloud into a 2D image with a differentiable renderer.  
The network is then trained by minimizing the distance between real color and colorized fake color.  
The experimental results demonstrate the effectiveness of point2color using the IEEE GRSS 2018 Data Fusion Contest dataset with lower error than previous studies.  
Furthermore, an ablation study demonstrates the effectiveness of using a cGAN pipeline and 2D images via a differentiable renderer.  
Our code will be available at [https://github.com/shnhrtkyk/point2color](https://github.com/shnhrtkyk/point2color.)