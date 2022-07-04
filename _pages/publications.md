---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## [SLIC: Self-Supervised Learning with Iterative Clustering for Human Action Videos](https://rvl.cs.toronto.edu/video-similarity/#)
Published in <em>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</em>, 2022

What’s a good way to select positives and negatives for self-supervised contrastive learning of video representations? In our paper, we analyze the idea of alternating between clustering and contrastive learning of video representations, using pseudolabels from clustering to improve the selection of positive and negative video examples for contrastive learning. This leads to significantly better retrieval of human action videos and similar accuracy on downstream classification tasks compared to existing self-supervised video representation learning methods.

[[Project Page]](https://rvl.cs.toronto.edu/video-similarity/#) [[Arxiv]](https://arxiv.org/abs/2206.12534) [[Code]](https://github.com/rvl-lab-utoronto/video_similarity_search)
