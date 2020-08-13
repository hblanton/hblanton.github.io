---
title: "Extending Absolute Pose Regression to Multiple Scenes"
collection: publications20
permalink: /publication/mspn
excerpt: 'We extend PoseNet for localization in several scenes using a single CNN.'
date: 2020-06-14
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops'
paperurl: 'http://openaccess.thecvf.com/content_CVPRW_2020/papers/w3/Blanton_Extending_Absolute_Pose_Regression_to_Multiple_Scenes_CVPRW_2020_paper.pdf'
citation: 'Blanton, Hunter, et al. "Extending Absolute Pose Regression to Multiple Scenes." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops. 2020.'
---

# Abstract
Direct pose regression using deep convolutional neural networks has become a highly active research area. However, even with significant improvements in performance in recent years, the best performance comes from training distinct, scene-specific networks. We propose a novel architecture, Multi-Scene PoseNet (MSPN), that allows for a single network to be used on an arbitrary number of scenes with only a small scene-specific component. Using our approach, we achieve competitive performance for two benchmark 6DOF datasets, Microsoft 7Scenes and Cambridge Landmarks, while reducing the total number of network parameters significantly. Additionally, we demonstrate that our trained model serves as a better initialization for fine-tuning on new scenes compared to the standard ImageNet initialization, converging to lower error solutions within only a few epochs.

<iframe width="1280" height="720" src="https://www.youtube.com/embed/CeYArlXR_9E" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
