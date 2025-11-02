# 🏊‍♂️ Diving Phase Detection with YOLOv11
**Author:** Omar Aloweidi  

This project detects and classifies diving phases — **Takeoff**, **Rotation**, **Entry**, and **Underwater** — from video frames using **YOLOv11**.  
It was built entirely from scratch using a custom-labeled dataset and tested on real Olympic footage.

---

## 📁 Dataset
- 54+ custom-labeled frames using **Roboflow**
- Classes:
  - `Takeoff`
  - `Rotation`
  - `Entry`
  - `Underwater`
- Images collected from multiple angles and lighting conditions  
- Annotated and exported for **YOLOv8/YOLOv11** format

---

## ⚙️ Model Details
- **Base Model:** YOLOv11n (lightweight, real-time capable)
- **Training Device:** CPU (20–30 epochs)
- **Framework:** [Ultralytics](https://github.com/ultralytics/ultralytics)
- **Validation Metric:** *(add mAP once tested)*

---

## 🚀 Demo Results
**Prediction Example:**

