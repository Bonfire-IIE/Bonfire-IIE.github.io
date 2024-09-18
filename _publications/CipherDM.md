---
title: "CipherDM: Secure Three-Party Inference for Diffusion Model Sampling"
collection: publications
category: conferences
permalink: /publication/2024-09-18-CipherDM
excerpt: 'This paper is about secure inference for Diffusion Model sampling.'
date: 2024-09-18
venue: 'ECCV2024,Preprint'
paperurl: 'https://arxiv.org/abs/2409.05414'
citation: 'Xin, Zhao. (2024). &quot;CipherDM: Secure Three-Party Inference for Diffusion Model Sampling.&quot; <i>ECCV2024</i>.'
---

Diffusion Models (DMs) achieve state-of-the-art synthesis results in image generation and have been applied to various fields. However, DMs sometimes seriously violate user privacy during usage, making the protection of privacy an urgent issue. Using traditional privacy computing schemes like Secure Multi-Party Computation (MPC) directly in DMs faces significant computation and communication challenges. To address these issues, we propose CipherDM, the first novel, versatile and universal framework applying MPC technology to DMs for secure sampling, which can be widely implemented on multiple DM based tasks. We thoroughly analyze sampling latency breakdown, find time-consuming parts and design corresponding secure MPC protocols for computing nonlinear activations including SoftMax, SiLU and Mish. CipherDM is evaluated on popular architectures (DDPM, DDIM) using MNIST dataset and on SD deployed by diffusers. Compared to direct implementation on SPU, our approach improves running time by approximately $1.084\times \sim 2.328\times$, and reduces communication costs by approximately $1.212\times \sim 1.791\times$.
