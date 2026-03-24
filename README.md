# Adeept 5-DOF Robotic Arm for Isaac Gym

A unified URDF and STL mesh set for the Adeept 5-DOF robotic arm, specifically optimized for high-performance physics simulations like **NVIDIA Isaac Gym**.

---

## 🚀 Overview
This repository provides a simulation-ready URDF model of the Adeept 5-DOF Robotic Arm. Each link has been carefully aligned with its rotation pivot at the origin (0,0,0) to ensure stable and intuitive joint control.

## 📂 Project Structure
- `resources/urdf/`: Contains the master `.urdf` file.
- `resources/meshes/`: Includes all `.stl` link files.

## 🛠️ Key Features
- **Pivot-Aligned Meshes**: No more visual offsets. All meshes rotate around the global origin.
- **Simulation Optimized**: Includes simplified collision boxes and realistic inertial properties for Isaac Gym.
- **Mimic Joint Support**: Pre-configured mimic tags for parallel gripper control.

## 📜 Disclaimer
This data is not an official release from Adeept and has been developed independently for personal educational and simulation purposes. The creator is not responsible for any issues arising from the use of this data in hardware or software environments.

## 🤝 Attribution
This project is based on the [Adeept 5-DOF Robotic Arm](https://www.adeept.com/).