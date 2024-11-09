---
title: "Comparing Federated Gradient Descent and Stochastic Gradient Descent for Modelling Housing Value Prediction"
excerpt: "Project paper prepared for CS-E4740 - Federated Learning course. <br/><img src='/images/output_clus.png' width='1000px' height='auto'>"
collection: portfolio
---

This paper investigates the use of Federated Learning (FL) to improve pricing models in decentralized settings. By utilizing the California Housing dataset, we cluster data based on geographical features to form distinct local datasets, ensuring data privacy. Each cluster corresponds to a local dataset, analogous to real estate agencies in a real-world scenario. We act as a marketplace website, aiding these agencies in their pricing processes. We implement Federated Gradient Descent (FedGD) and Federated Stochastic Gradient Descent (FedSGD) techniques, formulated as a Generalized Total Variation Minimization (GTVMin) problem, to enable efficient parameter sharing among local models. Our results show that FedGD consistently outperforms FedSGD, making it the preferred method in our FL framework. Additionally, our findings reveal that the FL approach significantly surpasses the benchmark linear regression model trained on the entire dataset in terms of performance.

Link to paper: [arXiv](https://arxiv.org/abs/2106.00000)
