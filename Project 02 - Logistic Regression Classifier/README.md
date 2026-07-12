# Logistic Regression Classifier using PyTorch

A beginner-friendly implementation of **Logistic Regression** for binary classification using **PyTorch**. This project demonstrates how to build, train, and evaluate a logistic regression model from scratch using a simple dataset.

---

## 📌 Project Overview

This notebook covers the complete workflow of implementing a binary classifier using PyTorch:

- Creating a sample dataset
- Building a Logistic Regression model
- Defining the Binary Cross-Entropy Loss
- Training with Stochastic Gradient Descent (SGD)
- Predicting binary classes
- Inspecting learned parameters

---

## 🚀 Features

- ✅ Built completely with PyTorch
- ✅ Binary Classification
- ✅ Custom Logistic Regression Model
- ✅ Sigmoid Activation Function
- ✅ Binary Cross Entropy (BCELoss)
- ✅ SGD Optimizer
- ✅ Simple and beginner-friendly implementation

---

## 🛠️ Technologies Used

- Python 3
- PyTorch
- Torch.nn
- Torch.optim

---

## 📂 Project Structure

```
Logistic-Regression-PyTorch/
│
├── Project 2 - Logistic Regression Classifier.ipynb
├── README.md
└── requirements.txt
```

---

## 🧠 Model Architecture

The model consists of:

```
Input Feature
      │
Linear Layer
      │
Sigmoid Activation
      │
Binary Prediction (0 or 1)
```

Mathematically,

\[
\hat{y} = \sigma(wx+b)
\]

where

- **w** = Weight
- **b** = Bias
- **σ** = Sigmoid Function

---

## 📊 Loss Function

Binary Cross Entropy Loss

```python
criterion = nn.BCELoss()
```

Formula:

\[
L = -(y\log(\hat y)+(1-y)\log(1-\hat y))
\]

---

## ⚙️ Optimizer

Stochastic Gradient Descent (SGD)

```python
optimizer = torch.optim.SGD(model.parameters(), lr=0.1)
```

---

## 📈 Training

The model is trained for **1000 epochs**.

Training steps:

1. Forward Pass
2. Compute Loss
3. Backpropagation
4. Update Parameters

---

## 📌 Example Dataset

| Feature | Label |
|----------|------:|
| 1.0 | 0 |
| 2.0 | 0 |
| 3.0 | 1 |
| 4.0 | 1 |

---

## ▶️ Run the Notebook

Clone the repository

```bash
git clone https://github.com/yourusername/Logistic-Regression-PyTorch.git
```

Navigate into the project

```bash
cd Logistic-Regression-PyTorch
```

Install dependencies

```bash
pip install torch
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Project 2 - Logistic Regression Classifier.ipynb
```

---

## 📚 Learning Outcomes

By completing this project, you will understand:

- Binary Classification
- Logistic Regression
- Sigmoid Activation
- Binary Cross Entropy Loss
- Gradient Descent
- Model Training in PyTorch
- Making Predictions using Neural Networks

---

## 📖 Future Improvements

- Add accuracy calculation
- Train on a real-world dataset
- Data visualization
- Decision boundary plotting
- Multi-feature logistic regression
- GPU support

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork the repository, improve the implementation, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project helpful:

- ⭐ Star this repository
- 🍴 Fork it
- 📢 Share it with others learning PyTorch

---

## 👨‍💻 Author

**Sulthan Siyad**

Aspiring AI & Machine Learning Engineer passionate about Deep Learning, Computer Vision, NLP, and PyTorch.

---

### Happy Learning! 🚀
