---
title: "Privacy and Accuracy Implications of Model Complexity and Integration in Heterogeneous Federated Learning"
collection: publications
permalink: /publication/2025-Privacy
date: 2025-02-27
venue: 'IEEE Access'
paperurl: 'http://negedng.github.io/files/2025-Privacy.pdf'
citation: 'Németh, G. D., Lozano, M. A., Quadrianto, N., & Oliver, N. (2025). &quot; Privacy and Accuracy Implications of Model Complexity and Integration in Heterogeneous Federated Learning&quot; <i>IEEE Access</i> 10.1109/ACCESS.2025.3546478'
---
Federated Learning (FL) has been proposed as a privacy-preserving solution for distributed machine learning, particularly in heterogeneous FL settings where clients have varying computational capabilities and thus train models with different complexities compared to the server’s model. However, FL is not without vulnerabilities: recent studies have shown that it is susceptible to membership inference attacks (MIA), which can compromise the privacy of client data. In this paper, we examine the intersection of these two aspects, heterogeneous FL and its privacy vulnerabilities, by focusing on the role of client model integration, the process through which the server integrates parameters from clients’ smaller models into its larger model. To better understand this process, we first propose a taxonomy that categorizes existing heterogeneous FL methods and enables the design of seven novel heterogeneous FL model integration strategies. Using CIFAR-10, CIFAR-100, and FEMNIST vision datasets, we evaluate the privacy and accuracy trade-offs of these approaches under three types of MIAs. Our findings reveal significant differences in privacy leakage and performance depending on the integration method. Notably, introducing randomness in the model integration process enhances client privacy while maintaining competitive accuracy for both the clients and the server. This work provides quantitative light on the privacy-accuracy implications client model integration in heterogeneous FL settings, paving the way towards more secure and efficient FL systems.
[Download paper here](http://negedng.github.io/files/2022-Snapshot.pdf)
