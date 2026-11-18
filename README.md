# Alex — Robot Learning & Embodied AI

I build and evaluate generative policies for robotic manipulation, with a focus on **Flow Matching**, **Diffusion Policies**, **World Action Models**, and vision-based continuous control.

My current work connects model research with deployment: multi-view RGB and robot-state observations are mapped to executable action chunks, trained under reproducible data contracts, and evaluated in Isaac-based manipulation environments.

[Portfolio](https://alex7537.github.io/) · [Research profile](#research-focus) · [Selected work](#selected-work) · [Kurzprofil auf Deutsch](#kurzprofil-auf-deutsch) · [中文简介](#中文简介)

## Research focus

- Generative policies for robotic manipulation
- Flow Matching, Diffusion Policy, and multimodal action generation
- World Action Models and video-assisted policy learning
- Vision-based continuous robot control
- Isaac Lab / Isaac Sim evaluation
- Stereo vision, depth estimation, and industrial 6D pose pipelines

## Selected work

### Generative Robot Policies for A2D Manipulation

**[flow-matching-test-a2d-v2](https://github.com/alex7537/flow-matching-test-a2d-v2)**

A unified research pipeline for comparing Conditional Flow Matching, Diffusion Policy, IMLE, video-assisted learning, Joint World Action Models, and an RDT-170M transfer route under a shared observation/action contract.

- Input: multi-view RGB observations and optional robot proprioception
- Output: 16-step continuous action chunks for arm and hand control
- Emphasis: reproducible splits, masked training, checkpoint provenance, and deployment bundles
- Status: several offline baselines are complete; closed-loop Isaac evaluation is tracked separately and is not overstated

### Isaac-Based Policy Deployment

**[fk-issac-logistics](https://github.com/alex7537/fk-issac-logistics)**

Inference and simulation integration for loading trained policy bundles and evaluating robot behavior in closed loop. The project separates successful model loading from demonstrated grasp performance and records deployment compatibility explicitly.

### Stereo Vision for Industrial Robotics

**[rgb-zed-mainline](https://github.com/alex7537/rgb-zed-mainline)**

A practical stereo-vision workflow covering dual-RGB calibration, ZED capture, RealSense helper tools, FoundationStereo integration, depth validation, and data preparation for industrial 6D pose estimation.

## Current direction

I am looking for a **Master's thesis opportunity** in robot learning, embodied AI, generative robot policies, or vision-based manipulation. I am particularly interested in projects that combine method development with simulation or real-robot evaluation.

## Kurzprofil auf Deutsch

Ich beschäftige mich mit generativen Methoden für die Robotersteuerung, insbesondere mit Flow Matching, Diffusion Policies, World Action Models und visueller Roboter-Manipulation. In meinen aktuellen Projekten entwickle und vergleiche ich Modelle, die aus mehreren Kamerabildern und dem Roboterzustand kontinuierliche Aktionssequenzen erzeugen, und integriere sie in Isaac-basierte Simulationsumgebungen.

Aktuell suche ich eine Masterarbeit im Bereich Robot Learning, Embodied AI, generative Roboter-Policies oder visuell gesteuerte Manipulation.

## 中文简介

我的研究与项目主要围绕生成式机器人策略、Flow Matching、Diffusion Policy、World Action Models、Isaac 仿真评估，以及工业场景中的双目视觉与 6D 位姿估计。中文技术细节保留在各项目的 `README.zh-CN.md` 中，默认项目入口使用英文，便于国际研究人员阅读。


