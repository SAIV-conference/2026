---
name: "Precise Verification of Transformers through ReLU-Catalyzed Abstraction Refinement"
speakers:
  - Hengjie Liu
  - Zhenya Zhang
  - Jianjun Zhao
categories:
  - Presentation
  - Short presentation (7 min)
  - "Chair: Ekaterina Komendantskaya"
---

### Abstract

Formal verification of transformers has become increasingly important due to their widespread deployment in safety-critical applications. Compared to classic neural networks, the inferences of transformers involve highly complex computations, such as dot products in self-attention layers, rendering their verification extremely difficult. Existing approaches explored over-approximation methods by constructing convex constraints to bound the output ranges of transformers, which can achieve high efficiency. However, they may sacrifice verification precision, and consequently introduce significant approximation error that leads to frequent occurrences of false alarms.  In this paper, we propose a transformer verification approach that can achieve improved precision. At the core of our approach is a novel usage of ReLU, by which we represent a precise but non-linear bound for dot products such that we can further exploit the rich body of literature for convex relaxation of ReLU to derive precise bounds. We extend two classic approaches to the context of transformers, a rule-based one and an optimization-based one, resulting in two new frameworks for efficient and precise verification. We evaluate our approaches on different model architectures and robustness properties derived from two datasets about sentiment analysis, and compare with the state-of-the-art baseline approach. Compared to the baseline, our approach can achieve significant precision improvement for most of the verification tasks with acceptable compromise of efficiency, which demonstrates the effectiveness of our approach.
