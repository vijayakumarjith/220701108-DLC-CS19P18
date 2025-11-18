🧠 Deep Learning — Concepts & Experimental Overview

This repository contains implementations and experiments based on Deep Learning, covering the essential concepts required for understanding, training, evaluating, and optimizing neural network models.

🔍 What is Deep Learning?

Deep Learning is a sub-field of Machine Learning that uses artificial neural networks with multiple layers to automatically learn representations from data.
It is widely used in computer vision, NLP, recommendation systems, autonomous driving, speech recognition, and more.

🧩 Core Concepts Included
1️⃣ Artificial Neurons & Perceptron

Mathematical model of a biological neuron

Computes weighted sum + bias

Output passed through activation function

2️⃣ Neural Network Architecture

Input Layer – raw data

Hidden Layers – pattern extraction

Output Layer – prediction

Models implemented: ANN, CNN, RNN (based on experiment)

3️⃣ Forward Propagation

Data flows layer by layer

Each layer transforms inputs

Final output is generated

4️⃣ Activation Functions

Used to introduce non-linearity:

ReLU

Sigmoid

Tanh

Softmax

5️⃣ Loss Functions

Measure prediction error:

Mean Squared Error (MSE)

Binary & Categorical Cross-Entropy

6️⃣ Backpropagation

Computes gradients of loss

Updates weights using Gradient Descent

Formula:

W_new = W_old - learning_rate * dL/dW

7️⃣ Optimizers

Used to speed up learning:

SGD

Adam

RMSProp

Momentum

8️⃣ Data Preprocessing

Normalization

Standardization

One-hot encoding

Train-Test split

9️⃣ Model Evaluation

Accuracy

Precision / Recall / F1-score

Confusion Matrix
