---
name: "MetaMoE: Formal Verification of Compositional Robustness and Scalability of Mixture-of-Experts Architecture"
speakers:
  - Quang Pham
  - Ben Wooding
  - Luke Nam
  - Samuel Sasaki
  - Taylor T. Johnson
categories:
  - Presentation
  - Paper
  - "Chair: TBA"
---

### Abstract

Mixture-of-experts (MoE) architectures offer modularity and scalability, yet their robustness, and the practicality of certifying that robustness, in heterogeneous settings are not well understood. This work presents MetaMoE, a heterogeneous MoE framework designed for compositional formal verification. In MetaMoE, a neural network, called a router, classifies an input image's domain and routes it to the corresponding domain expert neural network for fine-grained classification; we study how robustness propagates compositionally across these router and experts and establish when system-level verification can be derived from component-level verification. In homogeneous MoE, all experts share the same task, so a misroute may still preserve correctness if the receiving expert classifies the input correctly; in heterogeneous MoE, experts operate on disjoint class spaces, making any misroute catastrophic. We prove that when the router maintains expert selection under hard routing (k=1) within a perturbation limit, and the selected expert also maintains its classification within that perturbation limit, the end-to-end system robustness is compositional. This enables scalability as the computational power needed for verification and re-verification does not snowball as the system expands. We further complement the formal verification results with empirical experiments, which support the same robustness trends observed under certification. Experiments across 8 MoE configurations and 3 perturbation budgets show that robustly trained (RT) experts improve adversarial accuracy by up to 13.1% over non-robustly trained (NRT) ones and are a prerequisite for formal certifiability -- NRT models on complex domains are completely unverifiable -- while router training paradigm has negligible impact (<0.1%), and verified routers achieve 100% certified robustness accuracy (RoCRA) at practical perturbation bounds. These results outline a principled path toward scalable, verifiable modular AI.
