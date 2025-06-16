# Handwritten Digit Recognizer from Scratch

This project implements a neural network from scratch in **NumPy** to classify handwritten digits from the [Kaggle Digit Recognizer competition](https://www.kaggle.com/competitions/digit-recognizer).

The goal is to recognize digits (0–9) from grayscale images of size **28×28 pixels**, using a multi-layer feedforward neural network without any deep learning frameworks (e.g., TensorFlow or PyTorch).

---

## 🚀 Features

- Built using only NumPy (no deep learning libraries)
- Fully connected 3-layer neural network
- Activation functions: **Leaky ReLU**, **ReLU**, **Softmax**
- Achieves 96.2 % accuracy on test data
- Gradient descent optimization
- Easy-to-use inference and visualization functions

---

## 🧠 Architecture

```
Input Layer (784 nodes)
      ↓
Hidden Layer 1 (64 nodes) → ReLU
      ↓
Hidden Layer 2 (64 nodes) → Leaky Sigmoid
      ↓
Output Layer (10 nodes)  → Softmax
```

---

## 📁 Files

- `digit-recognizer-from-scratch.ipynb` – Jupyter notebook with complete model training and testing
- `submission.csv` – Sample submission file for Kaggle (28000 rows)
- `train.csv` – Train dataset further divided into train and dev (42000 rows)
- `README.md` – This documentation

---

## 🛠 How to Run (Google Colab / Local)

1. Upload the notebook to [Google Colab](https://colab.research.google.com/)
2. Upload the `train.csv` and `test.csv` files from the [Kaggle competition](https://www.kaggle.com/competitions/digit-recognizer/data)
3. Run each cell in order to train and generate predictions
4. Download the `submission.csv` file for Kaggle submission

---

## ✅ Results

| Metric        | Value        |
|---------------|--------------|
| Training Accuracy | 95.95 % |
| Test Accuracy     | 96.2 % |

---

## 📌 Dependencies

- Python 3.x
- NumPy
- pandas
- matplotlib

All dependencies are pre-installed on Google Colab or Kaggle Kernels.

---

## 👨‍💻 Author

**Anuj Trivedi**  
IIT Jodhpur 
2nd Year BTech, Chemical Engineering  
[LinkedIn](https://www.linkedin.com/in/anuj-trivedi-2a538827a/) • [GitHub](https://github.com/anujtrivedi06) 

---

