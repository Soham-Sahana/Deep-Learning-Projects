<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Deep%20Learning%20Projects&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Neural%20Network%20Architectures%20%7C%20Computer%20Vision%20%7C%20NLP&descSize=16&descAlignY=55"/>

<br/>

![Python](https://img.shields.io/badge/Python-3.10+-14354C?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

<br/>

A collection of end-to-end deep learning projects covering **ANNs**, **CNNs**, **RNNs**, **LSTMs**, **GRUs**, and **Transfer Learning** — built with TensorFlow/Keras.

---

[Explore Projects](#-projects) · [Models](#-trained-models) · [Getting Started](#-getting-started) · [Tech Stack](#%EF%B8%8F-tech-stack)

</div>

<br/>

## 📂 Projects

### 🖼️ Computer Vision

| Project | Architecture | Description |
|---------|-------------|-------------|
| [**Beans Disease Classification**](CNN.ipynb) | VGG16 / ResNet50 | Transfer learning for plant disease detection on the Beans dataset. Fine-tuned VGG16 (57 MB) and ResNet50 (94 MB) models included. |
| [**MNIST Digit Recognition**](MNIST.ipynb) | CNN | Convolutional neural network for handwritten digit classification on the MNIST dataset. |

### 💬 Natural Language Processing

| Project | Architecture | Description |
|---------|-------------|-------------|
| [**Sentiment Analysis**](ANN.ipynb) | RNN / LSTM / GRU | Comparative study of three recurrent architectures for sentiment classification. All three trained models are included. |
| [**Next Word Prediction**](ANN.ipynb) | LSTM | Language model that predicts the next word in a sequence using LSTM layers. |

### 🧠 Classical Deep Learning

| Project | Architecture | Description |
|---------|-------------|-------------|
| [**Customer Churn Prediction**](Churn_Modelling.ipynb) | ANN | Binary classification using a fully connected neural network to predict customer churn. |
| [**ANN Regression**](ANN_Regression.ipynb) | ANN | Regression task using artificial neural networks for continuous value prediction. |
| [**K-Fold Cross Validation**](K_Fold_Cross_Validation.ipynb) | ANN | Demonstrates K-Fold CV technique for robust model evaluation and reducing overfitting. |

---

## 🏗️ Architecture Overview

```
Deep-Learning-Projects/
│
├── 🖼️ Computer Vision
│   ├── CNN.ipynb                  # Beans classification with VGG16/ResNet50
│   ├── MNIST.ipynb                # Handwritten digit recognition
│   ├── beans_vgg16.keras          # Trained VGG16 model (57 MB)
│   └── beans_resnet50.keras       # Trained ResNet50 model (94 MB)
│
├── 💬 NLP
│   ├── sentiment_rnn.keras        # Sentiment Analysis - RNN
│   ├── sentiment_lstm.keras       # Sentiment Analysis - LSTM
│   ├── sentiment_gru.keras        # Sentiment Analysis - GRU
│   └── next_word_lstm.keras       # Next Word Prediction - LSTM
│
├── 🧠 ANN
│   ├── ANN.ipynb                  # ANN for classification
│   ├── ANN_Regression.ipynb       # ANN for regression
│   ├── Churn_Modelling.ipynb      # Customer churn prediction
│   └── K_Fold_Cross_Validation.ipynb  # K-Fold CV demo
│
└── README.md
```

---

## 🧪 Trained Models

| Model File | Architecture | Task | Size |
|-----------|-------------|------|------|
| `beans_vgg16.keras` | VGG16 (Transfer Learning) | Beans Disease Classification | 57 MB |
| `beans_resnet50.keras` | ResNet50 (Transfer Learning) | Beans Disease Classification | 94 MB |
| `sentiment_rnn.keras` | Simple RNN | Sentiment Analysis | 3.7 MB |
| `sentiment_lstm.keras` | LSTM | Sentiment Analysis | 3.8 MB |
| `sentiment_gru.keras` | GRU | Sentiment Analysis | 3.8 MB |
| `next_word_lstm.keras` | LSTM | Next Word Prediction | 11.4 MB |

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn jupyter
```

### Load a Pre-trained Model

```python
from tensorflow.keras.models import load_model

# Load any trained model
model = load_model('beans_vgg16.keras')

# Make predictions
predictions = model.predict(your_data)
```

### Run a Notebook

```bash
jupyter notebook MNIST.ipynb
```

---

## ⚙️ Tech Stack

<div align="center">

| Category | Technologies |
|----------|-------------|
| **Language** | Python 3.10+ |
| **DL Framework** | TensorFlow, Keras |
| **ML Library** | scikit-learn |
| **Data** | NumPy, Pandas |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook |
| **Pre-trained Models** | VGG16, ResNet50 (ImageNet) |

</div>

---

## 📖 Key Concepts Covered

- **Artificial Neural Networks (ANN)** — Fully connected layers for classification and regression
- **Convolutional Neural Networks (CNN)** — Feature extraction for image tasks
- **Recurrent Neural Networks (RNN)** — Sequential data processing
- **Long Short-Term Memory (LSTM)** — Handling long-range dependencies
- **Gated Recurrent Units (GRU)** — Efficient alternative to LSTMs
- **Transfer Learning** — Fine-tuning VGG16 and ResNet50 on custom datasets
- **K-Fold Cross Validation** — Robust model evaluation strategy
- **Binary and Multi-class Classification** — Various classification tasks
- **Regression with Deep Learning** — Continuous value prediction

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

---

## 📬 Contact

**Soham Sahana** — [GitHub](https://github.com/Soham-Sahana)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>

</div>