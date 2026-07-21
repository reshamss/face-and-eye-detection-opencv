# 👁️ Face and Eye Detection using OpenCV

A real-time **Face and Eye Detection** application developed using **Python** and **OpenCV**. This project uses Haar Cascade Classifiers to detect human faces and eyes from a live webcam feed in real time.

---

## 📌 Overview

This project demonstrates how to use OpenCV's pre-trained Haar Cascade models to perform real-time object detection. It captures video from the webcam, detects faces in each frame, and identifies eyes within the detected face regions.

---

## ✨ Features

- 📷 Real-time webcam face detection
- 👀 Eye detection inside detected faces
- 🟩 Bounding boxes around faces and eyes
- ⚡ Fast and lightweight implementation
- 🖥️ Easy to understand and beginner-friendly

---

## 🛠️ Technologies Used

- Python 3.x
- OpenCV
- NumPy
- Haar Cascade Classifiers

---

## 📂 Project Structure

```
face-and-eye-detection-opencv/
│
├── face_detection_realtime.py      # Face and eye detection using webcam
├── face_detection_sample.py        # Face detection example
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/reshamss/face-and-eye-detection-opencv.git
```

### 2. Navigate to the project folder

```bash
cd face-and-eye-detection-opencv
```

### 3. (Optional) Create a virtual environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install the required packages

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

### Run Face and Eye Detection

```bash
python face_detection_realtime.py
```

or

```bash
python face_detection_sample.py
```

A webcam window will open showing:

- ✅ Face Detection
- ✅ Eye Detection

Press **Q** to close the application.

---

## 📦 Requirements

Create a `requirements.txt` file with the following content:

```text
opencv-python
numpy
```

## 🧠 How It Works

1. Opens the webcam using OpenCV.
2. Captures video frames continuously.
3. Converts each frame to grayscale.
4. Detects faces using the Haar Cascade Face Classifier.
5. Detects eyes within each detected face.
6. Draws bounding boxes around detected faces and eyes.
7. Displays the processed video in real time.

---

## 📸 Output

The application displays:

- 🟩 Green rectangle around the detected face.
- 🟦 Blue/Green rectangles around detected eyes.
- Live webcam feed with real-time detection.

---

## 📚 OpenCV Haar Cascade Models Used

- `haarcascade_frontalface_default.xml`
- `haarcascade_eye.xml`

These classifiers are included with the OpenCV package.

---

## 🚀 Future Improvements

- Face recognition
- Smile detection
- Emotion detection
- Face mask detection
- Attendance system integration
- Deep Learning-based face detection (DNN/YOLO)

---

## 👨‍💻 Author

**Resham Shinalkar**

Bachelor of Engineering (Artificial Intelligence & Data Science)

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub!
