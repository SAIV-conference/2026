---
name: "Enhancing the Robustness of Counterfactual Explanations via Adversarial Training"
speakers:
  - Rithik Appachi Senthilkumar
  - Francesco Leofante
  - Vijay Ganesh
categories:
  - Presentation
  - Paper
  - "Chair: Christian Schilling"
---

### Abstract

Counterfactual explanations (CEs) provide a simple, yet powerful interpretive approach to understanding neural network behavior, envisioning hypothetical scenarios by systematically altering input features and analyzing the resulting changes in model predictions. However, CEs are useful only if they are robust, i.e., they remain consistent and meaningful even when adversarially perturbed. While prior work has explored the development of generators for robust CEs, checking the robustness of CEs produced for DNNs has not been explored within the verification context, nor has it been studied under adversarial training. We present a systematic study utilizing adversarial training to fortify the underlying neural network, observing its effect on the formal robustness of DNNs with respect to CEs using α, β-CROWN, a state-of-the-art NNV. Our experiments across multiple datasets, network architectures, and CE generators indicate that adversarial training has a positive impact on the number of formally verified robust CEs. We also measure the impact of adversarial training on other desirable properties of CEs, such as plausibility and proximity. While plausibility does not change, there is a trade-off with proximity when using a gradient-based CE generator.
