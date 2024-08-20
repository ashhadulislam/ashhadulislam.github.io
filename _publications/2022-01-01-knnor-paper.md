---
title: "KNNOR: An Oversampling Technique for Imbalanced Datasets"
collection: publications
category: manuscripts
permalink: /publication/2022-01-01-knnor-paper
excerpt: 'This paper introduces KNNOR, a novel oversampling technique that addresses class imbalance in datasets. The method focuses on enhancing the predictive performance of ML models by ensuring a more reliable augmentation of the minority class, overcoming issues such as within-class imbalance and the small disjunct problem.'
date: 2022-01-01
venue: 'Applied Soft Computing'
slidesurl: 'http://ashhadulislam.github.io/files/slides_knnor.pdf'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S1568494621010942'
citation: 'Islam, A., Belhaouari, S. B., Rehman, A. U., & Bensmail, H. (2022). &quot;KNNOR: An Oversampling Technique for Imbalanced Datasets.&quot; <i>Applied Soft Computing</i>, 115, 108288. https://doi.org/10.1016/j.asoc.2021.108288'
---

This paper presents a novel approach to addressing class imbalance in datasets, which is critical for improving the predictive performance of Machine Learning (ML) models. The K-Nearest Neighbor OveRsampling approach (KNNOR) proposed in this study characterizes the compactness of imbalanced datasets by utilizing each minority data point and its k-nearest neighbors to generate synthetic data points. This method effectively mitigates noise and outlier issues while ensuring a balanced representation of classes.

KNNOR is compared with ten contemporary oversampling techniques, consistently outperforming them in enhancing classifier accuracy across various imbalanced datasets. The technique is easy to implement and has been made available as an open-source Python library for the broader ML community.