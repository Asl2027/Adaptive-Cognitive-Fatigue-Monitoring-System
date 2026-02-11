# 🧠 Adaptive Cognitive Fatigue Monitoring System

An AI-powered wearable system for real-time cognitive fatigue detection using EEG, Heart Rate Variability (HRV), and Galvanic Skin Response (GSR) signals with adaptive mobile feedback.

---

## 📌 Overview

The Adaptive Cognitive Fatigue Monitoring System is a multidisciplinary project that integrates wearable hardware, embedded systems, artificial intelligence, and mobile application development to monitor mental fatigue in real time.

The system collects physiological signals, processes them using AI/ML models, and provides personalized, adaptive feedback through a mobile application to help users manage stress and prevent burnout.

---

## 🎯 Problem Statement

In today’s digital environment, prolonged screen exposure and cognitive workload often result in mental fatigue, reduced concentration, and decreased productivity.

Traditional fatigue monitoring methods are:
- Subjective (self-reported)
- Non-continuous
- Lacking real-time insights

This project addresses the need for an intelligent, adaptive, and continuous fatigue monitoring system.

---

## 🏗️ System Architecture

The system consists of four main modules:

### 1️⃣ Sensor Module
- EEG Sensor (Alpha, Beta, Theta waves)
- PPG Sensor (Heart Rate & HRV)
- GSR Sensor (Stress detection)
- Accelerometer (Movement detection)
- ESP32 Microcontroller with BLE communication

### 2️⃣ Data Processing & AI Module
- Signal filtering and normalization
- Feature extraction (EEG band power, HRV metrics, GSR levels)
- Fatigue classification using CNN / Random Forest
- Fatigue Score generation (0–100 scale)

### 3️⃣ Mobile Application (Flutter)
- Real-time fatigue dashboard
- Color-coded fatigue zones
- Trend visualization
- Mood journaling
- Personalized suggestions

### 4️⃣ Adaptive Feedback System
- Smart notifications
- One-Tap Relax Mode
- Gamified engagement tracking
- Personalized fatigue pattern learning

---

## 🚀 Key Features

- Real-time biometric monitoring
- AI-based fatigue classification
- Personalized adaptive feedback
- BLE communication between wearable and mobile app
- Mood journaling with AI insights
- Gamification for wellness motivation
- Minimalist, stress-reducing UI design

---

## 🛠 Hardware Components

- EEG Module (ADS1299 / OpenBCI compatible)
- MAX30102 (PPG Sensor)
- Grove GSR Sensor
- ESP32 Microcontroller
- BLE Communication Module
- Rechargeable Li-ion Battery
- Vibration Motor / RGB LED (Feedback)
- Custom Wearable Headband Design

---

## 💻 Software Stack

- Arduino IDE (Embedded C/C++)
- Python (Signal Processing & ML)
- TensorFlow Lite / Scikit-learn
- Flutter (Cross-platform Mobile App)
- SQLite (Local Data Storage)
- BLE API Integration

---

## 🤖 AI Model

- Extracts features from EEG, HRV, and GSR signals
- Classifies fatigue levels (Low / Moderate / High)
- Generates a dynamic Fatigue Score
- Learns user patterns for personalized feedback
- Deployed using TensorFlow Lite

---

## 📊 System Preview

(Add images in an /images folder and reference them like below)

![App Dashboard](images/dashboard.png)
![Wearable CAD Model](images/wearable_model.png)
![System Architecture](images/architecture.png)


## 🎥 Live Demo

Demo Video: https://acesse.one/linktovideo  
CAD Model: https://a360.co/43wmPC1  

---

## 📈 Impact

This project demonstrates:

- Integration of hardware + AI + mobile development
- Real-time physiological signal processing
- Embedded systems and BLE communication
- Human-centered adaptive UI/UX design
- Preventive mental health technology innovation
