# 🚀 Multi-Task Computer Vision Suite using YOLOv8

A modular and scalable **Computer Vision system** built using **YOLOv8** for real-time object detection, tracking, and vehicle speed estimation.

This project demonstrates real-world applications of deep learning in **traffic monitoring, surveillance, and intelligent systems**.

---

## 📌 Features

* 🚗 Vehicle Detection & Tracking
* ⚡ Real-Time Speed Estimation
* 📦 Object Detection using YOLOv8
* 🔲 Oriented Bounding Box Detection (OBB)
* 🎥 Video Processing with OpenCV
* 📊 Output Visualization

---

## 🧠 Tech Stack

* Python
* OpenCV
* YOLOv8 (Ultralytics)
* NumPy / Pandas

---

## 📁 Project Structure

```
Multi-Task-Computer-Vision-Suite-using-yolov8/
│
├── data/
│   ├── highway.mp4
│   ├── highway_mini.mp4
│
├── models/
│   ├── yolov8n.pt
│   ├── yolov8s.pt
│
├── notebooks/
│   ├── obb.ipynb
│   ├── speed_estimation.ipynb
│
├── output/
│   ├── output.avi
│
├── vechile_speed_detection/
│   └── outputs/
│       ├── Speed_detection(1).png
│       ├── Speed_detection(2).png
│       ├── Speed_detection(3).png
│       ├── Speed_detection(4).png
```

---

## ▶️ How to Run

### 1️⃣ Install Dependencies

```bash
pip install ultralytics opencv-python numpy pandas
```

### 2️⃣ Run Notebook / Script

```bash
jupyter notebook
```

---

## 📸 Output Results

### 🚗 Vehicle Speed Detection

<p align="center">
  <img src="./vechile_speed_detection/outputs/Speed_detection(1).png" width="45%"/>
  <img src="./vechile_speed_detection/outputs/Speed_detection(2).png" width="45%"/>
</p>

<p align="center">
  <img src="./vechile_speed_detection/outputs/Speed_detection(3).png" width="45%"/>
  <img src="./vechile_speed_detection/outputs/Speed_detection(4).png" width="45%"/>
</p>

---

## 🎯 Use Cases

* Smart Traffic Monitoring
* Speed Violation Detection
* Intelligent Surveillance Systems
* Autonomous Driving Research

---

## 🚀 Future Enhancements

* 🚦 Traffic Signal Violation Detection
* 🔍 License Plate Recognition (ANPR)
* 🧍 Multi-Object Tracking (DeepSORT)
* 🌐 Web Dashboard Integration

---

## 💡 Highlights

* Designed a **modular multi-project architecture**
* Implemented **real-time speed estimation using tracking**
* Used **pretrained YOLOv8 models for efficient inference**
* Structured outputs for scalability and clarity

---

## 👨‍💻 Author

**Aditya Sikarwar**
B.Tech (Artificial Intelligence)

---

## ⭐ Note

> Folder name is currently **vechile_speed_detection** (intentional for compatibility with current project structure).
> Make sure paths match exactly (case-sensitive) when viewing on GitHub.
