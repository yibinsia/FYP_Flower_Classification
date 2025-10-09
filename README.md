**Smart Garden: AI-Enhanced Flower Classification Mobile App**

A **lightweight mobile application** that classifies **102 flower species** using a **custom Convolutional Neural Network (CNN)** built and trained entirely from scratch. The goal was to design an efficient, high-performing deep learning model that works well on real-world images while remaining compact for mobile deployment.

The model is composed of **four convolutional blocks** with Batch Normalization, ReLU activation, max pooling, and dropout for regularization. It employs dual adaptive pooling (average and max) to capture both global context and local discriminative features. To enhance generalization and reduce overfitting, **Mixup** and **CutMix augmentation** techniques were used during training.

The final model achieved **94.2% test accuracy** and **91.18% validation accuracy** with a total size of **22.2 MB**. It was exported via TorchScript and integrated into an Android Studio application, enabling real-time flower recognition through image capture or upload.

This repository includes the **model architecture**, **training pipeline**, and **mobile app integration components**.
