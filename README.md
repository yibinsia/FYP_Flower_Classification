This project focuses on developing a lightweight mobile application capable of classifying 102 flower species using a custom-built Convolutional Neural Network (CNN) trained entirely from scratch. The objective was to create an efficient, accurate, and deployable model suitable for mobile environments, without relying on large pretrained architectures.

Key components of the system include:
• A four-block CNN architecture incorporating convolutional layers, Batch Normalization, ReLU activation, max pooling, and dropout regularization to balance learning and prevent overfitting.
• A dual pooling layer combining Adaptive Average Pooling and Adaptive Max Pooling, allowing the model to capture both broad contextual and fine-grained discriminative features from flower images.
• Advanced data augmentation strategies, including Mixup and CutMix, applied to improve generalization and prevent the model from memorizing specific patterns from the training data.

The final model achieved 94.2% testing accuracy and 91.18% validation accuracy, with a compact model size of only 22.2 MB—making it suitable for mobile deployment. The model was exported using TorchScript and integrated into an Android Studio–based mobile application that allows users to capture or upload flower images for instant classification.

This project demonstrates the potential of custom deep learning architectures to achieve high performance in specialized domains while maintaining efficiency for real-world applications.
