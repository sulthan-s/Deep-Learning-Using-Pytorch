# 🚀 Linear Regression Using PyTorch

A beginner-friendly deep learning project that demonstrates how to build and train a simple **Linear Regression model using PyTorch**. This project walks through the complete machine learning workflow including data preparation, model creation, training, loss calculation, optimization, and prediction.

---

## 📌 Project Overview

This notebook introduces the fundamentals of **Deep Learning with PyTorch** by implementing a simple linear regression model.

The model learns the relationship between input features and target values using:

* PyTorch tensors
* `nn.Linear()` layer
* Loss functions
* Gradient descent optimization
* Backpropagation

The project is ideal for:

* Beginners learning PyTorch
* Students exploring Deep Learning fundamentals
* Anyone transitioning from Machine Learning to Neural Networks

---

## 🧠 Concepts Covered

### ✅ PyTorch Fundamentals

* Tensor creation
* Automatic differentiation (`autograd`)
* Neural network modules
* Training loops

### ✅ Linear Regression

* Supervised learning
* Predicting continuous values
* Weight and bias learning
* Loss minimization

### ✅ Deep Learning Workflow

1. Prepare dataset
2. Define model
3. Define loss function
4. Configure optimizer
5. Train the model
6. Make predictions

---

## 🛠️ Technologies Used

| Technology       | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Programming Language    |
| PyTorch          | Deep Learning Framework |
| NumPy            | Numerical Operations    |
| Matplotlib       | Data Visualization      |
| Jupyter Notebook | Development Environment |

---

## 📂 Project Structure

```bash
📦 Linear-Regression-PyTorch
 ┣ 📜 Project 1 - Linear Regression using Pytorch.ipynb
 ┣ 📜 README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/sulthan-s/linear-regression-pytorch.git
cd linear-regression-pytorch
```

### 2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate environment:

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```
---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
Project 1 - Linear Regression using Pytorch.ipynb
```

Run all notebook cells.

---

## 📈 Model Workflow

### Step 1 — Import Libraries

```python
import torch
import torch.nn as nn
```

### Step 2 — Create Dataset

```python
X = torch.tensor(...)
Y = torch.tensor(...)
```

### Step 3 — Define Model

```python
model = nn.Linear(in_features=1, out_features=1)
```

### Step 4 — Define Loss & Optimizer

```python
criterion = nn.MSELoss()
optimizer = torch.optim.SGD(model.parameters(), lr=0.01)
```

### Step 5 — Training Loop

```python
for epoch in range(epochs):
    predictions = model(X)
    loss = criterion(predictions, Y)

    optimizer.zero_grad()
    loss.backward()
    optimizer.step()
```

---

## 📊 Output

The model learns the best-fit line for the provided data.

Typical outputs include:

* Training loss reduction
* Learned weights and bias
* Predicted values
* Visualization of regression line

---

## 📉 Example Learning Equation

The project demonstrates learning a relationship of the form:

genui{"math_block_widget_always_prefetch_v2":{"content":"y = wx + b"}}

Where:

* `x` → Input feature
* `w` → Weight
* `b` → Bias
* `y` → Predicted output

---

## 🎯 Learning Outcomes

By completing this project, you will understand:

* How neural networks learn
* How gradient descent works
* How backpropagation updates parameters
* How PyTorch simplifies Deep Learning workflows
* How to train simple AI models from scratch

---

## 🔥 Future Improvements

You can extend this project by adding:

* Multiple input features
* Polynomial regression
* Real-world datasets
* GPU training
* Model saving/loading
* Performance evaluation metrics
* Data normalization

---

## 📚 Resources

* urlPyTorch Official Documentation[https://pytorch.org/docs/stable/index.html](https://pytorch.org/docs/stable/index.html)
* urlPyTorch Tutorials[https://pytorch.org/tutorials/](https://pytorch.org/tutorials/)

---

## 🤝 Contributing

Contributions are welcome.

If you'd like to improve this project:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful:

* Star the repository
* Share it with others
* Follow for more AI/ML projects

---

## 👨‍💻 Author

Developed by **Sulthan S**

Passionate about:

* Artificial Intelligence
* Machine Learning
* Deep Learning
* Computer Vision
* NLP
