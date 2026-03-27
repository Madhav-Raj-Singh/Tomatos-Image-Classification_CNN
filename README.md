🍅 Tomato Leaf Disease Classification using CNN

📌 Overview

This project builds a Convolutional Neural Network (CNN) model to classify tomato leaf diseases from images. The model is trained on a dataset containing 4 different classes of tomato leaf conditions.

The goal is to enable early detection of plant diseases and assist in improving agricultural productivity.

⸻

🚀 Features
	•	Image classification using CNN
	•	Multi-class classification (4 classes)
	•	Data preprocessing and normalization
	•	Efficient data pipeline using TensorFlow
	•	Train-validation split for model evaluation

⸻

📂 Dataset
	•	Tomato Leaf Image Dataset
	•	Total Classes: 4

Classes:
	•	Tomato_Healthy
	•	Tomato_Disease_1
	•	Tomato_Disease_2
	•	Tomato_Disease_3

⸻

🧠 Model Architecture
	•	Input Layer (Image: 128x128)
	•	Convolutional Layers (Conv2D + ReLU)
	•	MaxPooling Layers
	•	Flatten Layer
	•	Dense Layers
	•	Output Layer: Dense(4, activation='softmax')

⸻

⚙️ Tech Stack
	•	Python
	•	TensorFlow / Keras
	•	NumPy
	•	Matplotlib

📊 Training Details
	•	Epochs: 20–30
	•	Batch Size: 32
	•	Optimizer: Adam
	•	Loss Function: Categorical Crossentropy

⸻

📈 Results
	•	Model achieves good accuracy on training and validation data
	•	Loss decreases consistently during training
	•	Suitable for multi-class image classification tasks
