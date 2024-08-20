---
title: "Multi-Cluster Jumping Particle Swarm Optimization for Fast Convergence"
collection: publications
category: manuscripts
permalink: /publication/2020-01-01-multi-cluster-jumping-pso
excerpt: 'This paper introduces the Multi-Cluster Jumping Particle Swarm Optimization (PSO) algorithm, designed to address the limitations of classical PSO by improving convergence speed and avoiding local minima, particularly in high-dimensional data spaces.'
date: 2020-01-01
venue: 'IEEE Access'
slidesurl: 'http://ashhadulislam.github.io/files/slides_multi_cluster_jumping_pso.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9223747'
citation: 'Rehman, A. U., Islam, A., & Belhaouari, S. B. (2020). &quot;Multi-Cluster Jumping Particle Swarm Optimization for Fast Convergence.&quot; <i>IEEE Access</i>, 8, 189382--189394. https://doi.org/10.1109/ACCESS.2020.3031003'
---

This paper presents the Multi-Cluster Jumping Particle Swarm Optimization (PSO) algorithm, a novel approach designed to enhance the convergence speed of traditional PSO, particularly in high-dimensional data environments. The classical PSO technique, while effective, often suffers from slow convergence rates and can become trapped in local minima as the dimensionality of the data increases.

The proposed Multi-Cluster Jumping PSO method divides the swarm into multiple clusters, each with its own best position, and uses inter-cluster communication to locate the global best solution. To prevent particles from getting stuck in local optima, a jumping strategy is introduced, allowing particles to relocate to new positions. Additionally, the algorithm employs a semi-random initialization method, distributing particles across the search space in a more structured manner.

Extensive experimentation on twelve benchmark functions demonstrates that the Multi-Cluster Jumping PSO significantly outperforms existing state-of-the-art approaches in terms of convergence speed, making it a robust solution for optimizing high-dimensional, dynamic data.
