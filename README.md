# 🔥 Real-Time Flame Detection using Computer Vision & AI

<p align="center">
  <img src="https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif" width="350">
</p>

<p align="center">
  <strong>Smart • Real-Time • Accurate Flame Detection using Computer Vision</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue">
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green">
  <img src="https://img.shields.io/badge/AI-Logic--Based-orange">
  <img src="https://img.shields.io/badge/License-MIT-yellow">
  <img src="https://img.shields.io/badge/Status-Active-success">
</p>

---

## 📌 Introduction

This project is a **real-time flame detection system** developed using **Python and OpenCV**.  
Unlike traditional detectors, this system uses **intelligent color and brightness logic** to detect a **lighter flame** by confirming:

- 🔥 A **white hot core**
- 🟡 Surrounded by a **yellow/orange flame body**

This dual-condition logic helps **avoid false detections** from normal lights or reflections.  
Once a flame is detected, an **audio alarm is triggered instantly** 🚨.

---

## 🎥 Real-Time Detection (Concept Animation)

<p align="center">
  <img src="https://media.giphy.com/media/l0HlQ7LRalYnxjvMs/giphy.gif" width="520">
</p>

---

## 🚀 Features

- ✅ Real-time webcam-based flame detection  
- ✅ HSV color space analysis  
- ✅ White core + yellow flame verification  
- ✅ Reduced false positives  
- ✅ Instant audio alert  
- ✅ Bounding box visualization  
- ✅ Lightweight & fast performance  

---

## 🧠 Detection Logic Explained

<p align="center">
  <img src="https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" width="480">
</p>

### 🔍 Step-by-Step Workflow

1. Capture live frames from the webcam  
2. Apply Gaussian Blur to reduce noise  
3. Convert image from BGR to HSV color space  
4. Detect yellow/orange flame regions  
5. Detect white hot core (high brightness, low saturation)  
6. Dilate flame region for connectivity  
7. Confirm flame only if white core exists inside flame body  
8. Trigger alarm and draw bounding box  

---

## 🛠️ Technologies Used

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="60">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" width="60">
</p>

- Python  
- OpenCV  
- NumPy  
- Pygame  

---

