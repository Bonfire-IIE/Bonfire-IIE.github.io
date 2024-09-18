---
title: "Unsupervised Graph Structure-Aided Personalized Federated Learning"
collection: publications
category: conferences
permalink: /publication/2023-09-30-FedSKA
excerpt: '**(Federated Learning)** This paper is about the graph personalized Federated Learning.'
date: 2023-09-30
venue: 'ECAI2023'
paperurl: 'https://www.semanticscholar.org/paper/Unsupervised-Graph-Structure-Assisted-Personalized-Li-Chen/8ec9fad64d46b6b49c9cc53d4935b76ec5acbbac'
citation: 'Xiaoying, Li. (2023). &quot;Unsupervised Graph Structure-Aided Personalized Federated Learning .&quot; <i>ECAI2023</i>.'
---


Non-IID data presents a significant challenge for federated learning(FL), and personalized FL is a natural solution to address this challenge. Recently, Graph Neural Network (GNN) has recently emerged to model the complex client relationship using a client graph to refine personalized models. However, this approach depends on an existing client relation graph on the server, making it impractical unless this prerequisite is satisfied. Furthermore, noisy and missing connections in the original graph structures can degrade personalization performance. In this work, we propose an unsupervised structure learning approach to improve personalized FL, where the server learns a dynamic client graph through self-supervision and generates structure-based client representations. These representations are then broadcasted to users, regulating local training using the learned knowledge as an inductive bias. Empirical studies on benchmark datasets demonstrate the significant effectiveness of our approach and the high quality of the client graphs. 
