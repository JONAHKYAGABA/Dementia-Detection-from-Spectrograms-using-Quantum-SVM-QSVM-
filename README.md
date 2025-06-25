# 🧠 Dementia Detection from Spectrograms using Quantum SVM (QSVM)

This project applies a hybrid classical-quantum machine learning approach to detect dementia from audio-derived spectrogram images. Classical deep features are extracted using a pre-trained **SqueezeNet**, then reduced via **PCA**, and finally classified using a **Quantum Support Vector Machine (QSVM)** implemented with **Qiskit Machine Learning**.

---

## 🎯 Objective

- Load spectrogram images from CSV metadata.
- Extract features using a deep CNN (SqueezeNet).
- Reduce feature dimensionality using PCA.
- Train a quantum kernel using `TrainableFidelityQuantumKernel`.
- Classify using a quantum-enhanced SVM (QSVC).
- Evaluate model performance and visualize confusion matrix.

---



