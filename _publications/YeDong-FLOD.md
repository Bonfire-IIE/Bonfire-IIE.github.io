---
title: "FLOD:Oblivious Defender for Private Byzantine-Robust Federated Learning with Dishonest-Majority"
collection: publications
category: conferences
permalink: /publication/2021-10-04-FLOD
excerpt: '**(MPC)** This paper is about the private inference for Federated Learning.'
date: 2021-10-04
venue: 'ESORICS 2021'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-88418-5_24'
citation: 'Ye, Dong. (2023). &quot;FLOD:Oblivious Defender for Private Byzantine-Robust Federated Learning with Dishonest-Majority.&quot; <i>ESORICS 2021</i>.'
---

Privacy and Byzantine-robustness are two major concerns of
 federated learning (FL), but mitigating both threats simultaneously is
 highly challenging: privacy-preserving strategies prohibit access to indi
vidual model updates to avoid leakage, while Byzantine-robust methods
 require access for comprehensive mathematical analysis. Besides, most
 Byzantine-robust methods only work in the honest-majority setting.
 We present FLOD, a novel oblivious defender for private Byzantine
robust FL in dishonest-majority setting. Basically, we propose a novel
 Hamming distance-based aggregation method to resist > 1 2 Byzantine
 attacks using a small root-dataset and server-model for bootstrapping
 trust. Furthermore, we employ two non-colluding servers and use ad
ditive homomorphic encryption (AHE) and secure two-party computa
tion (2PC) primitives to construct e cient privacy-preserving building
 blocks for secure aggregation, in which we propose two novel in-depth
 variants of Beaver Multiplication triples (MT) to reduce the overhead
 of Bit to Arithmetic (Bit2A) conversion and vector weighted sum aggre
gation (VSWA) signi cantly. Experiments on real-world and synthetic
 datasets demonstrate our e ectiveness and e ciency: (i) FLOD defeats
 known Byzantine attacks with a negligible e ect on accuracy and con
vergence, (ii) achieves a reduction of 2 for o ine (resp. online) over
head of Bit2A and VSWA compared to ABY-AHE (resp. ABY-MT) based
 methods (NDSS15), (iii) and reduces total online communication and
 run-time by 167-1416 and 31-74 compared to FLGUARD.
