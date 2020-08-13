---
title: "Surface Modeling for Airborne Lidar"
collection: publications20
permalink: /publication/lidar-surface-model
excerpt: 'We use lidar points and scan ray data to learn a lidar surface model that can be used to estimate novel points from single scans.'
date: 2020-09-26
venue: 'IEEE International Geoscience and Remote Sensing Symposium'

citation: 'Hunter Blanton, Sean Grate, Nathan Jacobs. "Surface Modeling for Airborne Lidar", IEEE International Geoscience and Remote Sensing Symposium. IEEE, 2020.'
---

# Abstract
Repeat-visit airborne lidar is a powerful tool for change detection in urban and rural environments. In this work, we present a learning-based approach that addresses one of the key challenges in comparing point cloud scans of the same region: handling geometric differences caused by varying sensor position. Our approach is to perform shape modeling through ray casting with a point cloud neural network. Recent work on learning-based shape modeling has been based on the assumption that an explicit surface representation is available, which is not the case for airborne lidar datasets. Our key insight is that by using a ray casting approach we can perform shape modeling directly with lidar measurements. We evaluate our method both quantitatively and qualitatively on learned surface accuracy and show that our method correctly predicts surface intersection even in sparse regions of the input cloud.

<iframe width="1280" height="720" src="https://www.youtube.com/embed/qaXwxFcATIk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
