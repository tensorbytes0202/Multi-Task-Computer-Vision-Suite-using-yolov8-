# 🚀 Multi-Task Computer Vision System (YOLOv8)

A modular and scalable computer vision system built using **YOLOv8** for real-time object detection, tracking, and vehicle speed estimation.

This project demonstrates practical implementation of deep learning in real-world scenarios such as **traffic monitoring and intelligent surveillance systems**.

---

## 📌 Key Features

* 🚗 Vehicle Detection & Tracking
* ⚡ Real-Time Speed Estimation
* 📦 Object Detection using YOLOv8
* 🔲 Oriented Bounding Box Detection (OBB)
* 🎥 Video Processing with OpenCV
* 📊 Output Visualization & Saving Results

---

## 🧠 Tech Stack

* Python
* OpenCV
* Ultralytics YOLOv8
* NumPy / Pandas

---

## 📁 Project Structure

```
Multi-Task Computer Vision System/
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
├── vehicle_speed_detection/
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

### 2️⃣ Run Detection / Notebook

```bash
jupyter notebook
```

or run scripts directly:

```bash
python main.py
```

---

## 📸 Output Results

### 🚗 Vehicle Speed Detection

![Speed Detection 1](vehicle_speed_detection/outputs/Speed_detection\(1\).png)
![Speed Detection 2](vehicle_speed_detection/outputs/Speed_detection\(2\).png)
![Speed Detection 3](vehicle_speed_detection/outputs/Speed_detection\(3\).png)
![Speed Detection 4](vehicle_speed_detection/outputs/Speed_detection\(4\).png)

---

## 🎯 Use Cases

* Smart Traffic Monitoring Systems
* Speed Violation Detection
* Intelligent Surveillance
* Autonomous Driving Research
* Urban Planning & Analytics

---

## 🚀 Future Enhancements

* 🚦 Traffic Signal Violation Detection
* 🔍 License Plate Recognition (ANPR)
* 🧍 Multi-Object Tracking (DeepSORT Integration)
* ☁️ Deployment on Cloud / Edge Devices
* 📱 Web Dashboard for Live Monitoring

---

## 💡 Highlights

* Designed a **modular architecture** for handling multiple CV tasks
* Used **pretrained YOLOv8 models** for efficient real-time inference
* Implemented **speed estimation logic using frame tracking**
* Organized outputs and results for better visualization

---

## 👨‍💻 Author

**Aditya Sikarwar**
B.Tech (AI) Student

---

## ⭐ Note

This project is part of a larger vision to build an **end-to-end AI-powered surveillance system** combining detection, tracking, and analytics.
