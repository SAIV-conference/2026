---
name: "Value Functions as Supermartingale Certificates"
speakers:
  - Alessandro Abate
  - Daniel Contro
  - Mirco Giacobbe
  - Agustín Martínez-Suñé
  - Diptarko Roy
categories:
  - Presentation
  - Paper
  - "Chair: Christian Schilling"
---

### Abstract

Certification methods for stochastic systems provide sufficient proof rules, based on real-valued supermartingale certificates, to determine the almost-sure satisfaction of ω-regular properties (and therefore of linear temporal logic) over general state spaces, encompassing both countably infinite and continuous state spaces. Conversely, reinforcement learning (RL) methods for ω-regular tasks have received considerable attention, but they typically lack formal guarantees that the learned policy satisfies the specification, except possibly for finite state and action spaces. We bridge these two lines of research by establishing a novel theoretical connection: under an appropriate reward, the value function associated to a policy that almost surely satisfies an ω-regular property encodes a Streett supermartingale certificate for that specification. Our results, validated experimentally on finite Markov decision processes, hold for finite, countably infinite, and continuous state spaces, suggesting a principled route to certificate synthesis via RL.
