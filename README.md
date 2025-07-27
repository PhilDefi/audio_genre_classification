# 🎵 Audio Genre Classification using Deep Learning POC

This project focuses on classifying audio tracks into musical genres using deep learning techniques. The models are trained on audio features extracted from music clips. Multiple architectures were explored including a simple Feedforward Neural Network, a Convolutional Neural Network (CNN), and a Recurrent Neural Network (RNN) with LSTM layers.

## 🔍 Problem Statement

Automatically classifying audio into its correct genre is a challenging task due to the temporal and spectral nature of music. This project attempts to solve this problem by extracting relevant audio features and feeding them into neural network models.

---

## 🛠️ Technologies & Libraries Used

- **Python** 🐍
- **TensorFlow / Keras** – for building and training deep learning models
- **Librosa** – for audio processing and feature extraction (MFCCs)
- **NumPy & Pandas** – for data manipulation
- **Scikit-learn** – for preprocessing and splitting data
- **Matplotlib & Seaborn** – for plotting results
- **MLflow** – for tracking experiments and model runs

---

## 🎧 Audio Feature Extraction

I used **Librosa** to extract **MFCCs (Mel Frequency Cepstral Coefficients)** from the audio clips. MFCCs are a compact representation of the spectral properties of sound and are widely used in audio classification tasks.

<img width="1105" height="539" alt="image" src="https://github.com/user-attachments/assets/67b0d452-a717-4ea6-a549-3af941b8d965" />


## 🧠 Models Trained
1️⃣ Feedforward Neural Network (DNN)
Architecture:

Flatten → Dense(512 → 256 → 64) → Dropout → Output (Softmax)


2️⃣ Convolutional Neural Network (CNN)
Architecture:

Conv2D → MaxPooling → BatchNorm → Dense → Dropout → Output


3️⃣ LSTM Recurrent Network
Architecture:

LSTM (64, return_sequences=True) → LSTM(64) → Dense → Dropout → Output

## Results

<img width="1553" height="977" alt="image" src="https://github.com/user-attachments/assets/165c6133-5c85-40b3-b6a3-2cb1798a515c" />

<img width="1528" height="1047" alt="image" src="https://github.com/user-attachments/assets/a94e665f-3f6a-4c2e-8eb6-b788b0ee5eb0" />


## 👤 Author
Philippe Deflandre
