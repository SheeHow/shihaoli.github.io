---
title: "Learning-Based Control for Complex Systems"
excerpt: "Developing safe reinforcement learning and data-driven control frameworks with robustness guarantees<br/><img src='/images/control-system-thumbnail.png'>"
collection: portfolio
---

## Overview

This project focuses on developing advanced learning-based control methodologies that guarantee safety and robustness under uncertainty. The work combines theoretical advances with practical implementations for industrial applications.

<img src='/images/control-system-overview.png' alt='Control System Overview' style='width:100%;'>

## Key Contributions

### Safe Reinforcement Learning

<img src='/images/safe-rl-framework.png' alt='Safe RL Framework' style='width:80%; display:block; margin:auto;'>

- Developed reinforcement learning algorithms with quadratic-program safety filters
- Implemented safety shielding mechanisms to prevent constraint violations
- Created curriculum-based learning strategies with physics-informed rewards

### Distributionally Robust Control

<div style='display:flex; justify-content:space-between; margin:20px 0;'>
  <img src='/images/mdr-deepc-architecture.png' alt='MDR-DeePC Architecture' style='width:48%;'>
  <img src='/images/robust-control-results.png' alt='Robust Control Results' style='width:48%;'>
</div>

- Designed MDR-DeePC (Model-Inspired Distributionally Robust Data-Enabled Predictive Control)
- Combined physics-based and data-driven predictions for improved robustness
- Developed trajectory valuation and influence-function methods for data attribution

### Implementation

<img src='/images/control-implementation.png' alt='Implementation Framework' style='width:100%;'>

- **Languages**: Python (NumPy, PyTorch), MATLAB/Simulink
- **Methods**: Model Predictive Control, DeePC, System Identification
- **Applications**: Energy systems, manufacturing processes

## Experimental Results

<div style='display:flex; justify-content:space-between; margin:20px 0;'>
  <img src='/images/control-experiment-setup.jpg' alt='Experimental Setup' style='width:32%;'>
  <img src='/images/control-results-graph.png' alt='Performance Results' style='width:32%;'>
  <img src='/images/control-comparison.png' alt='Method Comparison' style='width:32%;'>
</div>

## Related Publications

1. Li, S., Li, J., Martin, C., Bakshi, S., & Chen, D. (2025). "MDR-DeePC: Model-Inspired Distributionally Robust Data-Enabled Predictive Control." *MECC 2025*.

2. Li, J., Li, S., Xu, J., Bakshi, S., & Chen, D. (2025). "Influence Functions for Data Attribution in Linear System Identification and LQR Control." *arXiv:2506.11293*.

3. Li, J., Li, S., & Chen, D. (2025). "Smart Predict-Then-Control: Integrating identification and control via decision regret." *arXiv:2506.11279*.

## Impact

This research provides practical solutions for implementing safe and robust control in real-world systems where traditional model-based approaches may fail due to uncertainties and complex dynamics.

<img src='/images/control-impact-diagram.png' alt='Research Impact' style='width:100%;'>
