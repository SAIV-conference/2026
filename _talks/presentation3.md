---
name: "PICID: Proof-Driven Clause Learning in Neural Network Verification"
speakers:
  - Omri Isac
  - Idan Refaeli
  - Haoze Wu
  - Clark Barrett
  - Guy Katz
categories:
  - Presentation
  - Short presentation (7 min)
  - "Chair: TBA"
---

### Abstract

Current Deep Neural Network (DNN) verifiers are typically designed to prioritize scalability over reliability. Reliability can be reinforced through the generation of proofs that are checkable by trusted, external proof checkers. To date, only a handful of verifiers support proof production; and these rely on verifier-specific formats, and balance between scalability, proof detail, and the trustworthiness of their proof checker. In this tool paper, we introduce PICID, a DNN verifier that produces proofs in the standard Alethe format for SMT solving, checkable by multiple existing checkers. PICID implements a parallel CDCL(T) architecture that integrates a state-of-the-art, proof-producing SAT solver with the Marabou DNN verifier. Furthermore, PICID leverages UNSAT proofs to derive conflict clauses. Our evaluation shows that PICID generates valid proofs in the vast majority of cases and significantly outperforms existing tools that produce comparable proofs.
