---
title: "Roger: A Round Optimized GPU-Friendly Secure Inference Framework"
collection: publications
category: conferences
permalink: /publication/2024-06-09-Roger
excerpt: '**(MPC)** This paper is about the secure inference.'
date: 2024-06-09
venue: 'ICC2024'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10622609'
citation: 'Xudong, Chen. (2024). &quot;Roger: A Round Optimized GPU-Friendly Secure Inference Framework.&quot; <i>ICC2024</i>.'
---

Secure neural network inference provides a promis ing solution to preserve the privacy of Deep Learning as a Service (DLaaS), but its substantial communication and com putation overhead remain challenging. Recent works such as GForce and Piranha have introduced GPU-friendly secure inference protocols with improved computation efficiency, yet these approaches are either limited to supporting specialized trained networks or expensive in communication. As a conse quence, there remain potential improvements in functionalities and communication efficiency. To address the above challenges, we introduce Roger, a two party secure inference framework with semi-honest security, designed to support general neural network inference with a reduced number of round complexity. Drawing inspiration from ABY2.0, we propose the Partial-Fix technology, which fixes the share of one participant during the offline phase to improve its computation efficiency. Then, an online communication-free protocol for secure linear layer computation and a constant-round secure comparison protocol are proposed upon Partial-Fix. Imple mented on top of Piranha, the experiments demonstrate that for the CIFAR10 dataset, a single inference on VGG16 requires only 0.40 seconds. In comparison to GForce (resp. Piranha), Roger at least achieves 1.20× (resp. 1.94×) improvement in LAN setting in terms of throughput.
