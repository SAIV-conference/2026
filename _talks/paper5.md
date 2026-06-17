---
name: "Verified Tensor Operators for Safety-Critical ML: From Specification to Reference Implementation"
speakers:
  - João Machado
  - Ricardo Silva
  - Loïc Correnson
  - João Galego
  - Eric Jenn
  - Hugo Daniel Macedo
  - Jean Souyris
  - Jorge Sousa Pinto
categories:
  - Presentation
  - Paper
  - "Chair: TBA"
---

### Abstract

Safety-critical deployment of machine learning models requires unambiguous specification and verified implementation of tensor operators. This paper presents a formally verified workflow based on the Why3 deductive verification platform. The workflow takes each operator from an abstract WhyML specification over mathematical tensors to extracted C code, via a concrete implementation on flat arrays linked by a machine-checked refinement proof. A reusable library supports the development, providing abstract tensor types, a row-major layout with proven bijectivity, and a refinement mapping to a C-level representation.  We illustrate the workflow on several ONNX operators, developed within the SONNX Working Group. Finally, we demonstrate how the abstract specifications compose to enable contract-based verification of functional properties of complete networks. The methodology is applicable beyond ONNX to any framework requiring verified tensor implementations.
