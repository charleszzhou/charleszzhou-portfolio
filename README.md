# Weiran (Charles) Zhou — Mechanical Engineering Portfolio

This repository hosts my personal engineering portfolio, showcasing selected projects in **Dynamical Systems & Controls**, **Robotics**, **MEMS**, and **Experimental Mechanical Design**.

🔗 **Live site:**  
https://charleszzhou.github.io/charleszzhou-portfolio/

---

## Overview

I am a Mechanical Engineering student at **UC Santa Barbara (Class of 2026)**, specializing in **Dynamical Systems & Controls** and **MEMS**.  
My work focuses on designing, modeling, and validating real-world systems that operate under uncertainty, nonlinear dynamics, and practical constraints.

This portfolio emphasizes:
- Closed-loop control and embedded systems  
- Experimental validation and instrumentation  
- Mechanism and actuator design  
- Multiphysics modeling (COMSOL)  
- System-level integration and reliability  

---

## Featured Projects

### 🔹 Autonomous Submersible with Buoyancy Control  
Closed-loop buoyancy control using pressure feedback for autonomous descent, bottom detection, and resurfacing.  
Validated to **17 ft depth** and awarded *Most Technical Project*.

**Topics:** Embedded control · PID · Fluid dynamics · Waterproof design

---

### 🔹 Multi-Motor CAN Control Interface  
Python GUI for real-time MIT-mode control of CubeMars BLDC actuators over CAN with live telemetry, gain tuning, and safety logic.

**Topics:** CAN communication · Motor control · GUI design · Safety-critical software

---

### 🔹 Electrokinetic Injection Modeling in Microfluidics  
COMSOL multiphysics simulation of electrokinetic injection (pinch & dispense), capturing EOF, electrophoresis, and species transport.

**Topics:** Microfluidics · COMSOL · Nernst–Planck · Data extraction

---

## Additional Projects

- **MEMS Resonator for Picogram-Scale Mass Sensing**  
  COMSOL-backed modeling of a comb-drive MEMS resonator, establishing feasibility limits for picogram-scale detection.

- **Sampling Frequency Effects in DC Motor Control**  
  Experimental study quantifying how discrete-time sampling frequency affects tracking error, overshoot, and stability.

- **Pawl Clutch for an Untethered Jumping Robot**  
  Compact pawl clutch with Nitinol actuation for reliable spring energy release.

- **Torsional Stiffness Measurement for Soft Robotics**  
  Low-cost experimental rig achieving ~0.1 Nm/deg resolution as an alternative to commercial torque sensors.

---

## Repository Structure

```text
/
├── index.html                # Homepage
├── projects/                 # Individual project pages
│   ├── autoSubmersible.html
│   ├── multiMotorControl.html
│   ├── ekiComsol.html
│   ├── mems_resonator.html
│   ├── motor_sampling.html
│   ├── pawlClutch.html
│   └── torsionalRig.html
├── assets/
│   ├── css/                  # Global stylesheet
│   ├── img/                  # Images and thumbnails
│   └── pdf/                  # Project reports and slides
└── README.md
