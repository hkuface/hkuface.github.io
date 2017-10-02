---
layout: page
title: "Objectives"
description: "Objectives of our FYP"
header-img: "img/home-bg.jpg"
---


$\title{Objectives}$
Our project mainly contains two objectives.


$\section{Automatic filtering}$

Dataset is essential for training classifiers either in convolutional neural network or in traditional machine learning algorithms. This project aims at inventing ageneral face dataset generating procedure, where the filtering part will be innovative in the literature. A large-scale face dataset called HKU-Face will be produced through our method. 



$\section{Metric Learning}$


Metric learning is the task of learning a distance function over objects and is superior for solving open-set face recognition problem. 


metric learning model firstly map the input to a general feature $h$ which theoretically lies in a hyperspace manifold\cite{lee2003video}. Then training a discriminator $D$ to accomplish the task 
%\begin{center}
\[   
D(h_i, h_j) = 
     \begin{cases}
       0, & \text{if $h_i$, $h_j$ do not belong to the same identity} \\
       1, & \text{if $h_i$, $h_j$ belong to the same identity} \\
      
     \end{cases}
\]
%\end{center}


(2) Use the newly-developed or existed dataset to train existed metric learning model and a newly-designed model to achieve satisfying or even state-of-the-art performance.