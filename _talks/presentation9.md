---
name: "Of Good Demons and Bad Angels: Guaranteeing Safe Control under Finite Precision"
speakers:
  - Samuel Teuber
  - Debasmita Lohar
  - Bernhard Beckert
categories:
  - Presentation
  - Short presentation (7 min)
  - "Chair: Kaushik Mallik"
---

### Abstract

As neural networks (NNs) become increasingly prevalent in safety-critical neural network-controlled cyber-physical systems (NNCSs), formally guaranteeing their safety becomes crucial.  For these systems, safety must be ensured throughout their entire operation, necessitating infinite-time horizon verification. To verify the infinite-time horizon safety of NNCSs, recent approaches leverage Differential Dynamic Logic (dL). However, these dL-based guarantees rely on idealized, real-valued NN semantics and fail to account for roundoff errors introduced by finite-precision implementations.

This paper bridges the gap between theoretical guarantees and real-world implementations by incorporating robustness under finite-precision perturbations — in sensing, actuation, and computation — into the safety verification. We model the problem as a hybrid game between a good Demon, responsible for control actions, and a bad Angel, introducing perturbations. This formulation enables formal proofs of robustness w.r.t. a given (bounded) perturbation. Leveraging this bound, we employ state-of-the-art mixed-precision fixed-point tuners to synthesize sound and efficient implementations, thus providing a complete end-to-end solution. We evaluate our approach on case studies from the automotive and aeronautics domains, producing efficient NN implementations with rigorous infinite-time horizon safety guarantees.
