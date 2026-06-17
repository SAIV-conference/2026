---
name: "Temporal Guardrails for LLM Conversations: A Runtime Verification Framework"
speakers:
  - Itay Cohen
  - Moran Omer
  - Doron Peled
  - Klaus Havelund
categories:
  - Presentation
  - Paper
  - "Chair: TBA"
---

### Abstract

Large Language Models (LLMs) are increasingly integrated into organizational workflows, raising growing concerns about their potential abuse for fraud, security breaches, or intellectual property leakage. While LLMs embed protective mechanisms and organizations develop their own guardrails, many practical guardrail approaches remain stateless and lack formal temporal semantics, and existing formal methods are often domain-specific or rely on structured event representations. We propose a runtime verification (RV) framework that treats an LLM conversation as an execution trace that can be formally verified and develop a corresponding tool called Temporal Guard. It observes the stream of user messages and LLM-generated assistant responses, grounds each message into a set of atomic propositions, and thereby constructs a Boolean-labeled trace. Safety policies are specified as formulas in past-time linear temporal logic, and the monitor checks the evolving Boolean trace online to decide whether the conversation satisfies the policy. The central challenge is grounding: bridging the gap between the precise Boolean semantics of temporal logic and the ambiguity of natural language utterances. To address this, we developed a semantic grounding layer and experimentally evaluated a range of grounding strategies, including an embedding-based approach, Natural Language Inference (NLI), and LLM-based zero/few-shot classification. We demonstrate the effectiveness of Temporal Guard through grounding and end-to-end monitoring experiments.
