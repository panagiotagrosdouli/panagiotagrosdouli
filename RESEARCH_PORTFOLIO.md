# Robotics and AI Research Portfolio

This document organizes my GitHub projects as a coherent research portfolio for graduate research and PhD applications in robotics, autonomous systems, computer vision, and safety-aware artificial intelligence.

## Research Narrative

My long-term research goal is to develop autonomous systems that remain reliable when perception, localization, and planning become uncertain.

Many real-world robots fail not because a single algorithm is missing, but because the full autonomy stack is brittle under uncertainty: sensors degrade, maps are incomplete, environments are dynamic, localization becomes unreliable, and planners may optimize short paths without understanding risk.

The projects in this portfolio investigate different parts of the same research question:

> How can robots perceive, estimate, plan, and recover under uncertainty in a way that is measurable, reproducible, and safety-aware?

## Main PhD-Relevant Theme

**Robust, uncertainty-aware autonomy for mobile robots and intelligent mobility systems.**

This theme connects:

1. Perception under degradation
2. Visual-inertial odometry and SLAM robustness
3. Sensor reliability estimation
4. Risk-aware navigation and replanning
5. Vulnerable road user trajectory prediction
6. Safety monitoring and interpretable autonomy signals

## Core Repositories

## 1. SHIELD-VIO

Repository: https://github.com/panagiotagrosdouli/SHIELD-VIO

**Research area:** Visual-inertial odometry, degradation monitoring, self-healing localization

**Central question:**
Can a VIO system detect when it is becoming unreliable, diagnose the likely cause, and select a recovery action before catastrophic localization failure?

**Why it matters for PhD applications:**
This is the strongest single repository for a robotics PhD direction because it frames localization robustness as a closed-loop autonomy problem rather than a simple estimation problem.

**Research value:**

- Connects perception, state estimation, diagnosis, and recovery
- Introduces an interpretable Navigation Health Index
- Supports future ROS 2 and C++ integration
- Can evolve toward UAV autonomy, field robotics, or safety-critical localization

## 2. Adaptive Multi-Modal SLAM with Uncertainty-Aware Sensor Fusion

Repository: https://github.com/panagiotagrosdouli/Adaptive-Multi-Modal-SLAM-with-Uncertainty-Aware-Sensor-Fusion

**Research area:** SLAM, sensor fusion, uncertainty estimation, robust perception

**Central question:**
Can a SLAM system estimate sensor reliability online and adapt its fusion strategy under degraded visual conditions?

**Why it matters for PhD applications:**
This repository shows a research path from classical SLAM/VIO baselines toward adaptive and self-healing robotic perception.

**Research value:**

- Uses standard robotics datasets such as EuRoC and TUM-VI
- Connects ORB-SLAM3-style baselines with adaptive fusion
- Defines evaluation metrics such as ATE, RPE, failure rate, recovery time, and uncertainty calibration
- Supports a publishable research direction around robust SLAM under real-world degradation

## 3. DynNav: Dynamic Navigation Rerouting in Unknown Environments

Repository: https://github.com/panagiotagrosdouli/DynNav-Dynamic-Navigation-Rerouting-in-Unknown-Environments

**Research area:** Risk-aware navigation, unknown environments, uncertainty-aware planning

**Central question:**
How can a mobile robot plan and replan safely when the map is incomplete, uncertain, or changing?

**Why it matters for PhD applications:**
This repository connects planning, uncertainty, formal safety, and reproducible evaluation. It supports a strong autonomy research narrative beyond perception alone.

**Research value:**

- Focuses on belief-aware and risk-sensitive planning
- Uses safety concepts such as returnability, CVaR-style risk, and monitoring
- Can be connected to ROS 2 and simulation environments
- Provides a bridge from estimation uncertainty to decision-making under uncertainty

## 4. Uncertainty-Aware Navigation

Repository: https://github.com/panagiotagrosdouli/uncertainty-aware-navigation

**Research area:** Mobile robot navigation, uncertainty maps, controlled simulation experiments

**Central question:**
Can uncertainty-weighted planning reduce unsafe navigation behavior in unknown environments?

**Why it matters for PhD applications:**
This is a focused, clean research repository that can support a thesis chapter, technical report, or baseline paper.

**Research value:**

- Clear and narrow scope
- Baseline comparison against classical planners
- Safety-relevant metrics such as collision rate, path length, risk cost, and replanning frequency
- Good foundation for reproducible experiments

## 5. SafeCrossAI

Repository: https://github.com/panagiotagrosdouli/SafeCrossAI

**Research area:** Intelligent intersections, vulnerable road users, trajectory prediction, safety-aware mobility

**Central question:**
How can infrastructure-based AI predict vulnerable road user behavior and support safer connected/autonomous mobility?

**Why it matters for PhD applications:**
This repository broadens the robotics portfolio into intelligent transportation systems and multi-agent safety, which is highly relevant for autonomous driving and smart-city research groups.

**Research value:**

- Includes trajectory prediction and social interaction modeling
- Connects perception, prediction, risk assessment, and simulation
- Provides a bridge between robotics, autonomous vehicles, and safety-aware AI

## Supporting Repositories

## OpenUWOC-AI

Repository: https://github.com/panagiotagrosdouli/OpenUWOC-AI

A research framework for AI-powered underwater wireless optical communications. While not a robotics core repository, it supports the broader theme of intelligent systems under uncertain physical conditions.

## Personal Portfolio

Repository: https://github.com/panagiotagrosdouli/personalportfolio

The public-facing academic portfolio that can present the projects, CV, research interests, and contact information in a professional format.

## Recommended PhD Positioning

The strongest positioning is:

> I am interested in robust autonomy for robots operating under uncertainty, especially self-healing perception, uncertainty-aware SLAM/VIO, and risk-sensitive navigation.

This can be adapted for robotics labs working on:

- field robotics,
- autonomous navigation,
- SLAM and localization,
- UAV autonomy,
- safety-critical robotics,
- intelligent transportation systems,
- multi-agent trajectory prediction.

## Repository Quality Checklist

For each core robotics repository, the ideal structure is:

- Clear README with research question
- Installation and quick-start commands
- Reproducible experiment script
- Dataset or simulation description
- Baseline comparison
- Evaluation metrics
- `docs/` folder with methodology
- `paper/` folder with abstract/contributions
- `CITATION.cff`
- License
- Roadmap with completed vs planned work clearly separated

## Next Improvements

Priority order:

1. Keep SHIELD-VIO as the main PhD-level flagship repository.
2. Link Adaptive Multi-Modal SLAM and SHIELD-VIO as related research directions.
3. Keep DynNav and Uncertainty-Aware Navigation as planning/navigation repositories.
4. Use SafeCrossAI as the intelligent mobility and multi-agent safety branch.
5. Make the personal portfolio website point clearly to these repositories.
6. Add real experiment outputs, figures, and benchmark tables where available.
7. Avoid overclaiming: clearly distinguish implemented code, prototype work, and planned research.

## Short Academic Summary

My GitHub portfolio demonstrates a coherent research direction in robotics and AI: making autonomous systems more reliable under uncertainty. The repositories cover perception degradation, visual-inertial localization, adaptive SLAM, risk-aware navigation, and vulnerable road user safety. Together, they form a strong foundation for graduate research in robust autonomy, self-healing robotic perception, and safety-aware intelligent systems.