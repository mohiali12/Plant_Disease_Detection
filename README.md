# 🌿 Plant Disease Detection System

This project is a **Deep Learning-based Plant Disease Detection System** that identifies diseases in plant leaves using the **EfficientNetV2** Convolutional Neural Network (CNN).  
It helps farmers and researchers detect plant diseases quickly and accurately from images of leaves.

---

## 🚀 Features
- 🌱 Detects multiple plant diseases automatically from leaf images  
- 🧠 Uses **EfficientNetV2** for high-accuracy image classification  
- 💻 Web-based interface built with **Flask**  
- 📷 Real-time image upload and disease prediction  
- 🧾 Trained and tested on a custom dataset of healthy and diseased leaves  

---

## 🧠 Tech Stack
**Languages & Frameworks**
- Python  
- TensorFlow / Keras  
- Flask  
- OpenCV  
- NumPy, Pandas, Matplotlib  

**Tools**
- Google Colab (for model training)  
- Jupyter Notebook  
- Visual Studio Code  

---
## 📂 Project Structure
Plant-Disease-Detection/
│
├── dataset/ # Training and testing images
├── models/ # Trained model (.h5)
├── notebooks/ # Jupyter notebook
│ └── plant_disease_detection.ipynb
├── src/ # Source code modules
│ ├── data_preprocessing.py
│ ├── model_training.py
│ ├── model_evaluation.py
│ └── prediction.py
├── templates/ # HTML files (Flask)
│ └── index.html
├── static/ # CSS, JS, images
│ └── style.css
├── app.py # Flask backend application
├── requirements.txt # Dependencies
└── README.md # Documentation



---

## 🧩 Model Overview
The system uses **EfficientNetV2**, a powerful convolutional neural network architecture known for efficiency and accuracy.  
The model was trained on a labeled dataset containing both **healthy** and **diseased** plant leaf images.

| Parameter | Description |
|------------|-------------|
| Model Type | EfficientNetV2 |
| Framework | TensorFlow / Keras |
| Input | Leaf Image |
| Output | Disease Category / Healthy |

---

## ⚙️ Installation and Setup

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection


pip install -r requirements.txt

python app.py

http:----------


Metric	        Value
Training     Accuracy	96%
Validation   Accuracy	94%
Model      	EfficientNetV2
Dataset Size	 10,000+ images


How It Works
Upload a plant leaf image through the web app.
The image is preprocessed and passed into the trained model.
The model predicts whether the leaf is Healthy or Diseased.
The result appears instantly on the screen.


Future Enhancements
Add more crop types and disease classes
Deploy model on cloud (AWS / GCP)
Create Android mobile version
Real-time camera detection


