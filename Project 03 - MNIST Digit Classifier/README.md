# 🧠 MNIST Handwritten Digit Classifier using PyTorch

A beginner-friendly Deep Learning project that builds and trains a **Neural Network** using **PyTorch** to recognize handwritten digits from the famous **MNIST dataset**. This project demonstrates the complete deep learning workflow, from loading data to training, evaluating, and making predictions.

---

## 📌 Project Overview

The MNIST dataset contains **70,000 grayscale images** of handwritten digits (0–9). Each image is **28×28 pixels** and belongs to one of **10 classes**.

In this project, you will learn how to:

- Load the MNIST dataset
- Preprocess image data
- Build a Neural Network using PyTorch
- Train the model
- Evaluate model performance
- Predict handwritten digits

---

## 🚀 Features

- ✅ Automatic MNIST dataset download
- ✅ Image preprocessing with TorchVision
- ✅ Fully Connected Neural Network
- ✅ ReLU Activation Function
- ✅ CrossEntropy Loss
- ✅ Adam Optimizer
- ✅ Model Evaluation
- ✅ Digit Prediction
- ✅ Beginner-friendly implementation

---

# 🛠️ Technologies Used

- Python 3
- PyTorch
- TorchVision
- NumPy
- Matplotlib
- Jupyter Notebook

---

# 📂 Project Structure

```
MNIST-Digit-Classifier/
│
├── Project 3 - MNIST Digit Classifier.ipynb
├── README.md
```

---

# 📊 Dataset

**MNIST Dataset**

- 60,000 Training Images
- 10,000 Test Images
- Image Size: **28 × 28**
- Grayscale Images
- 10 Output Classes (0–9)

Example Classes:

```
0 1 2 3 4 5 6 7 8 9
```

---

# 🧠 Model Architecture

The neural network consists of:

```
Input Image (28×28)

↓

Flatten Layer (784 Features)

↓

Fully Connected Layer

↓

ReLU Activation

↓

Output Layer (10 Classes)

↓

Softmax (handled by CrossEntropyLoss)
```

---

# 📉 Loss Function

Cross Entropy Loss

```python
criterion = nn.CrossEntropyLoss()
```

This loss function is ideal for multi-class classification problems.

---

# ⚙️ Optimizer

Adam Optimizer

```python
optimizer = torch.optim.Adam(model.parameters(), lr=0.001)
```

Adam combines the benefits of Momentum and RMSProp, making training faster and more stable.

---

# 📈 Training Process

The training loop includes:

1. Load a batch of images
2. Forward pass
3. Compute loss
4. Backpropagation
5. Update model parameters
6. Repeat for multiple epochs

---

# 📊 Model Evaluation

After training, the model is evaluated on the test dataset.

Evaluation metrics include:

- Test Accuracy
- Loss
- Correct Predictions

---

# 🔮 Predictions

The trained model can predict handwritten digits such as:

```
Input Image

   7

↓

Predicted Digit

   7
```

---

# ▶️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/sulthan-s/Deep-Learning-Using-Pytorch.git
```

### Navigate to the Project

```bash
cd MNIST-Digit-Classifier
```

### Install Dependencies

```bash
pip install torch torchvision matplotlib
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Project 3 - MNIST Digit Classifier.ipynb
```

Run all cells.

---

# 📚 Learning Outcomes

By completing this project, you will understand:

- PyTorch Basics
- Neural Networks
- Image Classification
- Dataset Loading with TorchVision
- Forward & Backward Propagation
- Gradient Descent
- CrossEntropy Loss
- Adam Optimizer
- Model Evaluation
- Prediction on New Images

---

# 🎯 Future Improvements

- Add Convolutional Neural Networks (CNNs)
- Save and Load Trained Models
- GPU (CUDA) Training
- Hyperparameter Tuning
- Data Augmentation
- TensorBoard Visualization
- Confusion Matrix
- Precision & Recall Metrics

---

# 📖 Requirements

Install the required packages:

```bash
pip install torch
pip install torchvision
pip install matplotlib
pip install numpy
```

Or create a `requirements.txt` file:

```text
torch
torchvision
numpy
matplotlib
```

---

# 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository, improve the project, and submit a pull request.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Sulthan Siyad**

Aspiring AI & Machine Learning Engineer passionate about Deep Learning, Computer Vision, NLP, and Generative AI.

---

# ⭐ Support

If you found this project useful:

- ⭐ Star this repository
- 🍴 Fork it
- 📢 Share it with others
- 💡 Follow for more PyTorch and AI projects

---

## 🚀 Happy Coding & Happy Learning!
```
