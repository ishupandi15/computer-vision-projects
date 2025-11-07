# 🔥 Fire Detection (Main Project) & 🚗 License Plate Detection (Mini Project)

Undergraduate projects developed by  
**Ishwariya P**, **Lakshmi Prabha R**, **Mythireyeni P V**, and **Neelaveni M**  
**Department of Information Technology**  
**SRM Valliammai Engineering College (Autonomous)**  
Affiliated to **Anna University, Chennai – 603203**  
📅 *March 2022*

---

## 🔗 GitHub Repository Links
- 🔥 **Fire Detection (Main Project):** [github.com/ishwariyap/fire-detection](https://github.com/ishwariyap/fire-detection)  
- 🚗 **License Plate Detection (Mini Project):** [github.com/ishwariyap/license-plate-detection](https://github.com/ishwariyap/license-plate-detection)

---

## 🔥 Fire Detection — Main Project (IRJET Published)

### 📘 Overview
- Developed a **Computer Vision-based Early Fire Detection System** using image processing and machine learning.  
- Detects **fire and smoke** through a webcam feed and automatically sends **email alerts** to the **respective person** and the **nearest fire department**.  
- Simultaneously triggers a **sound alarm** and **SMS alert** for faster response.  
- Published in *International Research Journal of Engineering and Technology (IRJET)*, Volume 9, Issue 4 (2022).  

### 🧠 Technologies Used
- Python  
- OpenCV  
- NumPy  
- Pygame (for alarm sound)  
- smtplib (for email alerts)  
- Twilio or equivalent API (for SMS notifications)

### ⚙️ Key Features
- Real-time **fire and smoke detection** using webcam video.  
- Uses **Haar Cascade Classifier**, **Integral Image**, and **Adaptive Boosting (AdaBoost)** for enhanced detection accuracy.  
- Works across **RGB**, **YCbCr**, and **Lab** color spaces.  
- Plays an **audible alarm** (`alarm.wav`) when fire or smoke is detected.  
- Sends **email alerts** to the user and local **fire department**.  
- Sends **SMS notifications** for emergency awareness.  
- Detects **smoke and early heat signatures** to minimize fire damage.  
- Achieved **98.9% accuracy** and **1.1% false detection rate** in tests.  

### 🖥️ Workflow
1. Capture live video stream using webcam.  
2. Convert frames into multiple color spaces (RGB, YCbCr, Lab).  
3. Apply Haar-like feature extraction and integral image calculation.  
4. Use AdaBoost classification to detect potential fire regions.  
5. If fire is detected:
   - Trigger audible **alarm**  
   - Send **email** to user and fire department  
   - Send **SMS** notification  
6. Continue monitoring in real time.

### 📂 Folder Details
- **fire_detection/Code/** → `Fire detection.py` (main program)  
- **fire_detection/Presentation/** → project slides  
- **fire_detection/Publication/** → IRJET paper (V9I4332.pdf)  
- **fire_detection/report/** → detailed report and documentation  

---

## 🚗 License Plate Detection — Mini Project

### 📘 Overview
- Initial mini project to detect and recognize vehicle license plates using machine learning.  
- Designed to function under various lighting, motion, and weather conditions.  
- Served as the foundation project before developing the fire detection system.

### 🧠 Technologies Used
- Python  
- TensorFlow  
- OpenCV  
- Tesseract OCR  

### ⚙️ Key Features
- Detects and extracts license plate areas from vehicle images.  
- Performs text recognition using **Tesseract OCR**.  
- Uses **Histogram of Oriented Gradients (HOG)** and **Local Binary Pattern (LBP)** for feature extraction.  
- Employs **Support Vector Machine (SVM)** and **Extreme Learning Machine (ELM)** for classification.  
- Works in low light, rotated, or blurred images.  
- Achieved **99.62% detection rate** with **1.675% false positives**.

### 📂 Folder Details
- **license_plate_detection/Abstract/** → project abstract (`final ABSTRACT.docx`)  
- **license_plate_detection/Presentation/** → slides (`License plate.pptx`)  
- **license_plate_detection/report/** → project report (`REAL TIME LICENSE PLATE DETECTION USING TENSORFLOW AND TESSERACT.docx`)

---

## 🚀 Completed Features
- ✅ Real-time **fire and smoke detection** using computer vision  
- ✅ **Automatic email alerts** to user and fire department  
- ✅ **SMS notifications** for immediate response  
- ✅ **Sound alarm system** for on-site alerting  
- ✅ **Detection of early-stage smoke and heat patterns**  
- ✅ **License plate detection and recognition** using TensorFlow & Tesseract OCR  
- ✅ **High accuracy and minimal false positives**

---

## 📜 License
This repository is licensed under the **MIT License**.  
You are free to use, modify, and distribute this work with proper attribution.

---

## 🏫 Acknowledgment
Developed as part of undergraduate coursework at  
**SRM Valliammai Engineering College**, Department of Information Technology,  
under the guidance of **Dr. A. R. Revathi**, Associate Professor.  

The **Fire Detection System** with **email, SMS, and alarm alerting**  
was **published in IRJET (Volume 9, Issue 4, 2022)** as part of academic research.  

---

## 📚 Citation

If you reference or build upon this work, please cite our published paper:

**IEEE Style:**
> Ishwariya P., Lakshmi Prabha R., Mythireyeni P. V., and Neelaveni M.,  
> "Computer Vision-Based Early Fire Detection Using Machine Learning,"  
> *International*
