---
name: "Verification of LTL properties on Neural Networks for Chemical Process Monitoring"
speakers:
  - Julien Girard-Satabin
  - Simon Lutz
  - Daniel Neider
categories:
  - Presentation
  - Paper
  - Short presentation (7 min)
  - "Chair: TBA"
---

### Abstract

The specification and verification of temporal properties are crucial to assess the safety of monitoring systems. Such systems need to ensure that certain properties are validated during their full operation time. The rich pattern-finding capabilities of deep learning are a strong incentive to implement such monitors as neural networks. However, neural network verification historically focused on properties related to a single point in time. In this paper, we present a way to encode Linear Temporal Logic (LTL) properties in a neural network specification language. We derive from this encoding an automated translation to existing off-the-shelf provers. We apply our system to the verification of an industrial use case: a monitoring system for batch distillation. We were able to successfully specify and verify most of the properties in a small runtime.
