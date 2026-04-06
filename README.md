# 🎨 Children's Drawing Analysis Using AI

An AI-powered system that analyzes children's drawings to detect emotional and psychological states using computer vision and deep learning.

---

## 🚀 Overview

This project aims to support parents, educators, and psychologists by providing insights into a child's emotional state based on their drawings.

The system analyzes visual patterns such as colors, shapes, and composition to classify emotions expressed in children's artwork.

---

## 🧠 Features

* Emotion classification from children's drawings
* Supports four emotional categories:

  * 😢 Sad
  * 😨 Fear
  * 😊 Happy
  * 😡 Angry
* Uses deep learning for visual pattern recognition
* Provides prediction results based on image input

---

## ⚙️ How It Works

1. Input: Image of a child’s drawing
2. Preprocessing: Image resizing and normalization
3. Model: MobileNetV2 fine-tuned on a labeled dataset
4. Output: Emotion classification result

---

## 🏷️ Classes

The model predicts one of the following classes:

```python
classes = ["Sad", "Fear", "Happy", "Angry"]
```

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib

---

## 📂 Dataset

The model was trained on a dataset of children's drawings categorized by emotional labels.

* Dataset type: Image dataset
* Labels: Sad, Fear, Happy, Angry
* Source: Vishmi Perera – Children's Drawing Emotion Dataset

> Note: The dataset is not included in this repository due to size limitations.

---

## 📊 Results

The model predicts emotional states based on drawing patterns and visual features.

### Example Predictions

* Sad
* Fear
* Happy
* Angry

> You can add sample output images inside the `images/` folder and display them here.

---

## 📁 Project Structure

```bash
├── train_model.py
├── predict_image.py
├── requirements.txt
├── README.md
└── images/
```

---

## ▶️ How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Run prediction:

```bash
python predict_image.py
```

---

## 💡 Use Cases

* Helping parents better understand children's emotions
* Supporting psychologists and educators
* Exploring AI applications in emotional and behavioral analysis

---

## 🔮 Future Improvements

* Improve model accuracy with a larger dataset
* Add confidence scores for predictions
* Build a web-based or mobile-based interface
* Expand the system to support more emotional categories

---

## 👩‍💻 Author

**Shams Abdullah Alarifi**
AI Engineer | Machine Learning | Computer Vision

---
