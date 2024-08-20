---
title: 'Balancing Regression Datasets with KNNOR-Reg Oversampling Technique'
date: 2024-06-20
permalink: /posts/2024/06/balancing-regression-datasets/
tags:
  - Data Science
  - Machine Learning
  - Regression
  - Augmentation
---

Enhancing model performance in machine learning often begins with addressing the quality of your data. One of the most challenging issues is the imbalance in the target variable distribution, which can severely impact the accuracy of regression models. 

Consider a scenario where your dataset includes 9900 data points for typical house prices and only 100 data points for luxury house prices. A regression model trained on such data is likely to underpredict luxury house prices due to the overwhelming presence of typical prices, despite seemingly good performance on average.

To address this issue, my colleagues Dr. Khelil, Dr. Samir, Dr. Ala, Dr. Abdulsalam, and I at Hamad Bin Khalifa University and the Geneva School of Economics and Management have developed a novel data augmentation algorithm: KNNOR-Reg. This technique changes the distribution of minority data points based on specific parameters, enhancing the model's ability to make accurate predictions in imbalanced regression problems.

To read the entire article, [visit the link](https://ashhadulislam.medium.com/balancing-regression-datasets-f1b0e05f9cdf).
