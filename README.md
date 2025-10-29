# 🖊️ Automated Signature Authentication Using Deep Convolutional Neural Network

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-2.x-red)](https://keras.io/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🚀 Project Overview
This project implements an **offline handwritten signature verification system** using **deep learning**.  
It leverages **MobileNetV2** with **transfer learning** to accurately distinguish between genuine and forged signatures.  

**Key Highlights:**
- Lightweight and efficient deep feature extraction
- Personalized classification head for verification
- Robust performance with high accuracy and reliability

---

## 🛠️ Features
- ✅ Detects genuine vs. forged signatures  
- ✅ Uses **MobileNetV2** for feature extraction  
- ✅ Integrates **transfer learning** for improved accuracy  
- ✅ Performance visualization with accuracy/loss graphs and confusion matrix

---

## 🧰 Tech Stack
- **Programming Language:** Python  
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy, Matplotlib  
- **Platform:** Google Colab  

---

## 📂 Dataset
- Offline handwritten signature dataset  
- Contains **genuine** and **forged** signatures  
- Stored in **Google Drive** for training and evaluation

---

## 📊 Results
- **Test Accuracy:** 96.46%  
- Clear separation of genuine vs. forged signatures  
- Confusion matrix, accuracy, and loss graphs generated for validation  

---

## ⚙️ Methodology
1. Preprocess signature images (resize, normalize, augmentation).  
2. Use **MobileNetV2** as feature extractor.  
3. Add classification head for personal verification.  
4. Train with transfer learning on labeled dataset.  
5. Evaluate on held-out test set.  
6. Generate performance graphs (accuracy/loss, confusion matrix).  

---

## 🏃 How to Run
1. Open the notebook in **Google Colab**.  
2. Mount your **Google Drive** containing the dataset.  
3. Run the notebook sequentially for preprocessing, training, and evaluation.  
4. Check generated graphs for model performance visualization.

---

## 🔮 Future Scope
- Ensemble models or fine-tuning for improved accuracy  
- Deployment as a **web-based signature verification system**  
- Multi-modal biometric verification integration

---

## 📚 References
1. Deep Learning Based Handwritten Signature Recognition, ResearchGate  
2. Offline Signature Verification using Deep Learning, IJETT  
3. MobileNetV2: Inverted Residuals and Linear Bottlenecks, Google Research  

---

## ⚖️ License
This project is released under the **MIT License**.
