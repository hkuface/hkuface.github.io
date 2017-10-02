---
layout: page
title: "Objectives"
description: "Objectives of our FYP"
header-img: "img/home-bg.jpg"
---


### Automatic filtering


Dataset is essential for training classifiers either in convolutional neural network or in traditional machine learning algorithms. This project aims at inventing ageneral face dataset generating procedure, where the filtering part will be innovative in the literature. A large-scale face dataset called HKU-Face will be produced through our method. 



### Metric Learning


Metric learning is the task of learning a distance function over objects and is superior for solving open-set face recognition problem. Metric learning model firstly map the input to a general feature $h$ which theoretically lies in a hyperspace manifold[1]. Then training a discriminator $D$ to accomplish the task 

$$

D(h_i,h_j) =
\begin{cases}
0 \; & \text{if $h_i$, $h_j$ do not belong to the same identity} \\
1 \; & \text{if $h_i$, $h_j$ belong to the same identity}
\end{cases}

$$

In our project, we will use the newly-developed or existed dataset to train existed metric learning model and a newly-designed model to achieve satisfying or even state-of-the-art performance.


### Reference

[1] K.-C. Lee, J. Ho, M.-H. Yang, and D. Kriegman, “Video-based face recognition using proba- bilistic appearance manifolds,” in Computer vision and pattern recognition, 2003. proceedings. 2003 ieee computer society conference on, vol. 1. IEEE, 2003, pp. I–I.


