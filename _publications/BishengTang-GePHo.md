---
title: "Generalized heterophily graph data augmentation for node classification"
collection: publications
category: manuscripts
permalink: /publication/2023-09-11-GePHo
excerpt: '**(GNN)** This paper is about graph neural networks.'
date: 2023-09-11
venue: 'Neural Networks'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0893608023005142'
citation: 'Bisheng, Tang. (2023). &quot;Generalized heterophily graph data augmentation for node classification.&quot; <i>Neural Networks</i>.'
---

Graph data augmentations have demonstrated remarkable performance on homophilic graph neural networks (GNNs). Nevertheless, when transferred to a heterophilic graph, these augmentations are less effective for GNN models and lead to reduced performance. To address this issue, we propose a unified augmentation approach called GePHo, a regularization technique for heterophilic graph neural networks based on self-supervised learning, leveraging graph data augmentation to acquire extra information to guide model learning. Specifically, we propose to generate a pseudo-homophily graph that is type-agnostic, enabling us to apply GePHo to both homophilic and heterophilic graphs. Then, we regularize the neighbors with a sharpening technique for data augmentation and generate the auxiliary pseudo-labels to classify the original GNN’s output, whose operations are to constrain the local and global node representation, respectively. Extensive experiments on three homophilic graph and six heterophilic graph datasets demonstrate the competitive effectiveness of GePHo in node classification task, and the ablation experiments verify the efficacy of our GePHo in graph data augmentation.
