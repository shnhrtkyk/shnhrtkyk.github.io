---
title: "IMAGE TO POINT CLOUD TRANSLATION USING CONDITIONAL GENERATIVE ADVERSARIAL NETWORK FOR AIRBORNE LIDAR DATA"
collection: publications
permalink: /publication/2021-07-07-paper-title-number-5
excerpt: 'This paper is about a novel generative model for Poiint Cloud generatation for airborne LiDAR data, using  deep learning method with VAE and GAN.'
date: 2021-06-24
venue: 'ISPRS 2020'
paperurl: 'https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/V-2-2021/169/2021/'
citation: 'Shinohara, T., Xiu, H., and Matsuoka, M.: IMAGE TO POINT CLOUD TRANSLATION USING CONDITIONAL GENERATIVE ADVERSARIAL NETWORK FOR AIRBORNE LIDAR DATA, ISPRS Ann. Photogramm. Remote Sens. Spatial Inf. Sci., V-2-2021, 169–174, https://doi.org/10.5194/isprs-annals-V-2-2021-169-2021, 2021.'
---
This study introduces a novel image to a 3D point-cloud translation method with a conditional generative adversarial network that creates a large-scale 3D point cloud. This can generate supervised point clouds observed via airborne LiDAR from aerial images. The network is composed of an encoder to produce latent features of input images, generator to translate latent features to fake point clouds, and discriminator to classify false or real point clouds. The encoder is a pre-trained ResNet; to overcome the difficulty of generating 3D point clouds in an outdoor scene, we use a FoldingNet with features from ResNet. After a fixed number of iterations, our generator can produce fake point clouds that correspond to the input image. Experimental results show that our network can learn and generate certain point clouds using the data from the 2018 IEEE GRSS Data Fusion Contest.

