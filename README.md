# Power_System_Fault_Detection
Designed a machine learning model to detect and classify different types of faults in a power distribution system. This project implements various machine learning techniques for the detection and classification of faults in power systems. It focuses on improving the speed and accuracy of fault detection to enhance grid reliability and support preventive maintenance.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Problem Statement](#problem-statement)
- [Approach](#approach)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)

---

## 🔍 About the Project

Electrical power systems are vulnerable to a variety of faults (e.g., overheating, line breakage). Fast and accurate fault detection is essential to avoid widespread outages and ensure system stability.

This project explores the application of supervised machine learning algorithms to classify different types of faults.

---

## ⚠️ Problem Statement

Traditional methods of fault detection rely heavily on manual inspection and threshold-based logic, which are slow and less adaptive. The objective of this project is:

> **To build a machine learning-based fault detection model that can classify fault types with high accuracy based on sensor data from power transmission lines.**

---

## 🧠 Approach

1. **Data Preprocessing**: Cleaning and normalization of voltage and current signal data.
2. **Feature Engineering**: Time-domain and frequency-domain features extraction (e.g., RMS, FFT, DWT).
3. **Model Training**: Multiple ML models were trained:
   - Decision Trees
   - Random Forest
   - Support Vector Machine (SVM)
4. **Evaluation**: Cross-validation and confusion matrix analysis.

---

## 🛠 Technologies Used

- IBM Cloud watsonx.ai 
- Python 3.9+
- NumPy, Pandas
- Scikit-learn
- Jupyter Notebooks

---

## 📂 Dataset

The dataset includes labeled fault and non-fault signal data derived from simulation tools or real-time system logs.

> 📎 *Kaggle dataset link – https://www.kaggle.com/datasets/ziya07/power-systemfaults-dataset*

Each sample contains:
- Voltage and current waveform segments, weather condition, location
- Fault label (e.g. : fault type)

---

