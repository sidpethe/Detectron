# Detectron

This is a fork of the original Detectron platform provided by FAIR. It is meant to provide outputs in a format compatible with the KITTI evaluation script. 

Detectron is Facebook AI Research's software system that implements state-of-the-art object detection algorithms, including [Mask R-CNN](https://arxiv.org/abs/1703.06870). It is written in Python and powered by the [Caffe2](https://github.com/caffe2/caffe2) deep learning framework.

At FAIR, Detectron has enabled numerous research projects, including: [Feature Pyramid Networks for Object Detection](https://arxiv.org/abs/1612.03144), [Mask R-CNN](https://arxiv.org/abs/1703.06870), [Detecting and Recognizing Human-Object Interactions](https://arxiv.org/abs/1704.07333), [Focal Loss for Dense Object Detection](https://arxiv.org/abs/1708.02002), [Non-local Neural Networks](https://arxiv.org/abs/1711.07971), [Learning to Segment Every Thing](https://arxiv.org/abs/1711.10370), [Data Distillation: Towards Omni-Supervised Learning](https://arxiv.org/abs/1712.04440), [DensePose: Dense Human Pose Estimation In The Wild](https://arxiv.org/abs/1802.00434), and [Group Normalization](https://arxiv.org/abs/1803.08494).

## Installation Instructions
For information on requirements and installation of Detectron view the INSTALL.md file provided by FAIR. The updated code has no additional requirements.

## Related Repositories

This section contains links to some of the other repositories that may be useful in implementing Mask RCNN for use with KITTI and V-KITTI datasets.
1. [detectronRoot](https://github.com/sidpethe/detectronRoot.git) : Scripts for running Mask RCNN with detectron. 
2. [vkittiToKitti](https://github.com/sidpethe/vkittiToKitti.git): Converting the vkitti ground truth to kitti compatible ground truth. 

## Acknowledgements
A big thank you to everyone at FAIR for their amazing work with Mask RCNN and Detectron in general.

Most of this work was done in collaboration with Mina Henein, PhD candidate, ACRV and supervised by Prof. Viorela Ila. 

## Author
Sid Pethe is Master of Engineering(Mechatronics) from the Australian National University. 

Most of this work was undertaken in the course of his masters project, focusing on Instance Level Semantic Segmentation for Dynamic SLAM applications, at the Australian Centre for Robotic Vision and the Australian National University.
