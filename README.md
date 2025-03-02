# 🚀 Object Detection and Tracking using YOLOv5

## 📌 Overview
This project implements **real-time object detection and tracking** using **YOLOv5**. The system captures live video, detects objects, and overlays bounding boxes on detected objects. Built using **PyTorch** and **OpenCV**, it delivers efficient and accurate detection.

---

## 🎯 Features
✅ YOLOv5-powered object detection  
✅ Real-time detection via webcam  
✅ Bounding box visualization with confidence scores  
✅ Configurable **confidence** & **IoU thresholds**  
✅ Runs on **CPU** or **GPU**  

---

## 🔧 Requirements
Ensure you have the following dependencies installed:

```bash
pip install torch torchvision torchaudio opencv-python numpy yolov5
```

---

## 🛠 Installation
### 1️⃣ Clone the repository:
```bash
git clone https://github.com/shwethashaji-ai/CodeAlpha_object_detectionn
cd object detection
```

### 2️⃣ Download the YOLOv5 pre-trained model:
```bash
wget https://github.com/ultralytics/yolov5/releases/download/v6.0/yolov5s.pt
```

---

## 🚀 Usage
Run the script to start real-time object detection:
```bash
python object detection.ipynb
```
🛑 **Press `q` to exit the detection window.**

---

## 🏗 Code Structure
📌 **`load_model()`** → Loads the YOLOv5 model  
📌 **`preprocess_frame()`** → Prepares the frame for detection  
📌 **`detect_objects()`** → Runs object detection  
📌 **`draw_boxes()`** → Draws bounding boxes with labels  
📌 **`object_detection_realtime()`** → Captures video and processes frames  

---

## ⚡ Notes
⚠️ Ensure you have a **working webcam** connected.  
⚙️ Adjust **confidence and IoU thresholds** in `detect_objects()` for improved accuracy.  
💻 To run on **GPU**, change `device='cpu'` to `device='cuda'` in `load_model()`.  

---

## 📜 License
📄 **MIT License**  

🛠 **Happy Coding!** 🚀🎯

