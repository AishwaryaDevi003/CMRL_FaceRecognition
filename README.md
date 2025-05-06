# CMRL_FaceRecognition
Deep Learning-based Face Recognition System 

# Face Recognition System 

A deep learning-based Face Recognition System developed for verifying staff . This system ensures secure and real-time face verification using webcam input and includes features like liveness detection, SQLite-based data management, and a PyQt5-based user interface.

---

## 🧠 Features

- Capture 20 images per user with augmentation and preprocessing
- Base64 image conversion and storage in SQLite
- Train deep learning model with face embeddings
- Liveness detection to prevent spoofing
- Real-time webcam verification
- PyQt5 GUI for user-friendly interface
- Logging of verification details (Name, Date, Time, Location, Accuracy)

---

## 📂 Project Structure

Face-Recognition-Project/
│
├── data/
│ └── images/ # Captured & preprocessed face images
│
├── embeddings/
│ └── face_embeddings.pkl # Serialized face embeddings
│
├── model/
│ └── face_recognition_model.h5
│
├── ui/
│ └── main_interface.py # PyQt5 GUI application
│
├── reports/
│ └── weekly_report.md # Weekly internship progress
│
├── database/
│ └── verification.db # SQLite DB storing user data
│
├── scripts/
│ ├── capture_faces.py
│ ├── preprocess.py
│ ├── train_model.py
│ ├── verify_face.py
│
├── README.md
└── requirements.txt

## 🛠️ Installation

1. **Clone the repository**
2. 
git clone https://github.com/your-username/Face-Recognition-Project.git
cd Face-Recognition-Project

Install dependencies
pip install -r requirements.txt

## 🚀 How to Run
Capture Faces
python scripts/capture_faces.py

Train Model
python scripts/train_model.py
Launch GUI
python ui/main_interface.py

## 🧾 Requirements
Add the following to requirements.txt:
opencv-python
numpy
Pillow
tensorflow
keras
pyqt5
sqlite3
imutils
scikit-learn
