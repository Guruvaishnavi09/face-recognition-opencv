# Face Recognition System using OpenCV

## 📌 Project Overview
This project implements a real-time Face Recognition System using OpenCV and Haar Cascade Classifier. The system captures facial images using a webcam, trains a Local Binary Pattern Histogram (LBPH) model, and performs real-time face recognition.

---

## 🛠 Technologies Used
- Python
- OpenCV
- NumPy
- Haar Cascade Classifier
- LBPH Face Recognizer

---

## 📂 Dataset Details
The dataset consists of 100 grayscale facial images captured using a webcam.  
Each image is resized to 200x200 pixels and stored locally for model training.

(Note: Dataset images are not uploaded to this repository for privacy reasons.)

---

## ⚙️ Project Workflow

### 1️⃣ Face Detection
- Haar Cascade Classifier is used to detect faces in real-time.
- Detected faces are cropped and converted to grayscale.

### 2️⃣ Dataset Collection
- 100 facial samples are collected using webcam.
- Images are stored in a local dataset folder.

### 3️⃣ Model Training
- LBPH (Local Binary Pattern Histogram) algorithm is used.
- The model is trained using the captured dataset.

### 4️⃣ Face Recognition
- Webcam captures live video.
- The trained model predicts the face.
- Displays:
  - **Unlocked – Confidence %** (if recognized)
  - **Face Not Found** (if not detected)

---

## ▶️ How to Run the Project

1. Install required libraries:
   ```bash
   pip install opencv-contrib-python numpy
