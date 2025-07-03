# 🌱 Plant Seedling Species Classification - Computer Vision Project

**Course**: Introduction to Computer Vision  
**Objective**:  
Build a deep learning model using **Convolutional Neural Networks (CNNs)** to accurately classify plant seedlings into one of **12 species** based on leaf image data. This model will assist in automating agricultural identification processes using computer vision techniques.

---

## 🔍 Problem Statement

Identifying plant species at the seedling stage is crucial in modern agriculture. Manual classification is time-consuming and error-prone. The goal of this project is to leverage CNNs to:
- Classify plant seedling images into one of 12 categories
- Improve accuracy of seedling species detection
- Enable real-time and scalable agricultural diagnostics

---

## 🛠️ Skills & Tools Used

- **Python**
- **Keras** (TensorFlow backend)
- **Convolutional Neural Networks (CNNs)**
- **Image Preprocessing** (Resizing, normalization)
- **Image Data Generators**
- **Model Evaluation (Accuracy, Loss, Confusion Matrix)**

---

## 📊 Project Workflow

1. **Data Preparation**
   - Loaded and resized seedling images
   - Used ImageDataGenerator for data augmentation and normalization

2. **Model Building**
   - Designed a custom **CNN architecture** with multiple convolutional, pooling, and dense layers
   - Used ReLU activation and softmax output layer for multiclass classification

3. **Model Training**
   - Trained model on labeled images using categorical cross-entropy loss
   - Applied early stopping and batch normalization

4. **Model Evaluation**
   - Achieved **~66% accuracy** on validation set
   - Analyzed performance using classification report and confusion matrix

---

## ✅ Outcomes

- Successfully classified seedling species across 12 categories
- Demonstrated the effectiveness of CNNs in image classification tasks
- Provided a baseline model that can be expanded for real-world agricultural applications

---

## 📂 Dataset

The dataset includes labeled images of plant seedlings provided as part of the course. It contains 12 species folders such as:

- Black-grass
- Charlock
- Cleavers
- Common Chickweed
- Fat Hen
- Loose Silky-bent
- Maize
- Scentless Mayweed
- Shepherd’s Purse
- Small-flowered Cranesbill
- Sugar beet
- Common Wheat

## 📎 License & Credits

This project was developed as part of the [Advanced Machine Learning course at Great Learning](https://www.mygreatlearning.com/) & TEXAS McCOMBS(The University of Texas at Austin) 
All content is intended for educational and portfolio use only.


