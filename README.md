# pcos_prediction
A Deep Learning binary classification model built with Keras/TensorFlow to predict Polycystic Ovary Syndrome (PCOS) using 541 patient clinical and biological health parameters.
## Model Architecture & Details

- **Framework:** TensorFlow / Keras
- **Task:** Binary Classification (PCOS: Yes / No)
- **Model Type:** Multi-Layer Perceptron (MLP) / Artificial Neural Network (ANN)
- **Input Features:** 40+ clinical parameters (BMI, Hormone Levels, Cycle Length, Follicle Count, etc.)
- **Activation Functions:** 
  - Hidden Layers: `ReLU`
  - Output Layer: `Sigmoid` (for binary probability output)
- **Loss Function:** `binary_crossentropy`
- **Optimizer:** `Adam`
