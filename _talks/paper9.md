---
name: "Hybrid Robustness Verification for Spatio-Temporal Neural Networks"
speakers:
  - Sherwin Varghese
  - Matthew Wicker
  - Alessio Lomuscio
categories:
  - Presentation
  - Paper
  - "Chair: Omri Isac"
---

### Abstract

With AI increasingly deployed in safety-critical systems, providing formal robustness guarantees for the underlying models is essential. Existing verification methods either rely on overly conservative approximations or incur prohibitive computational costs. For example, the use of $\ell_p$-norm perturbations in video settings encodes the belief that the adversary can inject noise in every video frame. In practice, adversarial perturbations exhibit structured spatial and temporal correlations, constrained to lower-dimensional, semantically meaningful subspaces. In this work, we study robustness verification of \emph{3D convolutional neural networks} (3D CNNs) processing video and volumetric inputs, targeting applications in action recognition (UCF-101), autonomous driving (Udacity), and medical imaging (MedMNIST) exploiting realistic assumptions on adversarial strength by modelling them as spatio-temporal constraints --- where the attacker can modify either a subset of frames or patches within a set of consecutive frames. We demonstrate that modelling realistic constraints enables tighter approximations, particularly in CNNs. We introduce \emph{Spatio-Temporal Bound Propagation} (STBP), a verification framework that computes an exact closed-form characterization of the first convolutional layer and propagates certified bounds through subsequent layers using scalable approximations. Computing the exact closed-form provides the tightest bounds for the first convolutional layer. Thus, we utilise approximation methods in the remainder of the network. To spur further progress in this field, we propose \texttt{ST-Bench}, a verification benchmark for autonomous driving and activity recognition, to systematically evaluate verifiable robustness. Compared to existing verification and training-based approaches, STBP provides stronger robustness guarantees with significantly improved scalability, achieving up to $1.7\times$ higher certified robust accuracy under identical perturbation budgets.
