# Robotics and AI Research Portfolio

This document organizes my GitHub projects as a coherent research portfolio in robotics, autonomous systems, computer vision, and safety-aware artificial intelligence.

## Research Narrative

My long-term research goal is to develop autonomous systems that remain reliable when perception, localization, and planning become uncertain.

Real-world robots often fail because the full autonomy stack is brittle under uncertainty: sensors degrade, maps are incomplete, environments are dynamic, localization becomes unreliable, and planners may optimize short paths without explicitly reasoning about risk.

The projects in this portfolio investigate different parts of the same research question:

> How can robots perceive, estimate, plan, and recover under uncertainty in a way that is measurable, reproducible, and safety-aware?

## Main Research Theme

**Robust, uncertainty-aware autonomy for mobile robots and intelligent mobility systems.**

This theme connects:

1. perception under degradation,
2. visual-inertial odometry and SLAM robustness,
3. sensor reliability estimation,
4. risk-aware navigation and replanning,
5. vulnerable road user trajectory prediction,
6. safety monitoring and interpretable autonomy signals.

## Core Repositories

## 1. SHIELD-VIO

Repository: https://github.com/panagiotagrosdouli/SHIELD-VIO

**Research area:** Visual-inertial odometry, degradation monitoring, self-healing localization

**Central question:**
Can a VIO system detect when it is becoming unreliable, infer the likely cause, and select a recovery action before catastrophic localization failure?

**Role in the portfolio:**
This repository frames localization robustness as a closed-loop autonomy problem rather than a standalone estimation problem.

**Research value:**

- Connects perception, state estimation, diagnosis, and recovery.
- Introduces an interpretable Navigation Health Index.
- Defines a path toward ROS 2 and C++ integration.
- Can be extended toward UAV autonomy, field robotics, or safety-critical localization.

## 2. Adaptive Multi-Modal SLAM with Uncertainty-Aware Sensor Fusion

Repository: https://github.com/panagiotagrosdouli/Adaptive-Multi-Modal-SLAM-with-Uncertainty-Aware-Sensor-Fusion

**Research area:** SLAM, sensor fusion, uncertainty estimation, robust perception

**Central question:**
Can a SLAM system estimate sensor reliability online and adapt its fusion strategy under degraded visual conditions?

**Role in the portfolio:**
This repository shows a research path from classical SLAM/VIO baselines toward adaptive robotic perception.

**Research value:**

- Uses standard robotics datasets such as EuRoC and TUM-VI.
- Connects ORB-SLAM3-style baselines with adaptive fusion.
- Defines evaluation metrics such as ATE, RPE, failure rate, recovery time, and uncertainty calibration.
- Supports a publishable direction around robust SLAM under real-world degradation.

## 3. DynNav: Dynamic Navigation Rerouting in Unknown Environments

Repository: https://github.com/panagiotagrosdouli/DynNav-Dynamic-Navigation-Rerouting-in-Unknown-Environments

**Research area:** Risk-aware navigation, unknown environments, uncertainty-aware planning

**Central question:**
How can a mobile robot plan and replan safely when the map is incomplete, uncertain, or changing?

**Role in the portfolio:**
This repository connects planning, uncertainty, safety monitoring, and reproducible evaluation. It extends the portfolio beyond perception toward decision-making under uncertainty.

**Research value:**

- Focuses on belief-aware and risk-sensitive planning.
- Uses safety concepts such as returnability, risk measures, and monitoring.
- Can be connected to ROS 2 and simulation environments.
- Provides a bridge from estimation uncertainty to decision-making under uncertainty.

## 4. Uncertainty-Aware Navigation

Repository: https://github.com/panagiotagrosdouli/uncertainty-aware-navigation

**Research area:** Mobile robot navigation, uncertainty maps, controlled simulation experiments

**Central question:**
Can uncertainty-weighted planning reduce unsafe navigation behavior in unknown environments?

**Role in the portfolio:**
This is a focused research repository that can support a technical report, baseline study, or early-stage paper.

**Research value:**

- Clear and narrow scope.
- Baseline comparison against classical planners.
- Safety-relevant metrics such as collision rate, path length, risk cost, and replanning frequency.
- Foundation for reproducible experiments.

## 5. SafeCrossAI

Repository: https://github.com/panagiotagrosdouli/SafeCrossAI

**Research area:** Intelligent intersections, vulnerable road users, trajectory prediction, safety-aware mobility

**Central question:**
How can infrastructure-based AI predict vulnerable road user behavior and support safer connected/autonomous mobility?

**Role in the portfolio:**
This repository broadens the robotics portfolio into intelligent transportation systems and multi-agent safety.

**Research value:**

- Includes trajectory prediction and social interaction modeling.
- Connects perception, prediction, risk assessment, and simulation.
- Provides a bridge between robotics, autonomous vehicles, and safety-aware AI.

## Supporting Repositories

## OpenUWOC-AI

Repository: https://github.com/panagiotagrosdouli/OpenUWOC-AI

A research framework for AI-powered underwater wireless optical communications. While not a core robotics repository, it supports the broader theme of intelligent systems under uncertain physical conditions.

## Personal Portfolio

Repository: https://github.com/panagiotagrosdouli/personalportfolio

The public-facing academic portfolio that presents projects, CV, research interests, and contact information in a professional format.

## Research Positioning

The strongest concise positioning is:

> I am interested in robust autonomy for robots operating under uncertainty, especially reliability-aware perception, uncertainty-aware SLAM/VIO, and risk-sensitive navigation.

This direction is relevant to research groups working on:

- field robotics,
- autonomous navigation,
- SLAM and localization,
- UAV autonomy,
- safety-critical robotics,
- intelligent transportation systems,
- multi-agent trajectory prediction.

## Repository Quality Checklist

For each core robotics repository, the ideal structure is:

- clear README with research question,
- installation and quick-start commands,
- reproducible experiment script,
- dataset or simulation description,
- baseline comparison,
- evaluation metrics,
- `docs/` folder with methodology,
- `paper/` folder with abstract/contributions,
- `CITATION.cff`,
- license,
- roadmap with completed vs planned work clearly separated.

## Next Improvements

Priority order:

1. Keep SHIELD-VIO as the main localization and reliability-monitoring repository.
2. Link Adaptive Multi-Modal SLAM and SHIELD-VIO as related research directions.
3. Keep DynNav and Uncertainty-Aware Navigation as planning/navigation repositories.
4. Use SafeCrossAI as the intelligent mobility and multi-agent safety branch.
5. Make the personal portfolio website point clearly to these repositories.
6. Add real experiment outputs, figures, and benchmark tables where available.
7. Avoid overclaiming: clearly distinguish implemented code, prototype work, and planned research.

## Short Academic Summary

My GitHub portfolio demonstrates a coherent research direction in robotics and AI: making autonomous systems more reliable under uncertainty. The repositories cover perception degradation, visual-inertial localization, adaptive SLAM, risk-aware navigation, and vulnerable road user safety. Together, they form a foundation for research in robust autonomy, reliability-aware robotic perception, and safety-aware intelligent systems.