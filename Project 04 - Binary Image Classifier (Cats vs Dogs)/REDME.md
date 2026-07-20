# 🐱🐶 Binary Image Classifier (Cats vs Dogs)

A Deep Learning project built with **PyTorch** that classifies images as either **Cat** or **Dog** using a Convolutional Neural Network (CNN). This project demonstrates the complete workflow of image preprocessing, model training, and binary image classification.

---

## 📌 Project Overview

This project uses a custom Convolutional Neural Network (CNN) to distinguish between cat and dog images. Images are resized, normalized, and passed through multiple convolutional layers to learn visual features before making binary predictions.

---

## 🚀 Features

- Image preprocessing using `torchvision.transforms`
- Custom CNN architecture
- Binary image classification
- PyTorch DataLoader for efficient batching
- Adam optimizer
- Binary Cross Entropy (BCELoss)
- Simple and easy-to-understand implementation

---

## 🛠️ Technologies Used

- Python
- PyTorch
- TorchVision
- NumPy
- Matplotlib (optional for visualization)

---

## 📂 Project Structure

```
Binary-Image-Classifier/
│
├── data/
│   └── train/
│       ├── cat/
│       └── dog/
│
├── Project 4 - Binary Image Classifier (Cats vs Dogs).ipynb
├── README.md
```

---

## 🧠 Model Architecture

The model consists of:

- Convolution Layer (3 → 16)
- ReLU Activation
- Max Pooling
- Convolution Layer (16 → 32)
- ReLU Activation
- Max Pooling
- Fully Connected Layers
- Sigmoid Output Layer

Output:

- **0 → Cat**
- **1 → Dog**

---

## 📊 Data Preprocessing

Images are processed using:

- Resize to **128 × 128**
- Convert to Tensor
- Normalize pixel values

```python
transforms.Compose([
    transforms.Resize((128,128)),
    transforms.ToTensor(),
    transforms.Normalize([0.5],[0.5])
])
```

---

## ⚙️ Training Configuration

| Parameter | Value |
|-----------|--------|
| Optimizer | Adam |
| Loss Function | BCELoss |
| Learning Rate | 0.001 |
| Batch Size | 32 |
| Epochs | 5 |

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Binary-Image-Classifier.git
cd Binary-Image-Classifier
```

### 2. Install dependencies

```bash
pip install torch torchvision matplotlib numpy
```

### 3. Organize dataset

```
data/
└── train/
    ├── cat/
    └── dog/
```

### 4. Run the notebook

Open:

```
Project 4 - Binary Image Classifier (Cats vs Dogs).ipynb
```

Train the model by executing all cells.

---

## 📈 Workflow

```
Dataset
   │
   ▼
Image Preprocessing
   │
   ▼
DataLoader
   │
   ▼
CNN Model
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

- Building CNNs from scratch in PyTorch
- Image preprocessing techniques
- Binary image classification
- Training neural networks
- Using DataLoader for efficient training
- Binary Cross Entropy loss
- Optimizing models using Adam optimizer

---

## 🔮 Future Improvements

- Add validation and test datasets
- Implement model checkpointing
- Add accuracy, precision, recall, and F1-score
- Data augmentation
- Transfer Learning using ResNet18 or EfficientNet
- Hyperparameter tuning
- Deploy as a web application using Streamlit or Flask

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

If you'd like to improve this project, feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is intended for educational and learning purposes.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

Happy Coding! 🚀
