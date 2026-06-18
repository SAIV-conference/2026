---
name: "When Control Changes the Data: Safety under Interaction-Driven Distribution Shifts"
speakers:
  - Lars Lindemann
categories:
  - Invited Talk
  - Table Host
  - "Chair: TBA"
---

### Abstract

Accelerated by rapid advances in machine learning and AI, there has been tremendous success in the design of learning-enabled autonomous systems in areas such as autonomous driving and robotics. These exciting developments are accompanied by new fundamental challenges that arise regarding the safety and reliability of these increasingly complex systems due to imperfect learning, system unknowns, and uncertain environments. Statistical tools for uncertainty quantification have gained popularity due to their ability to deal with these challenges. However, their guarantees rely on i.i.d. data, an assumption that is violated when control actions change the underlying data distribution.

In this talk, I will provide new insight to design safe controllers under distribution shifts using robust conformal prediction (CP). I will begin by advocating for the use of CP due to its simplicity, generality, and efficiency as opposed to existing optimization-based verification techniques. I will then provide an introduction to CP and summarize existing work that uses CP to design probabilistically safe controllers in dynamic environments. Subsequently, we will look into interactive settings where the system’s behavior may change the environment's behavior, and vice versa. This circular dependency creates an interaction-driven distribution shift that invalidates existing CP guarantees. To deal with this problem, we propose an iterative framework that episodically updates the controller while robustly maintaining safety guarantees by quantifying the potential impact of a controller update on the environment's behavior. We realize this via adversarially robust CP where we perform a regular CP step in each episode using observed data under the current controller, but then transfer safety guarantees across controller updates by analytically adjusting the CP result to account for distribution shifts. Lastly, I will show how these ideas extend to handling policy-induced distribution shifts that arise when using barrier/Lyapunov functions to control uncertain systems.
