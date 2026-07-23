# AI-Waste-Segregation-Using-CNN
AI-powered waste segregation system using Convolutional Neural Networks (CNN) for image classification with ESP32-based smart bin automation.


# ♻️ AI-Based Smart Waste Segregation System using CNN & ESP32

# 📌 Project Overview

Waste segregation is one of the biggest challenges in modern waste management. Manual segregation is slow, unhygienic, and often inaccurate, resulting in poor recycling efficiency and increased environmental pollution.

This project presents an **AI-powered Smart Waste Segregation System** that automatically classifies waste using a **Convolutional Neural Network (CNN)**. A USB camera captures the waste image, which is processed using an image classification model. Based on the predicted category, an ESP32 microcontroller controls a servo motor to direct the waste into the appropriate collection bin.

The system provides an intelligent, low-cost, scalable, and automated solution for smart waste management.

---

# 🎯 Objectives

- Develop an AI-powered waste segregation system.
- Automatically classify waste into:
  - Dry Waste
  - Wet Waste
  - Hazardous Waste
- Reduce manual waste handling.
- Improve recycling efficiency.
- Integrate Computer Vision with Embedded Systems.
- Build an intelligent smart-city waste management prototype.

---

# ❗ Problem Statement

Manual waste segregation is slow, unhygienic, and prone to human error. Mixing different categories of waste reduces recycling efficiency and increases environmental pollution.

This project addresses these challenges by combining Artificial Intelligence and IoT to automate waste classification and sorting.

---

# 🛠 Technologies Used

## Programming

- Python

## Artificial Intelligence

- Machine Learning
- Deep Learning
- Convolutional Neural Networks (CNN)
- Computer Vision
- Image Classification

## Hardware

- ESP32
- Servo Motor
- IR Sensor
- USB Camera

## Development Tools

- VS Code
- Git
- GitHub

---

# ⚙️ System Architecture

```
Waste Object
      │
      ▼
IR Sensor detects object
      │
      ▼
USB Camera captures image
      │
      ▼
Image Preprocessing
      │
      ▼
CNN Model Prediction
      │
      ▼
Waste Category Prediction
      │
      ▼
ESP32 Controller
      │
      ▼
Servo Motor Rotation
      │
      ▼
Waste dropped into correct bin
```

---

# 🔄 Project Workflow

1. Waste is placed at the system inlet.
2. IR sensor detects the presence of waste.
3. USB camera captures an image.
4. Image is resized and preprocessed.
5. CNN extracts image features.
6. Waste is classified.
7. Classification result is sent to ESP32.
8. ESP32 rotates the servo motor.
9. Waste is dropped into the correct bin.
10. Servo returns to its initial position.

---

# 🧠 CNN Model

The Convolutional Neural Network performs automatic feature extraction from waste images and classifies them into predefined categories.

The model performs:

- Image preprocessing
- Feature extraction
- Pattern learning
- Classification
- Prediction

---

# 🗂 Waste Categories

- Dry Waste
- Wet Waste
- Hazardous Waste

---

# 💻 Hardware Components

- ESP32 Development Board
- USB Camera
- IR Sensor
- Servo Motor
- Waste Collection Bins
- Power Supply

---

# 📊 Features

- AI-powered waste classification
- Computer Vision based image recognition
- Real-time prediction
- Automated waste sorting
- Embedded system integration
- Low-cost implementation
- Smart city application
- Eco-friendly solution

---

# 📈 Advantages

- Reduces manual effort
- Improves hygiene
- Increases recycling efficiency
- Real-time waste classification
- Accurate automated sorting
- Supports smart waste management
- Cost-effective prototype
- Easily scalable

---

# ⚠ Limitations

- Performance depends on CNN model quality.
- Proper lighting is required.
- Similar-looking waste may be misclassified.
- Camera quality affects prediction.
- Hardware calibration is necessary.

---

# 🚀 Future Improvements

- Deploy the CNN model on edge devices.
- Add more waste categories.
- Mobile application integration.
- Cloud-based monitoring.
- IoT dashboard.
- Smart bin level monitoring.
- Voice notifications.
- RFID-based waste identification.

---

# 📂 Project Structure

```
AI-Based-Waste-Segregation-Using-CNN/

│── dataset/
│── images/
│── models/
│── notebooks/
│── src/
│── README.md
│── requirements.txt
│── LICENSE
```

---

# 📷 Screenshots

Add screenshots here:

<img width="757" height="642" alt="CNN_PROJECT" src="https://github.com/user-attachments/assets/30b77778-1a01-4bc1-af97-54929d8c2c2c" />

---

# 🎯 Applications

- Smart Cities
- Educational Institutes
- Offices
- Hospitals
- Residential Societies
- Recycling Plants
- Public Waste Collection

---

# 📚 Skills Demonstrated

- Artificial Intelligence
- Machine Learning
- Deep Learning
- CNN
- Computer Vision
- Image Classification
- Python
- ESP32
- Embedded Systems
- IoT
- Image Processing
- Model Evaluation
- Hardware Integration
- Automation

---

# 📖 References

- Automated Waste Segregation System using Arduino and IoT
- IoT-Based Intelligent Waste Management System
- IoT-Enabled Waste Management and Segregation System
- Design and Implementation of Automated Waste Segregation using Arduino Uno

---

# 👩‍💻 Author

**Kasturi Bhide**

Electronics & Telecommunication Engineering

Dr. D. Y. Patil Institute of Technology, Pune

GitHub: https://github.com/kbhide47

---

## ⭐ If you found this project useful, consider giving it a Star!
