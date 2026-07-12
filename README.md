# Panagiota Grosdouli

<p align="center">
  <strong>Electrical and Computer Engineering · Reliable Autonomous Systems · Uncertainty-Aware AI</strong>
</p>

<p align="center">
  <img src="assets/profile/research_portfolio_map.svg" alt="Panagiota Grosdouli research portfolio map" width="100%" />
</p>

<p align="center">
  <a href="mailto:panagros1@ee.duth.gr"><img src="https://img.shields.io/badge/Email-panagros1%40ee.duth.gr-0ea5e9" alt="Email"></a>
  <a href="https://www.linkedin.com/in/panagiota-grosdouli-b468b0201/"><img src="https://img.shields.io/badge/LinkedIn-Panagiota%20Grosdouli-2563eb" alt="LinkedIn"></a>
  <a href="https://panagiota-research-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Research%20Projects-8b5cf6" alt="Research portfolio"></a>
  <a href="https://www.researchgate.net/profile/Panagiota-Grosdouli"><img src="https://img.shields.io/badge/ResearchGate-Profile-14b8a6" alt="ResearchGate"></a>
</p>

## Research direction

I study how autonomous systems can remain reliable when perception is noisy, localization degrades, environments change, and predictive models become uncertain.

My long-term objective is to develop robotic systems that can:

- represent and propagate uncertainty across the autonomy stack;
- evaluate the health of their own perception and state estimates;
- anticipate failure before it becomes safety critical;
- adapt planning and control according to risk and recoverability;
- explain why a protective or recovery action was selected;
- produce reproducible evidence rather than unsupported performance claims.

> **Central research question**  
> How can an autonomous system reason about what it does not know and convert that reasoning into safer real-time behaviour?

## Flagship research projects

<table>
<tr>
<td width="50%" valign="top">

### [SHIELD-VIO](https://github.com/panagiotagrosdouli/SHIELD-VIO)

Failure-aware visual–inertial autonomy with real feature tracking, IMU preintegration, an error-state EKF, calibrated risk estimation, domain-shift monitoring, navigation shielding, and recovery actions.

**Focus:** VIO · estimator introspection · failure prediction · runtime protection

</td>
<td width="50%" valign="top">

### [Adaptive Multi-Modal SLAM](https://github.com/panagiotagrosdouli/Adaptive-Multi-Modal-SLAM-with-Uncertainty-Aware-Sensor-Fusion)

Adaptive fusion of heterogeneous sensing modalities using reliability estimation, covariance adaptation, innovation consistency, and failure-aware weighting.

**Focus:** SLAM · sensor fusion · reliability · uncertainty propagation

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AURA](https://github.com/panagiotagrosdouli/AURA-Autonomous-Uncertainty-Reasoning-Architecture)

An architecture for transforming perceptual, state, environmental, and predictive uncertainty into risk-aware action selection and interpretable safety decisions.

**Focus:** uncertainty reasoning · risk-sensitive autonomy · explainability

</td>
<td width="50%" valign="top">

### [DynNav](https://github.com/panagiotagrosdouli/DynNav-Dynamic-Navigation-Rerouting-in-Unknown-Environments)

Dynamic navigation and rerouting in partially observed environments with uncertainty-aware planning, recoverability analysis, and runtime replanning.

**Focus:** planning · navigation · replanning · recoverability

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [SafeCrossAI](https://github.com/panagiotagrosdouli/SafeCrossAI)

Interpretable trajectory prediction and interaction-risk reasoning for pedestrians, cyclists, vehicles, and intelligent intersections.

**Focus:** VRU safety · trajectory prediction · TTC/CPA · interaction graphs

</td>
<td width="50%" valign="top">

### [OpenUWOC-AI](https://github.com/panagiotagrosdouli/OpenUWOC-AI)

AI-assisted research for underwater wireless optical communication, digital twins, adaptive link optimisation, and uncertainty-aware system analysis.

**Focus:** underwater communication · digital twins · adaptive optimisation

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Uncertainty-Aware Navigation](https://github.com/panagiotagrosdouli/uncertainty-aware-navigation)

Research components for navigation decisions that account for uncertain maps, state estimates, future motion, and downstream safety risk.

**Focus:** uncertainty-aware planning · safety supervision

</td>
<td width="50%" valign="top">

### [Formula 1 Race Simulation](https://github.com/panagiotagrosdouli/formula1-race-simulation)

A simulation-oriented project for modelling race dynamics, strategy, uncertainty, and performance evolution.

**Focus:** simulation · modelling · strategy analysis

</td>
</tr>
</table>

## Research stack

| Area | Methods and tools |
|---|---|
| **Robot perception** | OpenCV, visual tracking, semantic segmentation, trajectory prediction |
| **State estimation** | Kalman filtering, error-state EKF, IMU preintegration, VIO, SLAM |
| **Uncertainty** | covariance analysis, NIS/NEES, calibration, conformal prediction, domain shift |
| **Planning and safety** | risk-sensitive planning, dynamic replanning, runtime shielding, recovery policies |
| **Machine learning** | PyTorch, scikit-learn, interpretable baselines, uncertainty-aware models |
| **Simulation** | ROS 2, Gazebo, CARLA, SUMO, deterministic synthetic experiments |
| **Engineering** | Python, C/C++, Java, TypeScript, testing, CI, reproducible artifacts |

## Research principles

1. **Evidence before claims.** Synthetic, dataset, simulator, and hardware evidence must remain clearly separated.
2. **Uncertainty must be evaluated.** Confidence visualisation alone is not sufficient; calibration and estimator consistency matter.
3. **Failure is part of the system model.** Reliable autonomy requires detection, protection, and recovery—not only nominal accuracy.
4. **Reproducibility is a research result.** Seeds, configurations, commands, versions, and output artifacts should be recorded.
5. **Safety requires layered validation.** Research prototypes are not deployment-ready safety systems.

## Current research trajectory

```text
Perception reliability
        ↓
Uncertainty-aware state estimation
        ↓
Failure and domain-shift prediction
        ↓
Risk-sensitive planning
        ↓
Runtime shielding and recovery
        ↓
Simulation, public datasets, and hardware validation
```

## Academic goal

I aim to pursue doctoral research in robotics and autonomous systems, focusing on reliable perception, uncertainty-aware localization, risk-sensitive planning, and runtime safety for intelligent robotic systems.

## Contact

- **Email:** [panagros1@ee.duth.gr](mailto:panagros1@ee.duth.gr)
- **LinkedIn:** [Panagiota Grosdouli](https://www.linkedin.com/in/panagiota-grosdouli-b468b0201/)
- **Research portfolio:** [panagiota-research-portfolio.vercel.app](https://panagiota-research-portfolio.vercel.app/)
- **ResearchGate:** [Panagiota Grosdouli](https://www.researchgate.net/profile/Panagiota-Grosdouli)

---

<sub>Repositories contain projects at different maturity levels. Each project README should be treated as the source of truth for its implementation status and validation boundary.</sub>
