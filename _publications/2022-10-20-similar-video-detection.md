---
title: "Framework Design for Similar Video Detection: A Graph-Based Video Clustering Approach"
collection: publications
category: conferences
permalink: /publication/2022-10-20-similar-video-detection
excerpt: 'This paper presents a graph-based video clustering approach for detecting similar videos, offering a novel strategy to identify and manage duplicated content efficiently.'
date: 2022-10-20
venue: '2022 International Symposium on Multidisciplinary Studies and Innovative Technologies (ISMSIT)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9932834'
citation: 'Al-Thani, N. F., Islam, A., Belhaouari, S. B., & Faramarzinia, S. (2022). &quot;Framework Design for Similar Video Detection: A Graph-Based Video Clustering Approach.&quot; In <i>2022 International Symposium on Multidisciplinary Studies and Innovative Technologies (ISMSIT)</i> (pp. 571--576). IEEE. https://doi.org/10.1109/ISMSIT56059.2022.9932834'
---

This conference paper addresses the challenge of detecting duplicated videos, a growing issue with significant social and economic impacts. The proposed framework efficiently identifies duplicated videos through a novel graph-based video clustering approach. The system scans videos to extract keyframes, generates their hash values, and matches these against an archive to detect duplicates.

The method enhances existing keyframe detection techniques by incorporating a window selection step to ensure smooth transitions between keyframes. Various hashing algorithms, including perceptual hashing, differential hashing, and average hashing, are employed to compare keyframes. Tested on the Partial Video Copy Detection (PVCD) dataset, which contains highly perturbed video versions, the proposed method achieved a 94% accuracy on a subset of the dataset.

Additionally, the paper introduces a graph-based architecture for clustering similar videos, allowing for an innovative search strategy that compares new videos with representative videos from each cluster. This approach significantly improves the efficiency of detecting and managing duplicated video content.
