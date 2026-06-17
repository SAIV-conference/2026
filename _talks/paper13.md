---
name: "Incremental Invariant-based Safety Verification of Neural Controllers"
speakers:
  - Vladislav Nenchev
categories:
  - Presentation
  - Paper
  - "Chair: TBA"
---

### Abstract

Safety analysis of neural-network controllers for cyber-physical systems requires combining closed-loop dynamical reasoning with formal neural-network verification. Standard invariant-based workflows typically compute the maximal controlled-invariant set before controller checking, although a violating execution may be detectable for an invariant inner-approximation. This paper proposes an incremental workflow for checking controller safe-set preservation. Starting from an initial inner-approximation, the method interleaves invariant refinement with verification, reuses proof results, checks only the newly added region between successive iterates, and supports early termination with a counterexample. If no violation is found, the verified domain grows progressively with each refinement step. Case studies on adaptive-cruise and lane-keeping neural controllers show that interleaving reduces time to counterexample in unsafe cases, lowers runtime in safe cases, and proof reuse becomes more beneficial as verification cost increases.
