# vehicle-queue-monitor
Computer Vision-Based Vehicle Queue and Wait-Time Monitoring using PyTorch YOLOv8

# 🚧 Vehicle Queue & Wait-Time Monitoring (Draft Prototype)

> **Status:** Work in Progress  
> This repository contains an early prototype for detecting and analyzing vehicle queues using computer vision.  
> The goal is to later expand this into a publishable independent-study project on **Computer Vision-Based Queue and Wait-Time Monitoring for Public Transit Stops**.

---

## 🎯 Objective
To explore how pretrained deep-learning models (YOLOv8) can estimate:
- Vehicle **queue lengths** within a region of interest (ROI)  
- Approximate **wait times** for each vehicle  
- Visual insights for traffic or public-transit optimization

---

## 🧠 Current Progress
✅ Video frame extraction  
✅ Vehicle detection using pretrained **YOLOv8n.pt** (PyTorch backend)  
✅ ROI-based queue counting  
⚙️ Work in progress: vehicle tracking (SORT/DeepSORT)  
📊 Next: accurate wait-time calculation and visualization dashboards  

---

## 🧩 Tools & Environment
- **Language:** Python 3  
- **Libraries:** PyTorch, Ultralytics, OpenCV, Pandas, Matplotlib  
- **Environment:** Google Colab  
- **Dataset:** sample traffic videos (UA-DETRAC / YouTube clips)
