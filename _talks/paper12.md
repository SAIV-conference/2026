---
name: "Principled Rewriting of ONNX Operators for Reluctant Solvers"
speakers:
  - Alban Grastien
  - Guilhem Ardouin
  - Julien Girard-Satabin
categories:
  - Presentation
  - Paper
  - "Chair: Christian Schilling"
---

### Abstract

Neural networks (NN) are often represented using the Open Neural Network Exchange (ONNX) format that provides a rich set of operators.  This richness implies that many tools support only a subset of ONNX operators and, consequently, a subset of NNs.  However, some of these operators can be expressed equivalently as combinations of simpler, already supported, operators.  In this work, we present an extension of CAISAR---a platform for verification of NN that uses external solvers---that automatically transforms these redundant operators into simpler ones before calling existing solvers, thus extending the range of these solvers.  This work focuses on the argmax operator, proposing a transformation, proving its correctness, and presenting experimental results.
