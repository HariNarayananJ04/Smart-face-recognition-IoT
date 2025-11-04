# 🧠 Smart Face Recognition System



<p align="center">
  <b>AI-powered Face Recognition project built using Python and OpenCV ⚙️</b>
</p>

---

## 📖 Overview

This project is a **Smart Face Recognition System** developed in **Python** using **OpenCV** and the **LBPH (Local Binary Pattern Histogram)** algorithm.  
It captures human faces, trains a recognition model, and identifies individuals through a live webcam feed.  
The system is lightweight, accurate, and works efficiently in real-time environments.

---

## 🧩 Features

- 👁️ Real-time **Face Detection & Recognition**  
- ⚙️ Uses **Haar Cascade Classifier** for detecting faces  
- 🧠 Trains model using **LBPH Algorithm**  
- 🧾 Generates unique dataset for each person  
- 💡 Modular Python code (clean and easy to understand)

---

## 🧠 Algorithms Used

| Function | Algorithm | Description |
|-----------|------------|-------------|
| **Face Detection** | Haar Cascade Classifier | Detects human faces using the Viola–Jones algorithm |
| **Face Recognition** | LBPH (Local Binary Pattern Histogram) | Creates unique texture patterns for each person’s face |

---

## 🗂️ Project Structure

```
Smart-Face-Recognition-IoT/
│
├── src/
│   ├── Readface.py        -> Captures face images & stores dataset
│   ├── Train.py           -> Trains LBPH model using captured data
│   ├── Detectface.py      -> Recognizes faces in real-time using webcam
│
├── data/
│   ├── haarcascade_frontalface_default.xml  -> Face detection model
│   └── hh.xml
│
├── models/
│   ├── trainer.yml        -> Trained model file (auto-generated)
│   └── name_labels.txt    -> Mapping of labels ↔ names
│
├── dataset/               -> Automatically created folder for face images
│   └── Profile.csv
│
├── requirements.txt       -> Python dependencies
├── .gitignore             -> Files to ignore during upload
└── README.md              -> Documentation file
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/HariNarayananJ04/Smart-face-recognition-IoT.git
cd Smart-face-recognition-IoT
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Capture Face Images
Run this command to capture your dataset:
```bash
python src/Readface.py
```

- Captures ~60 grayscale images per person  
- Stores them in the `dataset/` folder  
- Adds your name to `Profile.csv`

### 4️⃣ Train the Model
```bash
python src/Train.py
```

- Generates a trained model file `trainer.yml` under `models/`.

### 5️⃣ Recognize Faces
Run:
```bash
python src/Detectface.py
```

- Opens your webcam  
- Detects and recognizes faces using the trained model  
- Displays the recognized person’s name with confidence level

---

## 🎯 Real-World Applications

- 🏫 Smart Attendance Systems  
- 🏢 Secure Office Entry Systems  
- 🏠 Smart Home Face Recognition  
- 🚪 Visitor Identification Systems  

---

## 📊 Tech Stack

| Category | Tools / Tech |
|-----------|--------------|
| **Languages** | Python |
| **Libraries** | OpenCV, NumPy, Pillow |
| **Algorithm** | Haar Cascade + LBPH |
| **IDE** | VS Code / PyCharm |
| **OS Tested** | Windows 10 / 11 |

---

## 🧠 Working Flow

```
[ Capture Face ] → [ Train Model ] → [ Recognize Face ]
```

---

## ⚡ Fun Fact

> I don’t chase recognition...  
> I *code* it 😎  

---

## 📬 Connect with Me

📧 **Email:** [harinarayananbecse@gmail.com](mailto:harinarayananbecse@gmail.com)  
💼 **LinkedIn:** [www.linkedin.com/in/hari-narayanan-j-be](https://www.linkedin.com/in/hari-narayanan-j-be)  
💻 **GitHub:** [github.com/yourusername](https://github.com/yourusername)

---

<h3 align="center">🛰️ End of Transmission ⚙️</h3>
