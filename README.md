# 🩺 ISIC 9-Class Skin Cancer Classification using Deep Learning

> CNN-based Skin Cancer Classification with Large-Scale Data Augmentation and Hyperparameter Optimization, achieving **90.01% Accuracy**.

## 📌 Project Overview

Skin cancer is one of the most common forms of cancer worldwide, and early diagnosis plays a critical role in successful treatment. This project focuses on building a robust **Deep Learning-based Skin Cancer Classification System** capable of classifying dermoscopic images into **9 different skin disease categories**.

The project leverages **Convolutional Neural Networks (CNNs)**, extensive **data augmentation**, and systematic **hyperparameter tuning** to achieve high classification performance.

---

## 🚀 Key Achievements

### 📈 Dataset Expansion

The original dataset contained only **2,357 images**, which was insufficient for training a highly generalized deep learning model.

Using TensorFlow and Keras image augmentation techniques, the dataset was expanded to:

✅ Original Dataset: **2,357 Images**

✅ Augmented Dataset: **32,000+ Images**

Augmentation techniques used:

* Rotation
* Horizontal Flip
* Vertical Flip
* Zoom
* Width & Height Shift
* Brightness Adjustment

This significantly improved model generalization and reduced overfitting.

---

### ⚙️ Hyperparameter Optimization

Instead of using a default CNN architecture, extensive experiments were conducted to identify the optimal model configuration.

The following parameters were tuned:

* Number of CNN Layers
* Number of Filters
* Dense Layer Units
* Dropout Rate
* Learning Rate
* Batch Size
* L2 Regularization
* Optimizer Configuration

Multiple model variations were evaluated to find the best-performing architecture.

---

## 🎯 Results

| Metric           | Value      |
| ---------------- | ---------- |
| Dataset Classes  | 9          |
| Original Images  | 2,357      |
| Augmented Images | 32,000+    |
| Model Type       | Custom CNN |
| Final Accuracy   | **90.01%** |

### 🏆 Performance Highlights

* Achieved **90.01% classification accuracy**
* Successfully classified images across **9 skin cancer categories**
* Demonstrated the effectiveness of large-scale data augmentation
* Improved model performance through systematic hyperparameter tuning

---

## 🛠️ Tech Stack

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## 📂 Project Structure

```text
├── dataset/
├── notebooks/
├── models/
├── training/
├── evaluation/
├── saved_model/
├── requirements.txt
└── README.md
```

---

## 🔄 Project Workflow

### 1️⃣ Data Collection

* ISIC Skin Cancer Dataset

### 2️⃣ Data Preprocessing

* Image resizing
* Label encoding
* Train-test split

### 3️⃣ Data Augmentation

* Generated 32K+ training samples

### 4️⃣ CNN Model Development

* Custom Convolutional Neural Network

### 5️⃣ Hyperparameter Tuning

* Architecture optimization
* Regularization tuning
* Learning rate optimization

### 6️⃣ Model Training

* Multiple experiments
* Best model selection

### 7️⃣ Evaluation

* Accuracy analysis
* Performance comparison

---

## 💡 Why This Project Matters

Medical image classification is a challenging real-world application of Artificial Intelligence. This project demonstrates how careful data engineering and model optimization can significantly improve predictive performance, even when starting with a relatively small dataset.

The techniques used in this project are directly applicable to:

* Medical AI
* Computer Vision
* Healthcare Analytics
* Deep Learning Research
* Image Classification Systems

---

## 🔮 Future Improvements

* Transfer Learning using EfficientNet
* ResNet-based Classification
* Grad-CAM Visualization
* Web Application Deployment
* Mobile-Friendly Inference System
* External Dataset Validation

---

## 🤝 Connect With Me

If you found this project useful, feel free to ⭐ star the repository and connect with me.

### ⭐ Don't forget to Star this Repository if you like the project!
