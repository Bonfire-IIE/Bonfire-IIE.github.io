---
title: "Rethinking the Feature Iteration Process of Graph Convolution Networks"
collection: publications
category: conferences
permalink: /publication/2022-08-18-Rethinking
excerpt: '**(GNN)** This paper is about graph neural networks.'
date: 2022-08-18
venue: 'IJCNN2022'
paperurl: 'https://ieeexplore.ieee.org/document/9892737'
citation: 'Bisheng, Tang. (2023). &quot;Rethinking the Feature Iteration Process of Graph Convolution Networks.&quot; <i>IJCNN2022</i>.'
---

Node classification is a fundamental research problem in graph neural networks(GNNs), which uses node's feature and label to capture node embedding in a low dimension. The existing graph node classification approaches mainly focus on GNNs from global and local perspectives. The relevant research is relatively insufficient for the micro perspective, which refers to the feature itself. In this paper, we prove that deeper GCNs' features will be updated with the same coefficient in the same dimension, limiting deeper GCNs' expression. To overcome the limits of the deeper GCN model, we propose a zero feature (k-ZF) method to train GCNs. Specifically, k-ZF randomly sets the initial k feature value to zero, acting as a data rectifier and augmenter, and is also a skill equipped with GCNs models and other GCNs skills. Extensive experiments based on three public datasets show that k-ZF significantly improves GCNs in the feature aspect and achieves competitive accuracy.
