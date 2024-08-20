---
title: "Neural Network Optimization with Weight Evolution"
collection: publications
category: conferences
permalink: /publication/2023-07-12-neural-network-optimization-weight-evolution
excerpt: 'This paper presents a novel approach to neural network optimization through weight evolution, achieving higher compression with minimal loss of accuracy compared to traditional magnitude pruning methods.'
date: 2023-07-12
venue: 'ICML 2023 Workshop Neural Compression: From Information Theory to Applications'
paperurl: 'https://openreview.net/forum?id=b9NAEAUpd1'
citation: 'Belhaouari, S. B., & Islam, A. (2023). &quot;Neural Network Optimization with Weight Evolution.&quot; In <i>ICML 2023 Workshop Neural Compression: From Information Theory to Applications</i>.'
---

This paper introduces a new method for neural network optimization that emphasizes the evolution of weights throughout the training process, rather than focusing solely on magnitude pruning, which typically removes insignificant parameters at the end of training. The proposed approach tracks the importance of each parameter from the start of training to the final epoch, calculating a weighted average that prioritizes values closer to the completion of training.

Experiments conducted on popular deep neural networks such as AlexNet, VGGNet, ResNet, and DenseNet, using benchmark datasets like CIFAR10 and Tiny ImageNet, demonstrate that this method can achieve higher levels of compression with less accuracy loss compared to traditional magnitude pruning techniques. This research was presented at the ICML 2023 Workshop on Neural Compression: From Information Theory to Applications, contributing to the ongoing development of more efficient neural network models.
