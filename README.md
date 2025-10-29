# 🖊️ Automated Signature Authentication Using Deep Convolutional Neural Network

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-2.x-red)](https://keras.io/)
[![License: CC0 1.0](https://img.shields.io/badge/License-CC0_1.0-green.svg)](LICENSE)

---

## 🚀 Project Overview
This project implements an **offline handwritten signature verification system** using **deep convolutional neural networks (CNNs)**.  
It leverages **MobileNetV2** with **transfer learning** to accurately distinguish between **genuine** and **forged** handwritten signatures.

**Key Highlights:**
- Lightweight and efficient deep feature extraction  
- Personalized classification head for verification  
- Robust performance with high accuracy and generalization capability  

---

## 🛠️ Features
- ✅ Classifies signatures as *genuine* or *forged*  
- ✅ Employs **MobileNetV2** for deep feature extraction  
- ✅ Utilizes **transfer learning** for enhanced precision  
- ✅ Visualizes model performance through graphs and confusion matrix  

---

## 🧰 Tech Stack
- **Language:** Python  
- **Frameworks:** TensorFlow, Keras  
- **Libraries:** OpenCV, NumPy, Matplotlib  
- **Platform:** Google Colab  

---

## 📂 Dataset
- The dataset used for this project is included under the `dataset/` directory.  
- It contains **real and forged signature samples** used for training, validation, and testing.  
- The dataset and source code are archived on **Zenodo** for reproducibility.  

🔗 **DOI (to be updated after Zenodo publication):** [https://doi.org/10.5281/zenodo.17475131]

---

## 📊 Results
- **Test Accuracy:** 96.46%  
- Clear distinction between genuine and forged samples  
- Evaluation metrics include **accuracy**, **loss**, and **confusion matrix**

---

## ⚙️ Methodology
1. **Data Preprocessing** – Resize, normalize, and augment signature images.  
2. **Feature Extraction** – Use MobileNetV2 as a pretrained CNN backbone.  
3. **Classification Head** – Add dense layers for binary classification.  
4. **Training** – Fine-tune the model using transfer learning.  
5. **Evaluation** – Measure performance using validation and test sets.  
6. **Visualization** – Generate accuracy/loss curves and confusion matrix.  

---

## 🏃 How to Run
1. Open the notebook in **Google Colab**.  
2. Mount your **Google Drive** or load the included dataset.  
3. Execute all cells sequentially to train and test the model.  
4. View results including graphs and predictions.  

---

## 🔮 Future Scope
- Incorporate **ensemble models** for higher accuracy.  
- Deploy as a **web-based verification platform**.  
- Extend framework to **multi-modal biometric systems**.  

---

## 📚 References
1. *Deep Learning Based Handwritten Signature Recognition*, ResearchGate.  
2. *Offline Signature Verification using Deep Learning*, IJETT.  
3. *MobileNetV2: Inverted Residuals and Linear Bottlenecks*, Google Research.  

---

## ⚖️ License
This project is licensed under the **Creative Commons CC0 1.0 Universal (Public Domain Dedication)** license.  
See the [LICENSE](LICENSE) file for more information.
