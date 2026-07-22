---
name: "A Self-Correcting Neuro-Symbolic AI Reasoning Framework"
speakers:
  - Ben Wooding
  - Kiersten Brennan
  - Anne M. Tumlin
  - Hongchao Zhang
  - Taylor T. Johnson
categories:
  - Presentation
  - Paper
  - "Chair: Omri Isac"
---

### Abstract

Vision-Language Models (VLMs) struggle with explainability and tasks requiring step-by-step reasoning. This paper proposes a neuro-symbolic framework that leverages both logic and neural networks for interpretable results; chaining together convolutional neural networks (CNNs), computer vision techniques, and Satisfiability Modulo Theories (SMT). We introduce a challenging benchmark suite of KenKen and Sudoku puzzles, both NP-complete in the general case. Provided with an unsolved board image, these puzzles require image decomposition, constraint evaluation, and error detection/correction, making it a relevant benchmark suite for VLMs. We compare our neuro-symbolic framework against five state-of-the-art VLMs: Gemini-2.5-Pro, GPT-4o, GPT-4o-mini, Claude Sonnet 4.0, and Qwen2.5-VL-7B-Instruct. These VLMs have significant difficulty solving Sudoku or KenKen puzzles beyond 4x4 grids. The neuro-symbolic framework achieves 100% accuracy on computer-generated characters for all classes. For handwritten characters, we demonstrate the neuro-symbolic can correct image decomposition errors, improving solve rate. Overall, the benchmark is used to demonstrate the neuro-symbolic framework outperforms state-of-the-art VLMs while providing explainable reasoning to enable the self-correction of error. The benchmark suite consists of 2200 board images: seven classes of KenKen puzzle and four classes of Sudoku, for both computer-generated and handwritten characters.
