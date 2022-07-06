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

[K-FAC](https://arxiv.org/abs/1503.05671) is an approximate second order optimization method that has been shown to speed up training convergence while achieving competitive performance when training logistic autoencoders, convolutional networks, and RNNs. Here, we apply K-FAC to the [MLP-Mixer](https://arxiv.org/abs/2105.01601) architecture, and demonstrate that (without pretraining) K-FAC outperforms SGD and Adam when performing CIFAR-100 image classification and when handling large input sizes on CIFAR-10. Additionally, we perform [learning rate grafting](https://arxiv.org/abs/2002.11803) to confirm that the implicit learning rate schedule is the primary factor dictating classification performance.

[[Project Report]](https://Salarios77.github.io/files/CSC2541_Project_Analyzing_KFAC_on_MLP_Mixer.pdf) [[Code]](https://github.com/Salarios77/kfac-mlp-mixer)

## Learning Heuristics for Minimum Latency Problem with RL and GNN
University of Toronto, MIE1666 <em>Machine Learning for Mathematical Optimization</em> (Fall 2021)

Recent work has successfully applied methods from reinforcement learning (RL) to derive domain-dependent heuristics for challenging combinatorial optimization problems from a set of training instances. We build on this idea and show how RL can be applied to the Minimum Latency Problem by using a graph attention network to encode a stochastic policy for constructively building partial paths, yielding solutions which are comparable to state-of-the-art, hand-engineered methods.

[[Project Report]](https://Salarios77.github.io/files/MIE1666_Final_Report.pdf) [[Code]](https://github.com/Salarios77/mie1666_project)

## Analyzing the Effect of Adversarial Inputs on Saliency Maps
University of Toronto, CSC413 <em>Neural Networks and Deep Learning</em> (Winter 2021)

[FGSM](https://arxiv.org/abs/1412.6572) is a method for generating adversarial examples by applying small perturbations to input images that can fool deep networks into making confident but incorrect predictions. In this work, saliency maps, namely [GradCam](https://arxiv.org/abs/1611.07450), [GuidedBackprop](https://arxiv.org/abs/1412.6806), and [SmoothGrad](https://arxiv.org/abs/1706.03825), were used to compare the salient features of the original images from CIFAR-10 and their adversarial counterparts engineered using FGSM. For both untargetted and targetted attacks, quantitative measurements of similarity demonstrated that GradCam was the most successful at detecting adversarial inputs.

[[Project Report]](https://Salarios77.github.io/files/CSC413_Project.pdf) [[Code]](https://github.com/Salarios77/csc413-project)

## Real-Time Face Mask Detector using a Faster-RCNN (FPN backbone) Architecture
University of Toronto, APS360 <em>Applied Fundamentals of Machine Learning</em> (Fall 2020)

[[Project Report]](https://Salarios77.github.io/files/final_report_aps360.pdf) [[Code]](https://github.com/Salarios77/face_mask_detector)

## Full visual odometry using single scale and transformation invariant feature detectors
University of Toronto, ROB501 <em>Computer Vision for Robotics</em> (Fall 2020)

[[Project Report]](https://Salarios77.github.io/files/ROB501_Feature_based_Visual_Odometry_Report.pdf) [[Code]](https://github.com/Salarios77/feature-based-stereo-visual-odometry)
