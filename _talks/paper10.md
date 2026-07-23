---
name: "Certified Neural Approximations of Nonlinear Dynamics"
speakers:
  - Frederik Baymler Mathiesen
  - Nikolaus Vertovec
  - Francesco Fabiano
  - Luca Laurenti
  - Alessandro Abate
categories:
  - Presentation
  - Paper
  - "Chair: Kaushik Mallik"
---

### Abstract

Neural networks hold great potential to act as approximate models of nonlinear dynamical systems, with the resulting neural approximations enabling verification and control of such systems. However, in safety-critical contexts, the use of neural approximations requires formal bounds on their closeness to the underlying system. To address this fundamental challenge, we propose a novel, adaptive, and parallelizable verification method based on certified first-order models. Our approach provides formal error bounds on the neural approximations of dynamical systems, allowing them to be safely employed as surrogates by interpreting the error bound as bounded disturbances acting on the approximated dynamics. We demonstrate the effectiveness and scalability of our method on a range of established benchmarks from the literature, showing that it significantly outperforms the state of the art. Furthermore, we show that our framework can successfully address additional scenarios previously intractable for existing methods – neural network compression and an autoencoder-based deep learning architecture for training Koopman operators for the purpose of trajectory prediction.
