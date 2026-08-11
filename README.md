# Demograph_AI

A Flask-based web application that uses deep learning to predict **age and gender** from a face image or via live webcam feed.

## Features
- 📷 Upload an image or use your webcam
- 🤖 Real-time age & gender prediction using Caffe pre-trained models
- 🌐 Lightweight Flask backend

## Steps to Setup

### 1. Clone the repository
```bash
git clone https://github.com/Akriti2002/Demograph_AI.git
cd Demograph_AI
```

### 2. Download model files
Download the following large model files and place them in the project root:
- `age_net.caffemodel`
- `gender_net.caffemodel`
- `opencv_face_detector_uint8.pb`

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the application
```bash
flask run
```
