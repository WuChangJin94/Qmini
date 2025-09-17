# Unitree Qmini

<p align="center"><img src="images/Qmini.jpeg" width="100%"/></p>

**Unitree Qmini** is a fully open-sourced, low-cost bipedal robot that can be entirely 3D printed by individual users. Designed for hobbyists, educators, and researchers alike, Qmini enables users to rapidly get started and assemble their own robot in a modular, LEGO-like fashion. It provides an accessible and affordable entry point into robotics, accelerating innovation and contributing to the global development of the robotics ecosystem.

### 🚀 Fully Open Source

**Hardware:**

- Complete Bill of Materials (BOM)
- Electrical system block diagram
- [DIY instructions](Qmini_DIY.pdf)

**Mechanical Structure:**

- [STEP files](STEP_file) for all mechanical components
- Assembly SOP (Standard Operating Procedure)

**Software:**

- [URDF model](urdf/Qmini.urdf)
- Core software stack: [RoboTamer4Qmini](https://github.com/vsislab/RoboTamer4Qmini.git)

<p align="center"><img src="images/Qmini_simulation.gif" width="100%"/></p>

### 🧰 One-Stop Parts Sourcing

Thanks to the comprehensive open-source resources, developers can easily acquire all required components. The entire mechanical structure is 3D-printable, requiring virtually no custom machining. Once printed, the parts can be assembled in just **3–5 hours** using Unitree's high-reliability **8010 motors** and a standard battery pack.

<p align="center"><img src="images/Qmini_modules.png" width="100%"/></p>

### ⚙️ Balanced Performance and Expandability

Qmini integrates **11 Unitree 8010 motors**, a proven actuator used in various commercial robotics platforms:

- **10 motors** drive the robot's primary locomotion system
- **1 motor**, located at the neck, is reserved for custom expansions

This modularity encourages developers to design and prototype their own extensions—enhancing functionality, aesthetics, or interactivity.

### 🤖 Developer-Friendly Design

Staying true to the idea that great tools should be easy to use, Qmini is built with simplicity and cost-effectiveness in mind. The platform supports a range of affordable control boards, with the **Raspberry Pi 4 Model B** provided as the default reference. Developers are also free to choose alternative controllers based on their specific needs or projects.

### 🌍 Versatile Applications

Qmini is ideal for a wide range of use cases:

- **Individual hobbyists** – 3D print, assemble, and program your own robot at home
- **STEM education** – Perfect for robotics competitions, lab experiments, and graduation projects
- **Research institutions** – A compact platform for testing dynamic gait, locomotion control, and AI algorithms
- **Interactive entertainment** – Ready to perform in animation, stage shows, or other creative tech experiences
