# ✍️ Handwritten Digit Recognition — Neural Network Comparison

A neural network project that compares multiple MLP architectures and activation functions for classifying handwritten digits (0–9).

---

## 📌 Problem Statement

Handwritten digit recognition is a classic computer vision problem. This project explores how different neural network configurations (depth, width, activation function) affect classification performance on the MNIST-style digits dataset.

---

## 📊 Dataset

- **Source:** Scikit-learn built-in `load_digits` (based on UCI ML Digits Dataset)
- **Records:** 1,797 samples
- **Features:** 64 features (8×8 pixel grayscale images)
- **Classes:** 10 (digits 0–9)
- **Split:** 70% train / 30% test

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** NumPy, Scikit-learn, Matplotlib, Seaborn

---

## 🤖 Models Compared

| Model | Architecture | Activation |
|---|---|---|
| Tiny | (5,) | ReLU |
| Small | (10,) | ReLU |
| Medium | (32, 16) | ReLU |
| Complex | (64, 32, 16) | ReLU |
| Tanh | (32, 16) | Tanh |
| Logistic | (32, 16) | Sigmoid |

---

## 🔄 Project Pipeline

1. **Data Loading** — load_digits from Scikit-learn
2. **Preprocessing** — StandardScaler normalization, train/test split
3. **Model Training** — 6 MLP configurations trained and evaluated
4. **Best Model Selection** — automatically picks highest accuracy
5. **Evaluation** — Classification Report + Confusion Matrix heatmap

---

## 📈 Evaluation Metrics

- Accuracy Score
- Classification Report (Precision, Recall, F1-score per digit)
- Confusion Matrix (visualized as heatmap)

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/ahmedharb2004/handwritten-digit-recognition.git
cd handwritten-digit-recognition

# 2. Install dependencies
pip install numpy scikit-learn matplotlib seaborn

# 3. Run the notebook
jupyter notebook Handwritten_Digit_Recognition_Comparison.ipynb
```

---

## 📁 Repository Structure

```
├── Handwritten_Digit_Recognition_Comparison.ipynb
└── README.md
```

---

## 👤 Author

**Ahmed Harb**
- GitHub: [@ahmedharb2004](https://github.com/ahmedharb2004)
- LinkedIn: [Ahmed Harb](https://www.linkedin.com/in/ahmed-mohamed-el-sayed-harb-735786322)
