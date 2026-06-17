---
name: "Faster Optimization of Decision Tree Policies for Markov Decision Processes"
speakers:
  - Daniël Vos
  - Anna Lukina
categories:
  - Presentation
  - Paper
  - "Chair: TBA"
---

### Abstract

Markov Decision Processes (MDPs) are a powerful modeling paradigm for sequential decision-making problems, e.g., robot navigation and game playing. Decades of research have produced highly efficient algorithms for solving MDPs. A common limitation, however, is that the solutions (policies) are typically represented as large lookup tables that map agents' actions to thousands or even millions of states. In this work, we present a fast approach to optimizing (fixed-size) decision tree policies for MDPs, which are easier for human experts to analyze and for specialized tools to verify. Previous work tackled this problem using computationally intensive techniques, such as integer programming or abstraction refinement. While our method, Lipa, which combines branch-and-bound with smart heuristics, can often find high-quality policies orders of magnitude faster and prove optimality where previous methods fail. We evaluate Lipa on 21 discounted-return and model-checking benchmark MDPs of varying sizes and demonstrate consistent, significant improvement over the state of the art.
