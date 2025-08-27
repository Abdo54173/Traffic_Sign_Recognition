# 🚦 Traffic Sign Recognition using Deep Learning 🚦

## 📝 Project Overview
This project focuses on **classifying traffic signs** using deep learning techniques.  
The goal is to build a model that can accurately recognize traffic signs from images, which can be used in **autonomous driving systems** and **traffic monitoring applications**.

- **📂 Dataset:** [GTSRB - German Traffic Sign Recognition Benchmark](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)
- **🎯 Problem Type:** Multi-class image classification

---

## ⚡ Features
1. **Preprocessing**
   - Resize all images to a uniform size (32x32 for custom CNN, 96x96 or 224x224 for MobileNet)
   - Normalize pixel values (0–1)
   
2. **Data Augmentation**
   - Rotation, width/height shifts, zooming
   - Helps the model generalize better and reduces overfitting

3. **Models**
   - **🛠 Custom CNN:** Built from scratch using Conv2D, MaxPooling, Dense layers
   - **🤖 Pre-trained MobileNetV2:** Used as a feature extractor and fine-tuned on GTSRB dataset

4. **Evaluation**
   - Accuracy on test data
   - Confusion matrix for detailed performance analysis
   - Comparison between custom CNN and MobileNetV2

---

## 🛠 Requirements
- Python 3.x
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib, Seaborn
- OpenCV
- scikit-learn

---

## 🚀 Installation
1. Clone the repository:
```bash
git clone https://github.com/YourUsername/Traffic_Sign_Recognition.git
