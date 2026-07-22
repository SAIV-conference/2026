---
name: "Automated Algorithm Configuration of α,β-CROWN"
speakers:
  - Konstantin Kaulen
  - Holger H. Hoos
categories:
  - Presentation
  - Paper
  - "Chair: Omri Isac"
---

### Abstract

While neural networks have achieved remarkable success across a wide range of application domains, their predictions remain brittle when confronted with adversarial perturbations. To enable their responsible deployment in safety-critical settings, neural network verification techniques have been developed to formally establish input–output properties of interest. However, even state-of-the-art verification systems such as α,β-CROWN, the winner of the Verification of Neural Networks Competition (VNN-COMP) since 2021, may fail to prove challenging properties within reasonable time budgets. Fully exploiting the capabilities of such systems typically demands careful tuning of numerous parameters, a process that often relies on substantial domain expertise and extensive manual experimentation. In this work, for the first time, we apply automated algorithm configuration to α,β-CROWN using SMAC3, thereby eliminating the need for labour-intensive manual tuning. We show that, given a carefully designed parameter search space, automatically discovered configurations can achieve performance comparable to expert-crafted configurations, even when using relatively modest computational budgets for the optimisation process. We evaluate our approach on the benchmarks from the regular track of VNN-COMP 2025 and demonstrate that the automatically configured version of α,β-CROWN achieves a higher overall score than the author-provided configuration when applying the scoring scheme of the competition.
