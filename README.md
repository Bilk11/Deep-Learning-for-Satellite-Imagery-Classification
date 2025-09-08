# Deep Learning for Satellite Image Classification (xView Benchmark)

This project explores deep learning approaches for object classification in high-resolution satellite imagery using the **xView recognition benchmark**. The goal is to evaluate the performance of feedforward neural networks (ffNNs), convolutional neural networks (CNNs), and transfer learning with **ResNet50** on a dataset with 12 classes and significant class imbalance.

---

## 📊 Key Experiments & Results
| Model               | Accuracy  |
|---------------------|-----------|
| Feedforward (ffNN)  | 55.18%    |
| Custom CNN          | 76.36%    |
| Transfer Learning (ResNet50) | **77.87%** |

---

## 🔍 Challenges Addressed
- Small object recognition
- Class imbalance and noisy labels
- Overfitting and generalization

---

## 🛠 Technologies Used
- **Languages/Libraries:** Python, TensorFlow/Keras, OpenCV
- **Techniques:** Data augmentation, batch normalization, dropout, custom learning rate scheduling

---

## 🚀 Future Work
- Ensemble methods
- Vision Transformers
- Class weighting for imbalance mitigation

---
**Collaborators:** [Joseph Tartivel](https://github.com/yourusername), Ádám Földvári, Máté Lukács
**Institution:** Universidad Politécnica de Madrid (UPM)
**Course:** Deep Learning (2025)
