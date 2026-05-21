#  🍔CNN-Food-Classification
A deep learning powered food image classification system built using **Custom CNN**, **VGG16**, and **ResNet** architectures with **Redis integration** for nutritional information retrieval.

The application allows users to upload food images, select different deep learning models, and receive predictions along with confidence scores, nutrition details, and model evaluation metrics.

---

## 🚀 Project Overview

Food Vision AI combines:

- Deep Learning
- Computer Vision
- Flask Web Development
- Redis Database
- Transfer Learning

The system predicts food categories and displays nutritional insights through an interactive dashboard.

---

## ✨ Features

 Upload food images  

 Multi-model prediction support  

 Custom CNN model implementation  

 VGG16 transfer learning  

 ResNet architecture  

 Redis database integration  

 Nutrition information retrieval  

 Confidence score visualization  

 Accuracy, Precision, Recall, F1 Score  

 Glassmorphism UI  

 Dynamic result dashboard  

---

# 🛠 Tech Stack

### Frontend
- HTML
- CSS
- Jinja2

### Backend
- Flask
- Python

### Deep Learning
- TensorFlow
- Keras
- CNN
- VGG16
- ResNet

### Database
- Redis

### Libraries
- NumPy
- Pandas
- OpenCV
- Pillow
- Scikit-learn
- Matplotlib

---

# 📂 Project Structure

```bash
CNN FC/
│
├── Custom_CNN/
│   ├── custom_cnn_metrics.json
│   └── food_classification_custom_model.h5
│
├── VGG_16/
│   ├── model_evaluation_results_vgg16.json
│   └── vgg16_food_classification_model.keras
│
├── ResNet/
│   ├── food_classification_custom_Resnetmodel.keras
│   └── model_evaluation_resnet_results.json
│
├── static/
│   ├── uploads/
│   ├── image.jpeg
│   └── style.css
│
├── templates/
│   └── index.html
│
├── Food_Detail.json
├── app.py
├── main.py
├── redis data connect.py
├── store_metrics_redis.py
├── train_model.ipynb
├── Screenshot 2026-05-21 111056.png
├── Screenshot 2026-05-21 111140.png
├── requirements.txt
└── README.md
```

---

# ⚙ Installation

Clone repository:

```bash
git clone https://github.com/yourusername/Food-Vision-AI.git
```

Move into project:

```bash
cd Food-Vision-AI
```

Create virtual environment:

```bash
python -m venv .venv
```

Activate environment:

### Windows

```bash
.venv\Scripts\activate
```

### Linux/Mac

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 📦 Requirements

```txt
numpy
pandas
matplotlib
scikit-learn
tensorflow
opencv-python
pillow
redis
fastapi
uvicorn
flask
keras
```

---

# ▶ Running the Project

Start Redis server:

```bash
redis-server
```

Load nutrition data:

```bash
python "redis data connect.py"
```

Run application:

```bash
python app.py
```

Open browser:

```bash
http://127.0.0.1:5000
```

---

# 🔄 Project Workflow

### Step 1

Upload food image

↓

### Step 2

Choose model:

- Custom CNN
- VGG16
- ResNet

↓

### Step 3

Image preprocessing

↓

### Step 4

Model prediction

↓

### Step 5

Retrieve nutrition details from Redis

↓

### Step 6

Display:

- Predicted food
- Confidence score
- Metrics
- Nutrition values

---

# 📸 Application Screenshots

## 🏠 Home Page — Before Prediction

Initial dashboard interface before prediction.

<p align="center">
<img src="Screenshot%202026-05-21%20111056.png" width="100%">
</p>

Features shown:

- Upload image option
- Model selection
- Food class list
- User dashboard
- Total class count

---

## 🔍 Prediction Result — After Prediction

Displays predicted food class with nutrition and evaluation metrics.

<p align="center">
<img src="Screenshot%202026-05-21%20111140.png" width="100%">
</p>

Prediction details:

- Food prediction
- Confidence score
- Nutrition details
- Model metrics
- Uploaded image preview

---

# 📊 Model Metrics

| Metric | Description |
|----------|-------------|
| Accuracy | Overall prediction performance |
| Precision | Correct positive predictions |
| Recall | Ability to retrieve relevant predictions |
| F1 Score | Harmonic mean of precision and recall |

---

# 🧠 Models Used

## Custom CNN

Custom convolutional neural network trained for food classification.

Layers used:

- Conv2D
- MaxPooling
- BatchNormalization
- Dropout
- Dense

---

## VGG16

Transfer learning architecture using ImageNet pretrained weights.

Advantages:

- Deep feature extraction
- Better generalization

---

## ResNet

Residual Neural Network architecture with skip connections.

Advantages:

- Solves vanishing gradients
- High performance classification

---

# 📈 Future Improvements

- Docker deployment
- Cloud deployment
- Camera-based prediction
- Mobile application
- Recommendation engine
- Authentication system

---

# 👨‍💻 Developer

### Nikhil Goud

AI Engineer | Deep Learning Developer | Computer Vision Enthusiast

Skills:

- Machine Learning
- Deep Learning
- TensorFlow
- OpenCV
- Flask
- Redis
- Computer Vision

---

# ⭐ Support

If you like this project:

Give it a ⭐ on GitHub.
