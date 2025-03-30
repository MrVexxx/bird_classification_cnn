# Endangered Bird Species Classification (Nepal)

This project uses deep learning (CNN with ResNet50) to classify five endangered bird species native to Nepal using image data. It includes robustness testing via corrupted inputs and explores traditional classifiers (SVM) and Few-Shot Learning (Prototypical Networks) for comparison.

## 🔍 Features
- Image classification with transfer learning (ResNet50)
- Data augmentation and class balancing
- Evaluation on clean and corrupted datasets
- Grad-CAM visualizations for model explainability
- Alternative evaluation using SVM and Prototypical Networks
- Real-world prediction visualization

## 📁 Dataset
The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/sandipshresthad/endangered-bird-species-of-nepal) and includes:
- Train / Validation / Test splits
- 5 endangered species

## 🛠 Requirements
- Python 3.9+
- TensorFlow 2.x, Keras, OpenCV, scikit-learn, Matplotlib, Seaborn

