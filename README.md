<h1 align="center">🧠 Smart Face Recognition System</h1>

<p align="center">
  <img src="https://media.tenor.com/NOYF3f82b_gAAAAC/iron-man-jarvis.gif" width="700" alt="Jarvis HUD"/>
</p>

<p align="center">
  <b>AI-powered Face Recognition project built using Python and OpenCV ⚙️</b>
</p>

---

## 📖 Overview
This project is a **Smart Face Recognition System** developed in **Python** using **OpenCV** and **LBPH (Local Binary Pattern Histogram)** algorithm.  

It captures human faces, trains a recognition model, and identifies individuals through a live webcam feed.  
The system is lightweight, accurate, and works efficiently in real-time environments.

---

## 🧩 Features
- 👁️ Real-time **Face Detection & Recognition**
- ⚙️ Uses **Haar Cascade Classifier** for detecting faces
- 🧠 Trains model using **LBPH Algorithm**
- 🧾 Generates unique dataset for each person
- 💡 Modular Python code (well-structured and easy to understand)

---

## 🧠 Algorithms Used

| Function | Algorithm | Description |
|-----------|------------|-------------|
| **Face Detection** | Haar Cascade Classifier | Detects human faces using the Viola–Jones algorithm |
| **Face Recognition** | LBPH (Local Binary Pattern Histogram) | Creates unique texture patterns for each person’s face |

---

## 🗂️ Project Structure

Smart-Face-Recognition-IoT/
│
├── src/
│ ├── Readface.py # Captures face images & stores dataset
│ ├── Train.py # Trains LBPH model using captured data
│ ├── Detectface.py # Recognizes faces in real-time using webcam
│
├── data/
│ ├── haarcascade_frontalface_default.xml # Face detection model
│ └── hh.xml
│
├── models/
│ ├── trainer.yml # Trained model file (auto-generated)
│ └── name_labels.txt # Mapping of labels ↔ names
│
├── dataset/ # Automatically created folder for face images
│ └── Profile.csv
│
├── requirements.txt # Python dependencies
├── .gitignore # Ignore unnecessary files
└── README.md # Documentation\

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
``bash
git clone https://github.com/HariNarayananJ04/Smart-Face-Recognition-IoT.git
cd Smart-Face-Recognition-IoT 

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Capture Face Images

Run the following to capture your dataset:
python src/Readface.py

-Captures ~60 grayscale images per person
-Stores them in dataset/ folder
-Adds your name to Profile.csv

4️⃣ Train the Model

python src/Train.py

This will generate the trained model file trainer.yml under models/.

5️⃣ Recognize Faces
Run:
python src/Detectface.py

The system will open your webcam
Detect and recognize faces using the trained model
Display the recognized person’s name with a confidence score

🎯 Real-World Applications

🏫Smart Attendance Systems
🏢 Secure Office Entry
🏠 Smart Home Face Recognition
🚪 Visitor Identification Systems

📊 Tech Stack
Category            	Tools / Tech
Languages           	Python
Libraries	            OpenCV, NumPy, Pillow
Algorithm	            Haar Cascade + LBPH
IDE                   VS Code / PyCharm
OS Tested	            Windows 10 / 11

🧠 Working Flow

[ Capture Face ] → [ Train Model ] → [ Recognize Face ]

⚡ Fun Fact
I don’t chase recognition...
I code it 😎

📬 Connect with Me
📧 Email: harinarayananbecse@gmail.com
💼 LinkedIn: www.linkedin.com/in/hari-narayanan-j-be
💻 GitHub: github.com/yourusername

<h3 align="center">🛰️ End of Transmission — Jarvis Mode: Active ⚙️</h3> ```
