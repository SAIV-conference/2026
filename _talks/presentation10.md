---
name: "Optimizing VNN Solver Configuration Selection using Large Language Models"
speakers:
  - Salil Kamath
  - Matthew Davis
  - Jonathan Andreason
  - Yatis Dodia
  - Vijay Ganesh
categories:
  - Presentation
  - "Chair: TBA"
---

### Abstract

The rise in popularity and deployment of deep neural networks has resulted in an increased demand for trustworthy models, particularly in safety-critical applications. As a result, several solvers that formally verify properties of neural networks have been developed. However, state of the art solvers have combinatorially large configuration spaces. The task of selecting the best configuration for an instance or benchmark is non-trivial. Furthermore, current methods for algorithm selection and algorithm configuration are insufficient for large configuration spaces.

We present REGENT, an automated selection tool for verification of neural network (VNN) solver configurations via Large Language Model (LLM) prompting. Our zero-shot selection method is a three stage LLM inference tool that takes as input a feature description of a VNN instance and outputs a solver configuration. In case of failure, feedback from the solver is passed back to the LLM, after which a new configuration is queried. Our reinforcement learning with optimization feedback (RLOF) method fine-tunes LLMs to output configurations that cause VNN solvers to improve on an optimization objective.

We perform extensive empirical evaluations that show that the configurations selected by REGENT achieve comparable performance to hand-tuned configurations on a large set of competition grade test instances. When applying our fine-tuning approach, we show that LLMs can configure solvers to prove tighter bounds than those proven using hand-tuned configurations on up to 58% of the most challenging test instances. REGENT allows non-expert users of VNN solvers to automatically generate significantly better configurations, and therefore can save several human hours involved in hyperparameter-tuning.
