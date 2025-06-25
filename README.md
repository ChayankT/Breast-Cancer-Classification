# Breast Cancer Classification using Neural Networks

This project uses a neural network built with TensorFlow/Keras to classify tumors in the Breast Cancer Wisconsin dataset as **malignant** or **benign**. The model is trained on features extracted from cell nuclei in digitized images of breast masses.

## 📌 Dataset
- **Source**: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)
- **Features**: 30 numeric features describing characteristics of the cell nuclei.
- **Target**: Binary classification (0 = Malignant, 1 = Benign)

## 🧠 Model Architecture
- Input layer: 30 features
- Hidden layers: 
  - Dense(64, ReLU) + Dropout
  - Dense(32, ReLU)
- Output layer: Dense(1, Sigmoid)
- Loss function: Binary Crossentropy
- Optimizer: Adam

## 📊 Evaluation Metrics
- Accuracy on test data
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- ROC Curve and AUC Score

## ✅ Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/breast-cancer-nn.git
cd breast-cancer-nn

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Breast_Cancer_Classification.ipynb
