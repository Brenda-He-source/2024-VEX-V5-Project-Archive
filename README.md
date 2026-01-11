# VEX V5 Robotics Control System 🤖

### 1. Project Overview
This repository archives the C++ control logic I developed during the **Carnegie Mellon Robotics Academy (Summer 2024)**. The project focuses on **computational thinking**, **sensor fusion**, and **automated decision-making** using the VEX V5 hardware ecosystem.

Instead of simple linear execution, this project is structured into functional **Modules**, demonstrating a systematic approach to robotics programming.

### 2. System Architecture (Modules)
The code in `main.cpp` is organized into four distinct subsystems:

* **Module 1: HMI (Human-Machine Interface)**
    * Implements screen rendering and coordinate systems to visualize robot status.
* **Module 2: Navigation & Obstacle Avoidance**
    * Utilizes **Distance Sensors** to detect environmental barriers.
    * Implements feedback loops to execute avoidance maneuvers autonomously.
* **Module 3: Manipulation (Arm & Claw)**
    * Precise motor sequencing for grasping and lifting objects.
* **Module 4: Computer Vision (AI Perception)**
    * **Key Highlight:** Integrates the VEX Vision Sensor to track colored objects (e.g., Yellow Cones).
    * Simulates basic **AI perception logic**: Detecting visual inputs $\rightarrow$ Calculating centroids $\rightarrow$ Adjusting motor output to follow the target.

### 3. Technical Skills
* **Language:** C++ / VEXcode Pro
* **Concepts:** Finite State Machines (FSM), PID Control Logic, Computer Vision Basics.
---
*Note: This repository contains the core application logic (`main.cpp`) for portfolio demonstration purposes. Standard VEX V5 header files and configuration libraries are omitted for clarity.*
