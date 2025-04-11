# Thesis2024/ Licenta2024
# Emotion Detection via Transfer Learning

This repository presents my Bachelor's thesis project, focused on exploring the effectiveness of **Transfer Learning techniques in facial emotion detection**. The project was developed as part of my studies at the Faculty of Computer Science, Alexandru Ioan Cuza University of Iași.

## 🎯 Project Objective

To evaluate and compare multiple approaches for facial emotion recognition, with a particular emphasis on **Transfer Learning** using pre-trained deep learning models.

## 📚 Summary

Facial emotion detection is a challenging task due to the complexity of expressions, environmental variability, and ethical concerns. This project provides:

- A **theoretical and statistical analysis** of emotion recognition research.
- A review of **traditional Machine Learning approaches** and their limitations on small datasets.
- A deep dive into **Convolutional Neural Networks (CNNs)** trained from scratch.
- An extensive evaluation of **Transfer Learning** using pre-trained models like `ResNet50V2`, `VGG16`, `DenseNet201`, and `MobileNetV2`.

## 🧪 Models & Methods

### 1. CNN-Based Models
- Built and tested 8 custom CNN architectures.
- Monitored training performance via loss/accuracy curves and confusion matrices.
- Identified limitations in generalization and prediction confidence.

### 2. Transfer Learning with Pre-trained Models
- Applied `ResNet50V2` with multiple configurations.
- Best test accuracy achieved: **67.80%**
- Explored overfitting vs. underfitting trade-offs in 8 model versions.

### 3. Hybrid Approaches
- Integrated features from pre-trained models with traditional ML algorithms:
  - `Random Forest`
  - `KNN`
  - `XGBoost`
- Tested 12 hybrid approaches to optimize performance.
- Best results achieved through DenseNet+RandomForest combinations.

## 🗂 Dataset

- **FER2013** dataset: 7 emotion classes (Happy, Sad, Angry, Surprised, Fearful, Disgust, Neutral).
- Training set: 28,709 images
- Test set: 3,589 images

## 🧠 Key Learnings

- Transfer learning significantly improves accuracy on limited data.
- Hybrid methods combining deep features and traditional classifiers yield competitive results.
- Detecting subtle emotions like sadness and fear remains challenging.
- Ethical and data quality considerations are critical in emotion-based AI.

## 📌 Technologies

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Matplotlib / Seaborn

## 👩‍🎓 Author

**Mara-Georgiana Enache**  
Faculty of Computer Science, University of Iași  
July 2024

---

📫 Contact: maraenache1331@gmail.com  
🔗 LinkedIn: [linkedin.com/in/mara-enache](https://linkedin.com/in/mara-enache)


