# Facial Emotion Recognition
A deep learning project for recognizing facial emotions using Convolutional Neural Networks (CNN) built with TensorFlow and Keras.

---

# Overview
This project implements a CNN-based model to classify facial expressions into different emotion categories. The model uses data augmentation and a sequential architecture to achieve robust emotion recognition from facial images.

---

# Features
Image preprocessing with rescaling and normalization
Data augmentation (horizontal flip, rotation, zoom, contrast adjustment)
CNN architecture with multiple convolutional and pooling layers
Train/validation/test split for proper model evaluation
Early stopping to prevent overfitting
Model performance visualization and metrics tracking

---

# Project Structure
```
├── Main.ipynb                 
├── processed_data/           
├── models/                 
├── .gitignore                
└── README.md   
```

---

# Requirements
```
bashnumpy
pandas
matplotlib
seaborn
tensorflow
keras
Install dependencies:
bashpip install numpy pandas matplotlib seaborn tensorflow
```

---

# Dataset
The project expects a dataset organized in the following structure:
```
processed_data/
├── emotion_1/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
├── emotion_2/
│   └── ...
└── emotion_n/
    └── ...
````

---

# Clone the repository
```
bash   git clone <"https://github.com/Ydv-Suman/Facial_Emotion_Recognition.git">
   cd facial-emotion-recognition
```