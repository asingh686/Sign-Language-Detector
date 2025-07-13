# Sign-Language-Detector
Real-time hand gesture detection using MediaPipe &amp; OpenCV – foundation for future sign language applications

# 🤟 Sign Language Detection using Python, OpenCV & MediaPipe

A real-time hand gesture detection project that uses MediaPipe and OpenCV to recognize the number of fingers shown and map them to basic sign language alphabets.

---

## 📌 Project Overview

This project provides a foundation for gesture-based human-computer interaction and opens up possibilities for:

- 📱 Mobile or Web-based sign language translation tools  
- 🧠 Full sign recognition using ML (ASL/ISL alphabets)  
- 🎯 Real-time use in education, hospitals & help desks  
- 🌐 Bridging the gap for differently-abled communities

While the current version detects simple finger counts and maps them to a few letters, it can be scaled to support full words or phrases using ML classification.

---

## 🛠️ Technologies Used

- `Python 3.12`
- `OpenCV`
- `MediaPipe`

---

## 🚀 How It Works

- Captures live video feed using webcam
- Detects hand landmarks in real-time using MediaPipe
- Counts the number of fingers raised using geometric rules
- Maps the finger count to a pre-defined sign (A to F)
- Displays the detected sign on the screen

---

## 📷 Sample Output

![sample output](sample%20output.png)

---

## 📦 Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/asingh686/sign-language-detector.git
   cd sign-language-detector

