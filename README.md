
# 🌿 GreenSense — Plant Health Detective & Diagnostic System

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green.svg)](https://opencv.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**GreenSense** is a desktop-based plant health detection and diagnostic application. It uses computer vision techniques and structured botanical databases to analyze leaf imagery, identify plant pathologies, and provide treatment recommendations.

---

## 📌 Features

- **🔍 Image Preprocessing Pipeline:** Automated color-space transformation, contrast enhancement, and anomaly isolation using OpenCV & NumPy.
- **🩺 Plant Health Detection:** Rule-based and feature-driven detection logic to classify leaf symptoms accurately.
- **📚 Botanical Information Database:** Comprehensive repository mapping disease symptoms to botanical profiles, causal factors, and remedies.
- **🖥️ Intuitive GUI:** User-friendly graphical interface built for real-time image upload, diagnostic visualization, and automated report generation.
- **⚙️ Modular Architecture:** Decoupled codebase separated into configuration, image processing, database, and UI layers for easy extensibility.

---

## 🏗️ Project Architecture & File Structure

```text
├── 5. Main Plant Health Detector/   # Core diagnostic logic and disease classification
├── 6.Graphical User Interface/      # Desktop GUI implementation
├── 7.Main Application Entry Point/  # Central application launcher
├── Image Processing Module/         # Image enhancement, filtering, and feature extraction
├── Plant Information Database/      # Botanical metadata, symptoms, and treatment mappings
├── Configuration.File               # App constants, paths, and environment settings
├── requirements.txt                 # Project dependencies
└── Preview/                         # Screenshots and application demo assets
