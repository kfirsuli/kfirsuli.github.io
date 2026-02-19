---
title: "Quantum-secure multiparty deep learning"
authors:
  - Kfir Sulimany
  - Sri Vadlamani
  - Ryan Hamerly
  - Prahlad Iyengar
  - Dirk Englund
date: "2025-01-01"
publication_types: ["article-journal"]
publication: "*Physical Review X*"
abstract: "Secure multiparty computation enables the joint evaluation of multivariate functions across distributed users while ensuring the privacy of their local inputs. This field has become increasingly urgent due to the exploding demand for computationally intensive deep learning inference. These computations are typically offloaded to cloud computing servers, leading to vulnerabilities that can compromise the security of the clients' data. To solve this problem, we introduce a linear algebra engine that leverages the quantum nature of light for information-theoretically secure multiparty computation using only conventional telecommunication components. We apply this linear algebra engine to deep learning and derive rigorous upper bounds on the information leakage of both the deep neural network weights and the client's data via the Holevo and the Cramer-Rao bounds, respectively. Applied to the MNIST classification task, we obtain test accuracies exceeding 96% while leaking less than 0.1 bits per weight symbol and 0.01 bits per data symbol. This weight leakage is an order of magnitude below the minimum bit precision required for accurate deep learning using state-of-the-art quantization techniques. Our work lays the foundation for practical quantum-secure computation and unlocks secure cloud deep learning as a field."
hugoblox:
  ids:
    doi: "10.1103/k8wg-qmbh"
links:
  - name: DOI
    url: https://doi.org/10.1103/k8wg-qmbh
  - name: arXiv
    url: https://arxiv.org/abs/2408.05629
  - name: MIT News
    url: https://news.mit.edu/2024/new-security-protocol-shields-data-during-cloud-based-computation-0926
  - name: Tech Briefs
    url: https://www.techbriefs.com/component/content/article/52065-new-security-protocol-protects-cloud-based-server-data
image:
  caption: 'Image credit: Sampson Wilcox'
featured: true
---
