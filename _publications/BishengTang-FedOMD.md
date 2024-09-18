---
title: "Graph Federated Learning with Center Moment Constraints for Node Classification"
collection: publications
category: conferences
permalink: /publication/2024-08-12-FedOMD
excerpt: '**(Graph)** This paper is about Graph Federated Learning.'
date: 2024-08-12
venue: 'ICPP2024'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3677333.3678159'
citation: 'Bisheng, Tang. (2024). &quot;Graph Federated Learning with Center Moment Constraints for Node Classification.&quot; <i>ICPP2024</i>.'
---

Centralized learning graph-structured data representation commonly exists in various institutions, while it is challenging to learn other institutions’ graph-structured data representations without data leakage. Federated learning (FL) is proposed to federally learn a global model while keeping data privacy and security. However, FL is notorious for the non-i.i.d data. The existing works aim to form an undivided graph by linking all party subgraphs while neglecting the local non-i.i.d feature in the training phase. To this end, we propose a novel graph FL framework called FedOMD to leverage global independent and identically distributed (i.i.d) hidden feature representation to guide the local graph model training. Specifically, We first model each local feature as a Gaussian distribution to decrease the representation discrepancy in different parties and then calculate a global Gaussian distribution in the server. Finally, we use central moment discrepancy to minimize the distance between the party local and the server global distribution. With such distribution constraints, all parties can train the graph model in a unified feature space. Our extensive experiments on five datasets have manifested the competitive effectiveness of FedOMD over the seven mentioned FL models. The relevant ablation and sensitivity analysis also verify the effectiveness of FedOMD. @octocat :+1: This PR looks great - it's ready to merge! :shipit:
