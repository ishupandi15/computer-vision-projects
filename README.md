# 🔥 Fire Detection (Main Project) & 🚗 License Plate Detection (Mini Project)

Undergraduate projects developed using **Python, OpenCV, TensorFlow, and Tesseract OCR**.  
These projects were completed as part of my undergraduate studies — starting with a **mini project on license plate detection**, followed by a **main project on fire and smoke detection with automatic email and SMS alerts**, later **published in IRJET (Volume 9, Issue 4, 2022)**.

---

## 🔥 Fire Detection — Main Project (IRJET Published)

### 📘 Overview
- Developed a **Computer Vision-based Early Fire Detection System** using image processing and machine learning.  
- Detects **fire and smoke** from real-time video feed and sends **instant alerts via email and SMS**.  
- Once fire is detected, an **email notification** is automatically sent to the **respective user** and the **nearest fire department**.  
- The system also **triggers an audible alarm** for immediate local alert.  
- Published in *International Research Journal of Engineering and Technology (IRJET), Volume 9, Issue 4 (2022)*.

### 🧠 Technologies Used
- Python  
- OpenCV  
- NumPy  
- Pygame (for alarm)  
- smtplib (for email alerts)  
- Twilio or equivalent API (for SMS notification)

### ⚙️ Key Features
- Real-time fire and smoke detection using webcam footage.  
- Uses **Haar Cascade Classifier**, **Integral Image**, and **Adaptive Boosting (AdaBoost)** for accurate detection.  
- Analyzes frames using **RGB**, **YCbCr**, and **Lab** color spaces to distinguish fire from light or motion noise.  
- Sends **automatic email alerts** to the user and local fire department.  
- Sends **SMS alerts** for immediate notification.  
- Plays a **sound alarm (alarm.wav)** on detection.  
- Detects both **flame and smoke** patterns for early warning.  
- Reduces false positives using statistical color and motion filtering.  
- Achieved an overall **accuracy of 98.9%** with only **1.1% false detection**.

### 📂 Folder Structure
- **fire_detection/Code/** → main implementation (`Fire detection.py`)  
- **fire_detection/Presentation/** → project presentation slides  
- **fire_detection/Publication/** → IRJET paper (V9I4332.pdf)  
- **fire_detection/report/** → detailed project report and documentation  

### 📸 System Workflow
1. Capture video feed through webcam.  
2. Convert video frames into grayscale and color channels.  
3. Apply Haar features and Integral Image for region detection.  
4. Detect motion, brightness, and fire patterns using thresholds.  
5. Trigger alarm and send notifications (email & SMS) when fire > threshold (dt > 0.3).  
6. Stop alarm when fire is no longer detected.  

---

## 🚗 License Plate Detection — Mini Project

### 📘 Overview
- Designed a **real-time license plate detection system** using machine learning.  
- Detects and recognizes license plates from vehicle images under varying light and weather conditions.  
- Served as the **foundation project** before developing the main fire detection system.

### 🧠 Technologies Used
- Python  
- TensorFlow  
- OpenCV  
- Tesseract OCR

### ⚙️ Key Features
- Detects and extracts license plates from complex vehicle images.  
- Uses **Histogram of Oriented Gradients (HOG)** and **Local Binary Pattern (LBP)** for feature extraction.  
- Employs **Support Vector Machine (SVM)** and **Extreme Learning Machine (ELM)** classifiers for recognition.  
- Works under challenging conditions like low light, rotation, and motion blur.  
- Achieved **99.62% detection accuracy** and **1.675% false positives**.  
- Includes full documentation, abstract, and presentation slides.

### 📂 Folder Structure
- **license_plate_detection/Abstract/** → project abstract (`final ABSTRACT.docx`)  
- **license_plate_detection/Presentation/** → slides (`License plate.pptx`)  
- **license_plate_detection/report/** → project report (`REAL TIME LICENSE PLATE DETECTION USING TENSORFLOW AND TESSERACT.docx`)

---

## 🚀 Completed Features
- ✅ Automatic **fire and smoke detection** using machine learning.  
- ✅ **Sound alarm system** for local alert.  
- ✅ **Email notification** to user and fire department.  
- ✅ **SMS alert system** for immediate warning.  
- ✅ **High-accuracy detection** using multi-color analysis and machine learning.  
- ✅ **License plate recognition** with TensorFlow and Tesseract OCR.

---

## 📜 License
- Licensed under the **MIT License**.  
- Free to use, modify, and distribute with proper attribution.

---

## 🙌 Acknowledgment
Developed as part of undergraduate coursework at **SRM Valliammai Engineering College, Department of Information Technology**,  
under the supervision and guidance of faculty mentors.  
The **Fire Detection System** with **automatic email and SMS alerting** was later **published in IRJET (Volume 9, Issue 4, 2022)**.  
Both projects were created to gain hands-on experience in **Computer Vision**, **Machine Learning**, and **Image Processing**.
