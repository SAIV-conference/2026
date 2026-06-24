---
name: "Vancomycert: A Certified Neuro-Symbolic Drug Delivery System"
speakers:
  - Alistair Sirman
  - Fleur Conway
  - Jessica Ciupa
  - Gusts Gustavs Grīnbergs
  - Ekaterina Komendantskaya
  - Alessandro Bruni
  - Michael John Williams
  - Vaishak Belle
  - Thai Son Hoang
  - Michael Rawson
categories:
  - Presentation
  - Paper
  - Short presentation (7 min)
  - "Chair: TBA"
---

### Abstract

Neural network controllers for autonomous decision-making are well-established in cyber-physical systems, yet their deployment in safety-critical healthcare settings remains largely unverified. This paper presents a methodology and case study for the formal verification of a neural network controller for antibiotic dosing, motivated by the challenge of systems that must be simultaneously adaptive and provably safe across unbounded time horizons. We construct a simplified yet clinically-interpretable model that tracks drug concentration, body temperature, and white blood cell count. Vancomycin is selected as a representative antibiotic, widely prescribed for severe infections yet carrying a narrow therapeutic window, where supratherapeutic concentrations risk nephrotoxicity and subtherapeutic dosing risks treatment failure. A supervised neural network controller is trained on synthetic clinician-style dosing data. We establish formal verification of input-output safety properties, specifically verifying a property of a neural network that implies an infinite-horizon proof that automated dosing never exceeds the supratherapeutic boundary. This system property is proven in Rocq using the Vehicle interactive theorem prover back-end to integrate the different proof systems. The end result is a verification pipeline that allows for a wide variety of treatment approaches whilst maint aining safety for each specific patient.
