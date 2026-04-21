---
title: 'FedLOE: Federated Domain Generalization via Locally Overfit Ensemble'

authors:
  - me
  - David I. Inouye

date: '2026-03-25T00:00:00Z'

publication_types: ['article-journal']

publication: '*TMLR 2026*'

abstract: In federated learning (FL), clients typically access data from just one distribution. Ideally, the learned models would generalize to out-of-distribution (OOD) data, i.e., domain generalization (DG). However, centralized DG methods cannot easily be adapted to the domain separation context, and some existing federated DG methods can be brittle in the large-client, domain-separated regime. To address these challenges, we revisit the classic mixture-of-experts (MoE) idea by viewing each client as an expert on its own dataset. From this perspective, simple federated averaging can be seen as a type of iterative MoE, where the amount of local training determines the strength of each expert. In contrast to the standard FL communication-performance trade-off, we theoretically demonstrate in linear cases and empirically validate in deep models that reducing communication frequency can effectively enhance DG performance, surpassing centralized counterparts (e.g., on PACS). Building on this, we further propose an additional MoE strategy to combine the client-specific classifier heads using standard DG objectives. Our proposed FedLOE method can be viewed as an intermediate approach between FedAvg and one-time ensembling. It demonstrates both theoretical soundness and empirical effectiveness. Moreover, FedLOE requires fewer communication rounds, highlighting its practical efficiency and scalability.

summary: A mixture-of-experts approach to federated domain generalization.

tags:
  - Federated Learning
  - Domain Generalization

featured: true

links:
  - type: pdf
    url: https://openreview.net/forum?id=W4T9sK6Gai
---
