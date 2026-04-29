💵 Fake Currency Detection System
📌 Overview

The Fake Currency Detection System is a deep learning-based application designed to classify currency notes as real or fake using image processing techniques. This project leverages a pretrained convolutional neural network model to extract features and perform accurate binary classification.

The goal of this project is to assist in detecting counterfeit currency efficiently and reduce manual verification efforts.

🚀 Features
Image-based currency classification (Real vs Fake)
Uses transfer learning for better accuracy
Automated training and validation pipeline
Performance evaluation using accuracy and classification metrics
Scalable model for real-world applications
🛠️ Technologies Used
Python
TensorFlow / Keras
MobileNetV2 (Pretrained Model)
NumPy
Matplotlib
Scikit-learn
🧠 Model Architecture

The project uses MobileNetV2, a lightweight deep learning model, as the base model. Transfer learning is applied by freezing initial layers and adding custom classification layers on top.

Base Model: MobileNetV2
Loss Function: Binary Crossentropy
Optimizer: Adam
Evaluation Metric: Accuracy
📂 Dataset

The dataset consists of labeled images of currency notes categorized into:

Real Currency
Fake Currency

Images are preprocessed and augmented to improve model generalization.
