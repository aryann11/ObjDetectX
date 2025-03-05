# ObjDetectX
ObjDetectX  is an cutting-edge artificial intelligence solution designed to revolutionize workplace safety through automated personal protective equipment (PPE) detection.
# 🛡️ SafeGuard: AI-Powered PPE Detection System

![PPE Detection Banner](https://img.shields.io/badge/AI-Safety%20Detection-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![YOLO](https://img.shields.io/badge/Model-YOLOv11-orange)
![Status](https://img.shields.io/badge/Status-Active%20Development-blueviolet)

## 🚨 Project Mission

**SafeGuard** is an cutting-edge artificial intelligence solution designed to revolutionize workplace safety through automated personal protective equipment (PPE) detection. Our mission is to reduce workplace accidents by ensuring critical safety standards are met in real-time.

## 🌟 Key Features

- 🤖 **Advanced AI Detection**
  - Real-time PPE identification
  - Multi-format inference (images/videos)
  - High-precision object detection

- 🔍 **Comprehensive Safety Monitoring**
  - Detects multiple PPE types
  - Configurable confidence thresholds
  - Instant safety compliance reporting

- 💻 **Flexible Deployment**
  - GPU-accelerated processing
  - Easy integration
  - Scalable architecture

## 🛠️ Quick Start Guide

### Prerequisites
- 💻 Python 3.8+
- 🖥️ CUDA-compatible GPU
- 📦 Dependencies: Ultralytics, Roboflow

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/safeguard-ppe-detection.git

# Install dependencies
pip install -r requirements.txt
```

### Training the Model
```bash
# Launch model training
yolo task=detect mode=train \
    data=dataset/data.yaml \
    model=yolo11n.pt \
    epochs=40 \
    imgsz=640
```

### Inference Modes
```bash
# Detect PPE in images
yolo task=detect mode=predict \
    model=best.pt \
    conf=0.25 \
    source=workplace_image.jpg

# Analyze safety in videos
yolo task=detect mode=predict \
    model=best.pt \
    conf=0.25 \
    source=safety_footage.mp4
```

## 📊 Performance Metrics

| Metric | Value |
|--------|-------|
| Model | YOLOv11 Nano |
| Training Epochs | 40 |
| Input Resolution | 640x640 |
| Default Confidence | 0.25 |

## 🔬 Technical Insights

### Dataset
- **Source**: Roboflow
- **Version**: 2.0
- **Annotation**: Professionally labeled PPE data

### Detection Capabilities
- Hard hat detection
- Safety vest identification
- Glove recognition
- Safety glasses tracking

## 🚀 Roadmap

- [ ] Real-time streaming detection
- [ ] Mobile application integration
- [ ] Cloud-based safety monitoring
- [ ] Enhanced multi-camera support

## 🤝 Contribution Guidelines

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request



**Email**: safeguard-support@example.com
**GitHub**: [SafeGuard PPE Detection](https://github.com/yourusername/safeguard-ppe-detection)

---

### 📃 License
MIT Open Source License

*Powered by AI, Driven by Safety* 🛡️
