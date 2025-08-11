# Handwritten_Digit_Recognition
Recognising handwritten numerical digits using deep neural networks.

This project uses a neural network built with TensorFlow/Keras to classify handwritten digits (0–9) from the MNIST dataset.

## Overview
- **Dataset:** MNIST (28x28 grayscale images of digits)
- **Model:** Fully connected neural network
- **Training Accuracy:** >99%
- **Test Accuracy:** >97%

## Model Architecture
1. Flatten layer (28x28 → 784)
2. Dense layer with 512 neurons and ReLU activation
3. Regularization techniques like EarlyStopping.
4. Dense output layer with 10 neurons.
5. Activations functions like sigmoid and softmax are used.


## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Jatinredhu/Handwritten_Digit_Recognition.git
3. Install dependencies:
   pip install -r requirements.txt
4. Open digit_recognition_ml.ipynb in Jupyter Notebook or Google Colab.
5. Run all cells — the MNIST dataset will be downloaded automatically.

""digit_recognition_model.keras" is the saved trained model that you can use directly without retraining."





