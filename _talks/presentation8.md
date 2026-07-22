---
name: "ProofBridge: Auto-Formalization of Natural Language Proofs in Lean via Joint Embeddings"
speakers:
  - Prithwish Jana
  - Kaan Kale
  - Ahmet Ege Tanriverdi
  - Cruise Song
  - Sriram Vishwanath
  - Vijay Ganesh
categories:
  - Presentation
  - Short presentation (7 min)
  - "Chair: Kaushik Mallik"
---

### Abstract

Translating human-written mathematical theorems and proofs from natural language (NL) into formal languages (FLs) like Lean 4 has long been a significant challenge for AI. Most state-of-the-art methods either focus on theorem-only NL-to-FL auto-formalization or on FL proof synthesis from FL theorems. In practice, auto-formalization of both theorem and proof still requires human intervention, as seen in AlphaProof's silver-medal performance at the 2024 IMO, where problem statements were manually translated before automated proof synthesis.

We present ProofBridge, a unified framework for automatically translating entire NL theorems and proofs into Lean 4. At its core is a joint embedding model that aligns NL and FL (NL-FL) theorem+proof pairs in a shared semantic space, enabling cross-modal retrieval of semantically relevant FL examples to guide translation. ProofBridge integrates retrieval-augmented fine-tuning with iterative proof repair, leveraging Lean's type checker and semantic equivalence feedback to ensure both syntactic correctness and semantic fidelity. Experiments show substantial improvements in proof auto-formalization over strong baselines (including GPT-5, Gemini-2.5, Kimina-Prover, DeepSeek-Prover), with our retrieval-augmented approach yielding significant gains in semantic correctness (SC, via proving bi-directional equivalence) and type correctness (TC, via type-checking theorem+proof) across pass@k metrics on miniF2F-Test-PF, a dataset we curated. In particular, ProofBridge improves cross-modal retrieval quality by up to 3.28x Recall@1 over all-MiniLM-L6-v2, and achieves +31.14% SC and +1.64% TC (pass@32) compared to the baseline Kimina-Prover-RL-1.7B.
