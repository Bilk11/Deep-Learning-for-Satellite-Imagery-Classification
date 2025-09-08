#Deep Learning for Satellite Image Classification (xView Benchmark)
This project explores various deep learning approaches for object classification in high-resolution satellite imagery using the xView recognition benchmark. The goal is to evaluate the performance of different neural network architectures—from feedforward networks (ffNNs) to convolutional neural networks (CNNs) and transfer learning with ResNet50—on a challenging dataset with 12 classes and significant class imbalance.
Key Experiments & Results:

Feedforward Neural Networks (ffNNs): Baseline models with and without regularization, achieving up to 55.18% accuracy.
Convolutional Neural Networks (CNNs): Custom architecture with data augmentation and batch normalization, reaching 76.36% accuracy.
Transfer Learning (ResNet50): Two-phase training strategy (feature extraction + fine-tuning) for the best performance at 77.87% accuracy.

Challenges Addressed:

Small object recognition in satellite imagery.
Class imbalance and noisy labels.
Overfitting and generalization.

Technologies Used:

Python, TensorFlow/Keras, OpenCV.
Data augmentation, batch normalization, dropout, and custom learning rate scheduling.

Future Work:

Ensemble methods and advanced architectures (e.g., Vision Transformers).
Class weighting and specialized loss functions for imbalance mitigation.

Collaborators: Joseph Tartivel, Ádám Földvári, Máté Lukács
Institution: Universidad Politécnica de Madrid (UPM)
Course: Deep Learning (2025)
