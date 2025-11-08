Google colab link: https://colab.research.google.com/drive/1K06fIOTmP-ft2FrTjG3XDwGoym_1Imur?usp=sharing
# 🌦️ Quantum–AI Hybrid Weather Prediction

A **hybrid Quantum + Deep Learning** system for multi-city weather prediction.  
This project integrates **PennyLane-based quantum feature encoding** with **TensorFlow LSTM networks** to forecast temperature, precipitation, and humidity across multiple cities using **parallelized AI pipelines**.

---

## 🚀 Overview

This project demonstrates a **Quantum-Classical Hybrid AI architecture** designed to:
- Fetch weather data from **NASA POWER API** (or Kaggle datasets if provided)
- Encode statistical patterns using **Quantum Circuits (PennyLane + Qiskit)**
- Train **LSTM-based neural networks** with quantum-enhanced features
- Evaluate predictions for **Temperature, Precipitation, and Humidity**
- Provide **Explainable AI (SHAP)** insights and **visual reports**

---

## 🧠 Core Features

| Feature | Description |
|----------|--------------|
| 🌎 Multi-City Support | Predicts weather for multiple cities (Delhi, Mumbai, Bangalore, Kolkata) |
| ⚛️ Quantum Encoding | Encodes time-series features into quantum states using PennyLane |
| 🔁 Parallel Processing | Uses `joblib` for multi-city and multi-threaded data encoding |
| 🤖 Hybrid LSTM Model | Combines classical sequence data + quantum embeddings |
| 📊 Explainability | SHAP-based interpretability for hybrid feature importance |
| 🧩 Scalable Design | Easily extendable to other cities or weather parameters |

---

## 🧰 Dependencies & Libraries

### 🔬 Quantum & Hybrid AI
- `pennylane`, `pennylane-qiskit`, `pennylane-lightning`
- `qiskit`, `torch`, `jax`, `jaxlib`

### 🧠 Deep Learning
- `tensorflow`, `keras`

### 📈 Data & ML Tools
- `scikit-learn`, `joblib`, `dask`
- `pandas`, `numpy`, `requests`, `kaggle`

### 📊 Visualization & Analysis
- `matplotlib`, `seaborn`, `shap`

### 🧪 Evaluation Metrics
- `mean_squared_error`, `mean_absolute_error`, `r2_score`, `confusion_matrix`, `classification_report`, `precision_recall_fscore_support`

---

## ⚙️ Installation

Run the following to install all dependencies in your Colab or local environment:

```bash
pip install pennylane pennylane-qiskit pennylane-lightning qiskit torch tensorflow keras scikit-learn pandas numpy matplotlib seaborn shap joblib requests kaggle dask jax jaxlib
