A lightweight mobile application that classifies 102 flower species using a custom Convolutional Neural Network (CNN) built and trained from scratch. The focus of this project was to design an efficient deep learning model that performs well on real-world images while remaining small enough for mobile deployment.

The model consists of four convolutional blocks with Batch Normalization, ReLU activation, max pooling, and dropout layers for regularization. It uses both adaptive average and max pooling to extract global and local image features effectively. To improve generalization, Mixup and CutMix data augmentation techniques were applied during training.

The final model reached 94.2% test accuracy and 91.18% validation accuracy with a total size of 22.2 MB. It was exported using TorchScript and integrated into an Android Studio application, allowing real-time flower recognition through photo capture or upload.

This repository includes the model architecture, training pipeline, and Android integration files.
