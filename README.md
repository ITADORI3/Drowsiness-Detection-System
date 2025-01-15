# Drowsiness-Detection-System
This project implements a real-time Driver Drowsiness Detection System to enhance road safety by preventing accidents caused by drowsy driving. Using a webcam, the system monitors the driver’s eye status and triggers an alarm if drowsiness is detected.
# Driver Drowsiness Detection System

This repository contains the code for a Driver Drowsiness Detection System that utilizes OpenCV and a Convolutional Neural Network (CNN) to monitor driver eye status and alert them if drowsiness is detected.

**Features:**

* **Real-time eye status monitoring:** Continuously analyzes video frames from a webcam.
* **Face and eye detection:** Utilizes Haar Cascade Classifiers for accurate face and eye detection.
* **CNN-based eye classification:** Classifies eye images as open or closed using a trained CNN model.
* **Drowsiness scoring:** Calculates a drowsiness score based on the duration of eye closure.
* **Alarm triggering:** Plays an audible alarm when a high drowsiness score is detected.

