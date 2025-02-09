# **Interactive Installation: Exploring Motion Tracking with TouchDesigner**

Welcome to my final-year Passion Projectproject repository! This project focuses on exploring how **motion tracking** can be used to create **engaging and immersive interactive installations**, built within **TouchDesigner** for real-time graphics and interaction design.

You canfind an overview & documentation of my work & process on the dedicated blog. Located at http://blog.jonahdesmet.be

---

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Research Question](#research-question)
3. [Directory Structure](#directory-structure)
4. [Setup Instructions](#setup-instructions)
5. [Project Deliverables](#project-deliverables)
7. [Acknowledgments](#acknowledgments)

---

## **Project Overview**

This project investigates how **body tracking** and **3D modeling** can be combined in TouchDesigner to create an interactive installation. Key areas of focus include:
- Developing **motion-reactive visuals**.
- Experimenting with **3D environments** for immersive projections.
- Integrating **real-time body tracking** using the NVIDIA Bodytrack CHOP, Google's Mediapipe, A little bit of Kinect and other techniques.

The end goal was to provide a working prototype or demonstrations that can serve as a foundation for future projects in **interactive installations**.

---

## **Research Question**

> **"How can motion tracking be leveraged to create an interactive installation that stimulates exploration and engagement?"**

This research question has driven all experiments, testing, and development throughout the project.

---

## **Directory Structure**

Here’s an overview of the repository’s organization:

```
project-repo/
│
├── README.md                     # This file
├── assets/                       # External assets used in the project
│   ├── images/                   # Reference images, textures
│   ├── videos/                   # Video files for input or demos
│   └── audio/                    # Audio files for sound effects
│   └── models/                   # 3D models
│
├── src/                          # Source TouchDesigner files
│   ├── grafitti_wall_main.toe    # Main project file
│   ├── experiments/              # Individual experiment files
│   └── modules/                  # Reusable .tox components
│
```

---

## **Setup Instructions**

### **1. Prerequisites**
- Install **TouchDesigner** (Non-commercial or Pro version).
- Use a **Windows PC** for body tracking experiments with NVIDIA Bodytrack CHOP requires Windows & Kinect tracking.
- All the other demo's should work on whatever plaform you are using, including MAC.
- Additional dependencies:
  - **Mediapipe** (optional for body tracking experiments).

### **2. Clone the Repository**
```bash
git clone https://github.com/JanoahDev/InteractiveWall.git
cd <InteractiveWall>
```

### **3. Open in TouchDesigner**
- Navigate to the `src/` folder and open the `main.toe` file in TouchDesigner.

### **4. Assets**
- Download any additional assets (videos, audio, or 3D models) from the `assets/` directory.

---

## **Project Deliverables**

### **1. TouchDesigner Files**
- **Main Project File**: `src/grafitti_wall_main.toe` – A consolidated project combining key features like motion tracking, 3D modeling, and interactivity.
- **Experiment Files**: `src/experiments/` – A collection of individual experiments, including:
  - **Basic Masking**: Static mask reveal using layered composite TOPs.
  - **Body Tracking Skeleton**: Generating a 3D skeleton with NVIDIA Bodytrack CHOP.
  - **Dynamic Masking**: Connecting the 3D skeleton to the masking setup.
  - **3D Room Experiment**: Exploring TouchDesigner’s 3D scene builder for interactive environments.
  - **3D Line Tracing**: Creating interactive 3D lines based on mouse or body tracking input.
  - **Furry Texture Effect**: Experimenting with procedural textures and noise manipulation.
  - **Particle GPU Experiment**: Converting video or input sources into dynamic particle systems.
  - **Graffiti Wall Prototype**: Simulating an interactive spray-paint experience using body tracking and animation triggers.

---

## **Acknowledgments**

This project was made possible with the guidance of my teachers, my project coach **Koen De Weggheleire** and inspiration from the very broad TouchDesigner community, and resources such as:
- [TouchDesigner Official Documentation](https://docs.derivative.ca/)
- [YouTube Tutorials](https://www.youtube.com)

Special thanks to the **Devine Program** for providing the opportunity to explore creative development in a hands-on environment.

---

Feel free to reach out with any questions or feedback on the project!

--- 