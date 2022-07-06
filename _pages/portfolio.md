---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

<!--
{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
-->

## Analyzing the Effectiveness of K-FAC on Training MLP-Mixers for Image Classification
University of Toronto, CSC2541 <em>Neural Network Training Dynamics</em> (Winter 2022)

([K-FAC](https://arxiv.org/abs/1503.05671)) is an approximate second order optimization method that has been shown to speed up training convergence while achieving competitive performance when training logistic autoencoders, convolutional networks, and RNNs. Here, we apply K-FAC to the [MLP-Mixer](https://arxiv.org/abs/2105.01601) architecture, and demonstrate that (without pretraining) K-FAC outperforms SGD and Adam when performing CIFAR-100 image classification and when handling large input sizes on CIFAR-10. Additionally, we perform [learning rate grafting](https://arxiv.org/abs/2002.11803) to confirm that the implicit learning rate schedule is the primary factor dictating classification performance.

[[Project Report]](https://Salarios77.github.io/files/CSC2541_Project_Analyzing_KFAC_on_MLP_Mixer.pdf) [[Code]](https://github.com/Salarios77/kfac-mlp-mixer)

## Learning Heuristics for Minimum Latency Problem with RL and GNN
University of Toronto, MIE1666 <em>Machine Learning for Mathematical Optimization</em> (Fall 2021)

[[Project Report]](https://Salarios77.github.io/files/MIE1666_Final_Report.pdf) [[Code]](https://github.com/Salarios77/mie1666_project)

## Analyzing the Effect of Adversarial Inputs on Saliency Maps
University of Toronto, CSC413 <em>Neural Networks and Deep Learning</em> (Winter 2021)

[[Project Report]](https://Salarios77.github.io/files/CSC413_Project.pdf) [[Code]](https://github.com/Salarios77/csc413-project)

## Real-Time Face Mask Detector using a Faster-RCNN (FPN backbone) Architecture
University of Toronto, APS360 <em>Applied Fundamentals of Machine Learning</em> (Fall 2020)

[[Project Report]](https://Salarios77.github.io/files/final_report_aps360.pdf) [[Code]](https://github.com/Salarios77/face_mask_detector)

## Full visual odometry using single scale and transformation invariant feature detectors
University of Toronto, ROB501 <em>Computer Vision for Robotics</em> (Fall 2020)

[[Project Report]](https://Salarios77.github.io/files/ROB501_Feature_based_Visual_Odometry_Report.pdf) [[Code]](https://github.com/Salarios77/feature-based-stereo-visual-odometry)
