---
name: "veriFIRE: An Industrial Case Study in Verifying Consistency Properties for DNN-Based Wildfire Detection System"
speakers:
  - Idan Refaeli
  - Maya Swisa
  - Itay Buchnik
  - Alon Zada
  - Guy Amir
  - Elad Mandelbaum
  - Ziv Freund
  - Guy Katz
categories:
  - Presentation
  - Paper
  - Short presentation (7 min)
  - "Chair: Kaushik Mallik"
---

### Abstract

We present our ongoing work on the veriFIRE project: a collaboration between industry and academia, aimed at applying verification to increase the reliability of a real-world, safety-critical system. Specifically, we target an airborne platform for wildfire detection, which incorporates two deep neural networks. We present an end-to-end methodology for verifying consistency properties in this system. Our approach encodes application-grounded requirements into solver-compatible queries for existing neural network verifiers. We study properties of interest over critical operational scenarios: (i) monotonicity of detector confidence as target intensity increases; and (ii) bounded detector response under physically plausible blur over the sensor. We instantiate these encodings using state-of-the-art neural network verification backends and evaluate them at scale on real background samples. For the first property, all verification queries are solved in under five minutes. For the second property, verification is substantially harder, highlighting key scalability challenges for richer, higher-dimensional specifications. Overall, the results demonstrate that meaningful, domain-specific guarantees can be obtained for industrial systems.
