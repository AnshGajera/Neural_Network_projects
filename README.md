# 🧠 Neural Network Projects

A collection of end-to-end deep learning and neural network projects built with Python and Jupyter Notebooks, covering image classification, regression, and binary classification tasks.

---

## 📁 Projects Overview

| Project | Type | Description |
|---|---|---|
| [Cat vs Dog CNN](#-cat-vs-dog-cnn) | Image Classification | Classify images as cat or dog using a Convolutional Neural Network |
| [MNIST CNN](#-mnist-cnn) | Image Classification | Handwritten digit recognition on the MNIST dataset |
| [Walmart Sales](#-walmart-sales) | Regression | Predict weekly sales for Walmart stores |
| [Car Price Prediction](#-car-price-prediction) | Regression | Predict car prices based on features |
| [Heart Disease Prediction](#-heart-disease-prediction) | Binary Classification | Predict presence of heart disease in patients |
| [House Price Prediction](#-house-price-prediction) | Regression | Predict housing prices from structured features |

---

## 🐱 Cat vs Dog CNN

**Folder:** `Cat_Dog_CNN/`

A binary image classifier that distinguishes between cats and dogs using a Convolutional Neural Network (CNN).

- Uses convolutional layers for feature extraction from images
- Data augmentation to improve generalization
- Binary cross-entropy loss with sigmoid output

---

## 🔢 MNIST CNN

**Folder:** `MNIST_CNN/`

Handwritten digit recognition using the classic MNIST dataset.

- Multi-class classification (digits 0–9)
- CNN architecture with pooling and dense layers
- Achieves high accuracy on the MNIST benchmark

---

## 🛒 Walmart Sales

**Folder:** `Walmart/`

Predicts weekly store sales for Walmart using historical data.

- Feature engineering on date, store, and economic indicators
- Neural network regression model
- Evaluated using RMSE / MAE metrics

---

## 🚗 Car Price Prediction

**Folder:** `carprice/`

Predicts the selling price of cars based on attributes like brand, mileage, fuel type, and age.

- Data preprocessing and feature encoding
- Feedforward neural network for regression
- Handles both numerical and categorical features

---

## ❤️ Heart Disease Prediction

**Folder:** `heartdisease/`

Binary classifier that predicts whether a patient has heart disease based on clinical features.

- Features include age, cholesterol, blood pressure, and more
- Sigmoid output with binary cross-entropy loss
- Evaluated with accuracy, precision, and recall

---

## 🏠 House Price Prediction

**Folder:** `houseprice/`

Predicts house prices using structured real estate data.

- Feature scaling and normalization
- Deep neural network regression model
- Evaluated using RMSE and R² score

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Notebooks:** Jupyter Notebook
- **Deep Learning:** TensorFlow / Keras
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **ML Utilities:** Scikit-learn

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/AnshGajera/Neural_Network_projects.git
   cd Neural_Network_projects
   ```

2. **Install dependencies**
   ```bash
   pip install tensorflow keras pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Run a notebook**
   ```bash
   cd <project_folder>
   jupyter notebook
   ```

---

## 📂 Repository Structure

```
Neural_Network_projects/
├── Cat_Dog_CNN/
├── MNIST_CNN/
├── Walmart/
├── carprice/
├── heartdisease/
└── houseprice/
```

---

## 👤 Author

**Ansh Gajera**  
[GitHub Profile](https://github.com/AnshGajera)

---

## 📄 License

This repository is open source and available for educational purposes.
