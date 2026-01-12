
# 🧠 Trash Detector (YOLO-based Waste Classifier)

This project is an AI-powered waste classification system using **YOLOv3** and **OpenCV**. It recognizes and classifies waste types (e.g. plastic, paper, metal) in real time to assist recycling efforts.

## 🚀 Features

* 🎥 **Real-Time Detection:** Instantly detects waste materials using a webcam feed.
* 🗑️ **Multi-Class Classification:** Identifies various types of trash:
  * Plastic
  * Glass
  * Metal
  * Paper
* ⚡ **Performance:** Optimized with **YOLOv3-tiny** for faster processing on standard hardware.

## 📦 Installation

1. **Clone the repository**
```bash
git clone [https://github.com/YusufTufan/trash-detector-yolo.git](https://github.com/YusufTufan/trash-detector-yolo.git)
cd trash-detector-yolo
```
2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. Download Weights
```bash
Download the yolov3-tiny.weights file (not included due to size) and place it in the root directory.

Ensure coco.names (or your custom classes file) is present.
```
▶️ Usage
Run the main script to start the detection:
```bash
python real_time_yolo.py

Press q to quit the application.
```

Make sure to download the weights file for YOLO and place it in the root directory.

## 📌 Notes

- Ensure your webcam is connected
- Lighting conditions may affect detection accuracy.
- The model uses pre-trained weights which can be fine-tuned for better specific waste detection.

---

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

Copyright (c) 2023 YusufTufan


