# **EmotionalTuneDL**


# 📌 Overview
This project detects human emotions from facial images using a Convolutional Neural Network (CNN) and recommends music based on the detected emotions. Implemented with Python, TensorFlow, Keras, and OpenCV, it runs on Google Colab.

# 📂 Dataset
✅ Training Data – Facial images categorized into seven emotions (Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise).
✅ Testing Data – Similar dataset used for model evaluation.


# Images are preprocessed and normalized for better performance.

📌 Model Architecture
✔ 4 Convolutional Layers with ReLU activation
✔ Batch Normalization & MaxPooling
✔ Dropout Layers to prevent overfitting
✔ Dense Layers with Softmax Activation* for multi-class classification

# The model classifies images into 7 emotion categories.

## 📊 Training & Evaluation
✅ Categorical Crossentropy Loss
✅ Adam Optimizer
✅ Data Augmentation
✅ Early Stopping to prevent overfitting

## 🚀 Technologies Used
✔ Python
✔ TensorFlow / Keras
✔ OpenCV
✔ NumPy & Pandas
✔ Matplotlib
