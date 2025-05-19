# 🛡️ AuralGuard  
**Intelligent Acoustic Threat Detection Using Deep Learning and Classical Machine Learning**

---

## 🔍 Overview
**AuralGuard** is an AI-powered sound classification system that detects suspicious environmental sounds — such as glass breaking, chainsaws, and door knocks — to support modern surveillance and public safety solutions. Built using the ESC-50 dataset, it compares traditional machine learning and deep learning models to find the most effective approach for acoustic-based threat detection.

---

## 🎯 Objectives
- Detect and classify abnormal or hazardous environmental sounds
- Evaluate and compare multiple machine learning and deep learning models
- Enable future integration into smart city and real-time monitoring systems

---

## 📁 Dataset
- **ESC-50**: Environmental Sound Classification dataset by Karol J. Piczak  
- Total: 2,000 labeled audio clips from 50 categories  
- **Classes used in this project**:
  - `glass_breaking`
  - `chainsaw`
  - `door_wood_knock`  
- Dataset Source: [ESC-50 GitHub](https://github.com/karoldvl/ESC-50)

---

## 🧪 Feature Extraction
- Root Mean Square Energy (RMS)
- Zero Crossing Rate (ZCR)
- Spectral Centroid
- Spectral Bandwidth
- Mel-Spectrograms (for deep learning)

---

## 🤖 Models Implemented

### Classical Machine Learning
- ✅ Random Forest  
- ✅ Decision Tree  
- ✅ K-Nearest Neighbors (KNN)  

### Deep Learning Models
- ✅ Convolutional Neural Network (CNN)  
- ✅ Gated Recurrent Unit (GRU)  
- ✅ Bidirectional GRU (BiGRU)

---

## 🔄 Data Augmentation Techniques
- Pitch Shifting (±2 semitones)
- Time Stretching (±10% speed)
- Spectrogram Normalization

---

## 📊 Model Accuracy Comparison

| Model                  | Accuracy (%) |
|------------------------|--------------|
| ✅ CNN (Deep Learning)       | **98.33%**  
| Bidirectional GRU           | 96.67%  
| Random Forest               | 87.50%  
| Decision Tree               | 87.50%  
| SVM                         | 87.50%  
| K-Nearest Neighbors (KNN)   | 68.75%  

> ✅ **CNN achieved the highest accuracy**, making it the best candidate for real-time deployment in acoustic surveillance systems.

---

## 📈 Visualizations
- Confusion Matrices per Model
- Accuracy and Loss Curves (CNN, GRU, BiGRU)
- Horizontal Bar Chart: Model Accuracy Comparison

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/auralguard
cd auralguard
pip install -r requirements.txt
