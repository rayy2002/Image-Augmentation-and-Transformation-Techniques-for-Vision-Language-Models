# Inference-Time Image Augmentation for Robust Vision–Language Model Scene Understanding on Edge Devices

This repository contains the implementation, documentation, and experimental framework for my Master’s thesis at the University of Stuttgart.  
The project investigates how **inference-time image augmentation and transformation techniques** can improve scene comprehension in **Vision–Language Models (VLMs)** deployed on **edge-based autonomous robotic systems**.

Unlike traditional approaches that rely on dataset expansion or retraining, this work focuses exclusively on **runtime preprocessing** to enhance robustness under challenging sensing conditions—such as low light, motion blur, occlusion, or sensor noise—without modifying any model parameters.

---

## 📌 Project Goals

- Conduct a comprehensive review of state-of-the-art inference-time augmentation and transformation methods.
- Develop a **modular, reproducible software pipeline** for applying augmentation methods and forwarding processed inputs to VLMs.
- Establish **evaluation benchmarks** to compare augmented vs. baseline model performance.
- Analyse **performance vs. computational cost** on edge hardware to determine real-time feasibility.

---

## 🛠 Planned Technologies & Tools

- Python  
- OpenCV, Torch, torchvision  
- Vision–Language Models (e.g., LLaVA, MiniGPT, VL-Transformer models)  
- NVIDIA Jetson / edge AI hardware  
- Markdown-based documentation  
- Git & GitHub for reproducibility

---

## 📅 Project Status

> **Project Start:** December 2025  
> This repository is currently being initialized. Documentation, pipeline development, and experiments will be added continuously throughout the thesis.

---

## 📘 Academic Context

This thesis is conducted at the  
**Institute of Industrial Automation and Software Engineering (IAS)**  
University of Stuttgart.

- **Supervisor:** Joachim Grimstad  
- **Examiner:** Jun.-Prof. Dr.-Ing. Andrey Morozov  

---

## 📣 Notes

Daily progress and development notes will be committed regularly to maintain transparency and traceability throughout the project.

