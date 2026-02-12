# 🌌 Galaxy - Space Runner

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python)
![Kivy](https://img.shields.io/badge/Framework-Kivy-green?logo=kivy)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Android-lightgrey)

**Galaxy** is a space runner arcade game developed in Python using the Kivy framework. It features dynamic 3D perspective movement and procedural path generation.

---

## 📘 Technical Documentation
The primary focus of this repository is the comprehensive technical documentation. This resource is essential for understanding how the game's engine, mathematical transformations, and class structures interact.

> 📁 **[Access the Technical Documentation PDF here](docs/Documentatie_Tehnica_Galaxy.pdf)**
>
> *This document provides a deep dive into:*
> * **3D Projection Logic:** How 2D coordinates are transformed to create a sense of depth.
> * **Class Architecture:** Detailed breakdown of `MainWidget`, `Ship`, and UI components.
> * **Input Handling:** Implementation of dual-control systems for keyboard and touch interfaces.
> * **Resource Management:** Configuration of `.kv` files and high-resolution assets.

---

## 🚀 Getting Started

### 🎮 For Players (Windows)
No Python installation is required.
1. Navigate to the **[Releases](https://github.com/davidCrejenovschi/Galaxy/releases)** section.
2. Download the latest version: `Galaxy_Game_v1.0_Windows.zip`.
3. Extract the folder and launch `GalaxyGame.exe`.

### 💻 For Developers
To explore the source code referenced in the documentation:
```bash
# Clone the repository
git clone [https://github.com/davidCrejenovschi/Galaxy.git](https://github.com/davidCrejenovschi/Galaxy.git)

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
