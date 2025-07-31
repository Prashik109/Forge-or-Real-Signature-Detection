# 🖋️ Real-Forge Signature Detection using Deep Learning

> A Convolutional Neural Network (CNN)-based system to detect **genuine** and **forged** handwritten signatures. Built using Python, TensorFlow, and Keras, this project aims to provide reliable signature verification for document authentication systems in legal, financial, and governmental sectors.

---

## 📌 1. Introduction

**Signature verification** and **forgery detection** involve the automatic analysis of a handwritten signature to determine whether it is real (genuine) or fake (forged). There are two primary methods:

- **Offline (Static)**: Verification of signatures captured on paper, later scanned or photographed.
- **Online (Dynamic)**: Verification based on the motion of signing on a digital tablet or device.

This project focuses on **offline verification**, where scanned images of handwritten signatures are analyzed using deep learning techniques.

---

## 🎯 2. Importance of Signature Verification

- Handwritten signatures are a widely accepted form of identity verification.
- Detecting forged signatures helps prevent document falsification in **banking**, **legal**, and **commercial** systems.
- This project compares different CNN-based deep learning models and proposes a lightweight yet effective classifier for this task.

---

## 📂 3. Dataset

The dataset used in this project is not publicly distributed. You may:
- Request access by emailing the original publisher.
- Use alternative datasets available on [Kaggle](https://kaggle.com) for experimentation and benchmarking.

---

## 🧠 4. Methodology

- Signatures are considered **behavioral biometrics** and are not purely physiological.
- Natural variations in signatures over time can increase false rejection rates.
- CNNs are used to model signature patterns and generalize across these variations.

---

## ⚙️ 5. Model Training

- Implemented using **Convolutional Neural Networks (CNN)** in **Keras** with **TensorFlow** backend.
- The model is trained on labeled signature images (real and forged).
- Achieved **95.5% accuracy** on the validation set after 10 epochs.

---

## 💻 6. Implementation Details

- Dataset structured in image directories compatible with Keras `ImageDataGenerator`.
- Preprocessing includes resizing, normalization, and augmentation.
- Model trained and evaluated in a Jupyter Notebook (`training.ipynb`) and executable Python scripts (`main.py`).

---


---

## 📊 8. Results

- **Validation Accuracy**: 95.5% after 10 training epochs.
- The system shows excellent classification capability between real and forged signatures.
- Future work can involve tuning the fully connected layers and improving generalization to new users.

---



## 💡 10. Motivation

This project provides a deployable signature verification system that:

- Can be used in **government offices**, **banks**, or **corporate approvals**.
- Helps prevent identity fraud using deep learning.
- Serves as a foundation for extending to **multilingual** or **stylized** signatures.

---

