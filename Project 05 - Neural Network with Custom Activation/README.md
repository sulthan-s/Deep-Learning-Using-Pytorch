# 🧠 Neural Network with Custom Activation

A Deep Learning project built with **PyTorch** that demonstrates how to create and use **custom activation functions** in a neural network. This project explores the flexibility of PyTorch by implementing a user-defined activation function and integrating it into a fully connected neural network.

---

## 📌 Project Overview

This project focuses on understanding the inner workings of neural networks by replacing standard activation functions (such as ReLU or Sigmoid) with a custom activation function. It showcases how custom layers can be implemented using PyTorch while training a neural network for a classification task.

---

## 🚀 Features

- Custom activation function implementation
- Feedforward Neural Network (ANN)
- PyTorch-based model development
- Forward propagation with custom layers
- Model training and evaluation
- Easy-to-understand implementation for beginners

---

## 🛠️ Technologies Used

- Python
- PyTorch
- TorchVision
- NumPy
- Matplotlib

---

## 📂 Project Structure

```
Neural-Network-Custom-Activation/
│
├── data/
├── Project 5 - Neural Network with Custom Activation.ipynb
├── README.md
└── requirements.txt
```

---

## 🧠 Model Architecture

The neural network consists of:

- Input Layer
- Hidden Layer(s)
- **Custom Activation Function**
- Fully Connected Layer
- Output Layer

Example Workflow:

```
Input
   │
Linear Layer
   │
Custom Activation
   │
Linear Layer
   │
Output
```

---

## ⚙️ Custom Activation Function

Instead of using built-in activation functions, this project demonstrates how to define your own activation function by subclassing `torch.nn.Module`.

Example:

```python
class CustomActivation(nn.Module):
    def forward(self, x):
        # Custom activation logic
        return x
```

This flexibility allows experimentation with new nonlinear transformations and research-oriented neural network architectures.

---

## 📊 Training Configuration

| Parameter | Value |
|-----------|--------|
| Optimizer | Adam |
| Loss Function | CrossEntropyLoss |
| Learning Rate | 0.001 |
| Batch Size | 32 |
| Epochs | 10 |

> *Values may vary depending on your notebook configuration.*

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Neural-Network-Custom-Activation.git
cd Neural-Network-Custom-Activation
```

### 2. Install dependencies

```bash
pip install torch torchvision matplotlib numpy
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the notebook

```
Project 5 - Neural Network with Custom Activation.ipynb
```

Run all cells sequentially to train and evaluate the model.

---

## 📈 Workflow

```
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Neural Network
   │
   ▼
Custom Activation
   │
   ▼
Training
   │
   ▼
Prediction
```

---

## 📚 Learning Outcomes

Through this project, I learned:

- Building Artificial Neural Networks (ANNs) in PyTorch
- Creating custom activation functions
- Extending `torch.nn.Module`
- Forward propagation mechanics
- Model training and optimization
- Using custom layers within neural networks
- Experimenting with different activation strategies

---

## 🔮 Future Improvements

- Compare custom activation with ReLU, GELU, and Swish
- Add validation accuracy tracking
- Implement learning rate scheduling
- Hyperparameter tuning
- Visualize activation functions
- Experiment with deeper neural network architectures
- Deploy the model using Streamlit

---

## 🤝 Contributing

Contributions, suggestions, and feature requests are welcome.

Feel free to fork this repository and submit a pull request to improve the project.

---

## 📄 License

This project is intended for educational and learning purposes.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

Happy Learning! 🚀
