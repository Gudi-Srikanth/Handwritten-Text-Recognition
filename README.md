# ✍️ Handwritten Text Recognition in Noisy Environments

This repository hosts the research paper titled **"Analysis of Image-based Handwriting System in Noisy Environments"**, co-authored by Gudi Srikanth and team. The study explores the use of deep learning models (CNN + RNN + CTC) for handwritten text recognition (HTR), particularly under noisy conditions, using the IAM Words dataset.

---

## 📌 Abstract

Handwritten Text Recognition (HTR) is essential for applications such as document digitization, historical record preservation, and intelligent OCR systems. This study presents a deep learning-based approach to recognizing handwritten words using CNNs and RNNs, enhanced with Connectionist Temporal Classification (CTC) for sequence modeling. We specifically explore the model’s performance in both clean and noisy environments.

> 📝 Authors: Bittu Kumar, Gudi Srikanth, Bommidi Sathvik, Kotha Ajay Kumar Rao, Kurma Srujan  
> 🎓 Department of Electronics and Communication Engineering  
> 📍 KL University, Hyderabad  
> 📄 [Download Full Paper](./Modified_HTR.pdf)

---

## 🧠 Key Concepts

- **Dataset**: IAM Words Dataset
- **Techniques Used**:
  - CNNs for feature extraction
  - RNNs (LSTM) for sequence modeling
  - CTC loss for alignment-free sequence training
- **Evaluation**: Model tested across varying dataset sizes and multiple noise types (Gaussian, Salt & Pepper, Speckle, etc.)

---

## 📊 Results Snapshot

| Dataset Size | Accuracy |
|--------------|----------|
| 10% (8K images) | 56.2% |
| 50% (43K images) | 63.9% |
| 100% (86K images) | 70.6% |

- Model struggles with unseen words and noisy samples.
- Performs best with full dataset and clean input images.

---

## 🔍 Noise Evaluation Examples

- Tested the same word ("Position") under:
  - No noise ✅ (accurate result)
  - Gaussian, Salt & Pepper, Speckle, Poison noise ❌ (reduced accuracy)

---
