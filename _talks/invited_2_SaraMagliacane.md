---
name: A high-level view on causal representation learning with actions
speakers:
  - Sara Magliacane
categories:
  - Invited Talk
  - Table Host
  - "Chair: TBA"
---

### Abstract

Causal representation learning (CRL) is a new and exciting research direction in causality and representation learning that aims at learning meaningful high-level causal variables from low-level representations (e.g. images or videos) in an unsupervised way, while providing theoretical guarantees on their identifiability/correctness or the disentanglement of their representations. For example, given a video of agent performing actions in a simulated environment, temporal CRL methods are able to learn in a low-dimensional latent space a representation of the causal variables, e.g., the individual objects and their attributes,  up to permutations and element-wise transformations with respect to the ground truth ones. This enables us to have a disentangled or "steerable" latent space, which allows us to imagine the effect of new combinations of actions and thus create new counterfactual trajectories. By reverse engineering the underlying causal system directly from visual inputs and actions, we can then provide a potential first step towards AI systems that reason about the world causally without supervision. In this talk I will give a high-level overview of a few recent CRL methods in this exciting setting, and I will try to discuss a few high-level ideas of why I think this is also interesting for the (AI) verification crowd, e.g., by providing a principled and theoretically grounded way to extract meaningful concepts from unstructured data that could be then used for safety specifications.
