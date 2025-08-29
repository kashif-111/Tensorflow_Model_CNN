CIFAR-10 Image Classification using TensorFlow CNN
📌 Project Overview

This project applies Machine Learning (ML) and Deep Learning (DL) techniques to the CIFAR-10 dataset (60,000 color images across 10 classes).
We implement:

Classical ML baseline (Logistic Regression)

Deep Learning approach with Convolutional Neural Networks (CNNs) in TensorFlow

Data visualization, preprocessing, augmentation, and analysis

📊 Dataset

CIFAR-10: 60,000 images (32×32 pixels, RGB)

Training set: 50,000 images

Test set: 10,000 images

Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

⚙️ Project Steps

Load & Explore Dataset

Shapes of train/test sets

Class distribution & mapping labels to names

Data Visualization

Display sample images with labels

Histogram of class frequencies

OpenCV: grayscale, edge detection, rotation, flipping

Preprocessing

Normalize pixel values (0–1)

One-hot encode labels

Optional: resize images

Machine Learning Baseline

Logistic Regression (on flattened images)

Accuracy ~30–40%

Deep Learning (CNN in TensorFlow)

CNN with 3 Conv layers, pooling, dropout, dense layers

Accuracy ~70–75%

Advanced Analysis

Misclassified images visualization

Confusion matrix

Data augmentation (rotation, shift, zoom, flip) → Accuracy ~78–80%

🧠 TensorFlow CNN Model Architecture

Conv2D + ReLU → MaxPooling

Conv2D + ReLU → MaxPooling

Conv2D + ReLU

Flatten → Dropout (0.5)

Dense (128, ReLU)

Dense (10, Softmax)

🚀 Results

Logistic Regression (ML baseline): ~35% accuracy

CNN (Deep Learning): ~75% accuracy

CNN + Data Augmentation: ~80% accuracy

📂 Deliverables

Google Colab Notebook: Full code with visualizations, ML, CNN, and augmentation

Report (PDF/Docx): Summary of dataset, methods, results, and key findings

README.md (this file)

🔑 Key Findings

ML models struggle with raw image pixels

CNNs significantly outperform ML by learning spatial patterns

Data augmentation improves robustness and reduces overfitting

✍️ Author: [Your Name]
📚 Course: Machine Learning and Deep Learning
