---
name: Neural Stochastic Control and Verification for Safe Autonomy
speakers:
  - Đorđe Žikelić
categories:
  - Invited Talk
  - Table Host
  - "Chair: Guy Avni"
---

### Abstract

Learning-based methods, such as reinforcement learning, are receiving increasing attention for solving challenging control tasks. However, the lack of safety assurances about learned controllers poses a significant barrier to their practical deployment. In this talk, we will present a framework for learning and formally verifying neural controllers for tasks specified via temporal logic specifications. The framework is applicable to stochastic dynamical systems, thus also taking into account environment uncertainty. Given a specification and a probability bound, the framework jointly learns and formally verifies a controller together with a formal certificate of the specification being satisfied with at least the desired probability, both parametrized as neural networks. Certificates are supermartingale-like objects that can be effectively used to formally reason about stochastic systems in a fully automated fashion. The talk will touch upon several aspects of the neural control problem, including learning of neural controllers from temporal logic specifications, formal verification via neural certificates, and safety assurances upon runtime deployment.

### <a href="../../assets/slides/neural_stochastic_control_and_verification.pdf">Download the slides</a>
