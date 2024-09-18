---
title: "ACTSS: Input Detection Defense against Backdoor Attacks via Activation Subset Scanning"
collection: publications
category: conferences
permalink: /publication/2022-09-30-ACTSS
excerpt: '**(Backdoor Attacks)** This paper is about defense methods against backdoor attacks.'
date: 2022-09-30
venue: 'IJCNN2022'
paperurl: 'https://ieeexplore.ieee.org/document/9891900'
citation: 'Yuexin, Xuan. (2022). &quot;ACTSS: Input Detection Defense against Backdoor Attacks via Activation Subset Scanning.&quot; <i>IJCNN2022</i>.'
---

Deep neural networks are vulnerable to backdoor attacks where adversaries inject the trigger into partial training data to manipulate the trained model misclassification. In addition, the poisoned model behaves normally on clean inputs, and the malicious behavior only occurs when the secret trigger is present, making backdoor attacks hard to be detected. Most existing input detection methods leverage the link between triggers and outputs to reveal the poisoned inputs, which suffer from the trigger-size or the “all-to-all” attack scenario. We show that the internal activations produced by benign and poisoned inputs are significantly different in the poisoned model. In this paper, we propose a novel and run-time input detection algorithm, Activation Subset Scanning (ACTSS), which extracts the activations of incoming inputs and leverages an anomaly detection algorithm to identify malicious inputs. We search and score for the abnormal activation subset according to the statistical difference of activations between benign and poisoned data using nonparametric statistics technology. Extensive experiments are conducted on three public datasets: CIFAR10, GTSRB, and ImageNet, with three representative models. The results verify our approach's effectiveness and state-of-the-art performance, which achieve over 98% false rejection rate for different types of triggers.
