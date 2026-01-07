project:
  title: "🔥 Real-Time Flame Detection using Computer Vision"
  subtitle: "AI-powered flame detection with smart color logic and instant alerts"

badges:
  - "https://img.shields.io/badge/Python-3.8+-blue"
  - "https://img.shields.io/badge/OpenCV-Computer%20Vision-green"
  - "https://img.shields.io/badge/Status-Active-success"
  - "https://img.shields.io/badge/License-MIT-yellow"

intro_animation:
  gif: "https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif"
  description: >
    This project demonstrates real-time flame detection using a live webcam feed.
    The system intelligently detects a lighter flame by verifying a white hot core
    inside a yellow/orange flame body and triggers an audio alarm instantly.

overview:
  description: >
    This is a real-time flame detection system built using Python and OpenCV.
    Instead of relying on deep learning, it uses HSV color space intelligence
    to accurately detect small flames while reducing false positives from normal
    lighting conditions.

  highlights:
    - Real-time webcam processing
    - White core + yellow flame verification
    - Intelligent HSV-based logic
    - Audio alarm on detection
    - Lightweight and fast execution

how_it_works:
  animation: "https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif"
  steps:
    - Capture live video from webcam
    - Apply Gaussian blur to reduce noise
    - Convert frame from BGR to HSV color space
    - Detect yellow/orange flame region
    - Detect white hot core (high brightness, low saturation)
    - Dilate yellow region to ensure connectivity
    - Confirm flame only if white core exists inside yellow region
    - Trigger alarm and display bounding box

tech_stack:
  icons:
    - "https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"
    - "https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg"
  technologies:
    - Python
    - OpenCV
    - NumPy
    - Pygame

use_cases:
  animation: "https://media.giphy.com/media/l0HlQ7LRalYnxjvMs/giphy.gif"
  applications:
    - Fire safety and early warning systems
    - Smart surveillance solutions
    - Industrial monitoring
    - AI automation projects
    - Educational computer vision demos

installation:
  steps:
    - "Clone the repository from GitHub"
    - "Install dependencies using pip"
    - "Run the Python script to start detection"

  commands:
    clone: "git clone https://github.com/your-username/real-time-flame-detection-opencv.git"
    install: "pip install opencv-python numpy pygame"
    run: "python flame_detection.py"

requirements:
  - Python 3.8 or higher
  - Webcam
  - Speakers or headphones for alarm

limitations:
  - Optimized for small flames (lighter-scale)
  - HSV thresholds may require tuning per environment
  - Not designed for large wildfire detection

future_scope:
  animation: "https://media.giphy.com/media/3oKIPnAiaMCws8nOsE/giphy.gif"
  improvements:
    - Deep Learning integration (YOLO / CNN)
    - Smoke detection support
    - Mobile camera compatibility
    - IoT-based fire alert system
    - Cloud notifications

author:
  name: "Muhammad Asim"
  role: "Software Engineer | AI & Computer Vision Developer"
  contact:
    instagram: "DM 'LINK' on Instagram for source code"
    github: "More AI projects coming soon"

license:
  type: "MIT License"
  note: "Free to use, modify, and distribute"

footer:
  animation: "https://media.giphy.com/media/xUPGcguWZHRC2HyBRS/giphy.gif"
  message: "⭐ If you like this project, please star the repository. Your support matters!"
