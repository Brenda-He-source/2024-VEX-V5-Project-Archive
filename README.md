# VEX V5 Robotics Learning Journey 🤖

### Project Overview
This repository archives the C++ code I developed during the **Carnegie Mellon Robotics Academy VEX V5 Summer Intensive in 2024**. It documents my 5-day progression from basic coordinate systems to implementing AI-based computer vision logic.

The code in `main.cpp` aggregates the daily learning modules into a single, cohesive system.

### Learning Timeline

#### Day 1: Human-Machine Interface (UI)
* **Goal:** Master the VEX V5 Screen API and coordinate systems.
* **Implementation:**
    * Designed a custom startup screen featuring my team name **"Avengers"** and school **"GX No.1 High School"**.
    * Programmed a dynamic **face animation** with blinking eyes using `drawCircle` and loops.

#### Day 2: Sensor-Based Navigation
* **Goal:** Implement autonomous feedback loops.
* **Implementation:**
    * Utilized **Ultrasonic Rangefinders (Sonar)** to detect obstacles in real-time.
    * Wrote `while` loops to stop the drivetrain when objects are detected within **200mm**.

#### Day 3: Tele-operated Control Systems
* **Goal:** Map human inputs to mechanical outputs.
* **Implementation:**
    * Developed a **Split Arcade Control** scheme (Axis 3 for power, Axis 1 for turning).
    * Integrated a **Timer** function to display runtime on the controller screen.
    * Programmed logic for the **Robotic Arm and Claw** using bumper buttons (L1/L2, R1/R2).

#### Day 4: Environmental Sensing
* **Goal:** Process analog sensor data.
* **Implementation:**
    * Used a **Light Sensor** (`centerLT`) to distinguish between floor surfaces.
    * Implemented threshold-based logic for autonomous line tracking.

#### Day 5: Computer Vision (AI Foundation)
* **Goal:** Apply machine perception to control logic.
* **Implementation:**
    * Configured the VEX Vision Sensor to recognize **Blue Objects** (`BLUE_OBJECT` signature).
    * **Data Processing:** Extracted object centroids (X/Y coordinates) and dimensions in real-time.
    * **Control Algorithm:** Developed a closed-loop tracking system that automatically rotates the robot to keep the blue target centered in its field of view.

### Technical Stack
* **Language:** C++ (VEXcode Pro)
* **Hardware:** VEX V5 Brain, Smart Motors, Vision Sensor, Sonar, Light Sensor.
* **Key Concepts:** Computational Thinking, Finite State Machines, Sensor Fusion.

---
*Note: This repository is a consolidated portfolio of the original source files (`day1.h` through `day5.h`).*
