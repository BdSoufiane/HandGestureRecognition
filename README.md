 Hand Gesture Recognition using CNN

This project implements a Convolutional Neural Network (CNN) to classify hand gestures using the Sign Language MNIST dataset.
The goal is to build an image-based gesture recognition system for Human–Machine Interaction (HMI).

📁 Project Structure
HandGestureRecognition/
│
├── training.ipynb # Training notebook
│
├── models/
│ └── hand_gesture_model.keras # Saved trained model
│
├── data/ # Dataset (optional)
│ ├── sign_mnist_train.csv
│ └── sign_mnist_test.csv
│
├── requirements.txt # Dependencies
└── README.md # Project documentation

 Features

🧠 CNN-based hand gesture classification

📝 Training on Sign Language MNIST

🔄 Image preprocessing (reshape, normalization)

📈 Training & validation accuracy and loss curves

🧮 Confusion matrix visualization

🔍 Single-image prediction example

💾 Model saved in .keras format

🔧 Installation

Install all dependencies:

pip install -r requirements.txt

▶️ Training

Open and run the notebook:

training.ipynb


The notebook includes:

Dataset loading

Preprocessing

CNN model architecture

Model training

Evaluation on the test set

Confusion matrix

Prediction examples

Saving the model

📊 Results

Test Accuracy: ~89%

✔️ Confusion Matrix included

✔️ Accuracy / Loss curves included

✔️ Example predictions included

👥 Authors

Soufiane Baddah

Zakaria Ahaji

GitHub: https://github.com/BdSoufiane

