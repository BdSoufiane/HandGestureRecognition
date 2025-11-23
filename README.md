# Hand Gesture Recognition using CNN
This project implements a Convolutional Neural Network (CNN) to classify hand gestures using the Sign Language MNIST dataset.
The goal is to build an image-based hand gesture classifier for Human–Machine Interaction.
## 📁 Project Structure

HandGestureRecognition/
│
├── training.ipynb                # Training notebook
│
├── models/
│   └── hand_gesture_model.keras  # Saved trained model
│
├── data/                         # Dataset (optional to include)
│   ├── sign_mnist_train.csv
│   └── sign_mnist_test.csv
│
├── requirements.txt              # Dependencies
└── README.md                     # Project documentation


Features

CNN-based hand gesture classification

Training on Sign Language MNIST

Preprocessing, normalization, reshaping

Training & validation accuracy and loss curves

Confusion matrix

Single-image prediction example

Model saved in .keras format

## 🔧 Installation

pip install -r requirements.txt

## ▶️ Training

Open the notebook:

hand_gesture_project.ipynb


It includes:

Data loading

Preprocessing

Model creation

Training & evaluation

Saving the model

Plotting curves & confusion matrix

Results

Test Accuracy: ~89%

Confusion Matrix: included

Training/Validation curves: included

Correct predictions visualized


Author

Soufiane Baddah - Zakaria Ahaji
GitHub: https://github.com/BdSoufiane

