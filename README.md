![Project Cover](cover.jpg)

<p align="center"><b>Undergraduate Computer Vision Projects</b></p>

# 🔥 Fire Detection (Main Project) & 🚗 License Plate Detection (Mini Project)

Undergraduate projects developed by  
**Ishwariya P**, **Lakshmi Prabha R**, **Mythireyeni P V**, and **Neelaveni M**  
**Department of Information Technology**  
**SRM Valliammai Engineering College (Autonomous)**  
Affiliated to **Anna University, Chennai – 603203**  
📅 *March 2022*

---

## 🔗 GitHub Repository Links
- 🔥 **Fire Detection (Main Project):** [github.com/ishupandi15/computer-vision-projects/tree/main/fire_detection](https://github.com/ishupandi15/computer-vision-projects/tree/main/fire_detection)  
- 🚗 **License Plate Detection (Mini Project):** [github.com/ishupandi15/computer-vision-projects/tree/main/license_plate_detection](https://github.com/ishupandi15/computer-vision-projects/tree/main/license_plate_detection)

---

## 🔥 Fire Detection — Main Project (IRJET Published)

### 📘 Overview
- A **Computer Vision-based Early Fire Detection System** built using image processing and machine learning.  
- Detects **fire and smoke** in real time through webcam video feed.  
- Sends **automatic email alerts** to both the **respective user** and the **nearest fire department**.  
- Also triggers a **sound alarm** and **SMS notification** for quick action.  
- Published in *International Research Journal of Engineering and Technology (IRJET)*, Volume 9, Issue 4 (2022).  

### 🧠 Technologies Used
- Python  
- OpenCV  
- NumPy  
- Pygame (for alarm sound)  
- smtplib (for email alerts)  
- Twilio / equivalent API (for SMS notifications)

### ⚙️ Key Features
- Real-time **fire and smoke detection** using webcam video.  
- Combines **Haar Cascade Classifier**, **Integral Image**, and **Adaptive Boosting (AdaBoost)** for enhanced accuracy.  
- Works across **RGB**, **YCbCr**, and **Lab** color models.  
- Plays a **sound alarm** (`alarm.wav`) when fire or smoke is detected.  
- Sends **automatic email alerts** to the user and fire department.  
- Sends **SMS notifications** for emergency response.  
- Detects **smoke and early heat patterns** before visible flames.  
- Achieved **98.9% accuracy** with only **1.1% false detection rate**.  

### 🖥️ Workflow
1. Capture live video through webcam.  
2. Convert frames to grayscale and color channels.  
3. Apply Haar and integral image techniques for detection.  
4. Use AdaBoost classification for accuracy improvement.  
5. When fire is detected:
   - Trigger audible alarm  
   - Send **email alert** to user and fire department  
   - Send **SMS alert** to registered contacts  
6. Continue real-time monitoring until terminated manually.

### 📂 Folder Details
- **fire_detection/Code/** → `Fire detection.py` (main program)  
- **fire_detection/Presentation/** → project presentation slides  
- **fire_detection/Publication/** → IRJET paper (V9I4332.pdf)  
- **fire_detection/report/** → final project report and documentation  

---

## 🚗 License Plate Detection — Mini Project

### 📘 Overview
- A **mini project** built to detect and recognize vehicle license plates using machine learning and OCR.  
- Implemented as a precursor to the main Fire Detection system.  
- Works across challenging environments — glare, motion blur, and low light.

### 🧠 Technologies Used
- Python  
- TensorFlow  
- OpenCV  
- Tesseract OCR

### ⚙️ Key Features
- Detects and isolates vehicle license plates from images and video.  
- Recognizes text via **Tesseract OCR**.  
- Uses **Histogram of Oriented Gradients (HOG)** and **Local Binary Pattern (LBP)** for feature extraction.  
- Employs **Support Vector Machine (SVM)** and **Extreme Learning Machine (ELM)** classifiers for classification.  
- Works under various lighting and rotational conditions.  
- Achieved **99.62% detection rate** and **1.675% false positives**.  

### 📂 Folder Details
- **license_plate_detection/Abstract/** → project abstract  
- **license_plate_detection/Presentation/** → project slides (`License plate.pptx`)  
- **license_plate_detection/report/** → full report (`REAL TIME LICENSE PLATE DETECTION USING TENSORFLOW AND TESSERACT.docx`)  

---

## 🚀 Completed Features
- ✅ Real-time **fire and smoke detection**  
- ✅ **Email alerts** to user and fire department  
- ✅ **SMS notifications** for emergency response  
- ✅ **Sound alarm** for local warnings  
- ✅ **Smoke and heat detection** for early alert  
- ✅ **License plate detection and recognition** using OCR  
- ✅ **High accuracy and minimal false positives**

---

## 🏆 Results & Highlights
- Fire Detection Accuracy: **98.9%**  
- License Plate Detection Accuracy: **99.62%**  
- False Detection Rate: **~1%**  
- Published in **IRJET, April 2022 (Vol. 9, Issue 4)**  

---

## 📜 License
This repository is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project with proper attribution.

---

## 🏫 Acknowledgment
Developed as part of undergraduate coursework at  
**SRM Valliammai Engineering College**, Department of Information Technology,  
under the guidance of **Dr. A. R. Revathi**, Associate Professor.  

The **Fire Detection System**, featuring **email, SMS, and alarm alerting**,  
was **published in IRJET (Volume 9, Issue 4, 2022)** as part of academic research.

---

## 📚 Citation

If you reference this work, please cite our publication:

**IEEE Format:**
> I. P., R. L. Prabha, P. V. Mythireyeni, and M. Neelaveni,  
> "Computer Vision-Based Early Fire Detection Using Machine Learning,"  
> *International Research Journal of Engineering and Technology (IRJET)*,  
> vol. 9, no. 4, pp. 332–336, Apr. 2022.

**APA Format:**
> Ishwariya, P., Lakshmi Prabha, R., Mythireyeni, P. V., & Neelaveni, M. (2022).  
> *Computer Vision-Based Early Fire Detection Using Machine Learning*.  
> International Research Journal of Engineering and Technology (IRJET), 9(4), 332–336.

---

📧 *For queries or collaborations:* [ishupandi15@gmail.com](mailto:ishupandi15@gmail.com)
