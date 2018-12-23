# NN Approach

## TensorFlow & Keras

### Why use Keras?

**TensorFlow** is one of the most powerful deep learning frameworks. However, its structure is more sophisticated than other deep learning frameworks. **Keras** is a high-level interface for neural networks that run on top of multiple backends. Its functional API is very **user-friendly, yet flexible enough** to build all kinds of applications. Keras quickly gained traction after its introduction and in 2017, the *Keras API* was integrated into core Tensorflow as *tf.keras*. Although *tf.keras* and *Keras* have separate code bases, they are tightly coupled and with the updated documentation and programmer guides as of Tensorflow 1.9, *tf.keras* is clearly **the high-level API to look for when building neural networks with Tensorflow.**

![](appendix/keras.png)
*Source: https://keras.io/why-use-keras/*

## Contents
### 1. Neural Network (Embedding and Simple Fully Connected)
#### a. Data Preparation for NN Model
- Simple Feature Engineering
- Label Encoder
- log1p Transform
- MinMax Scaler
- Saving Processed Data

#### b. NN Model
- Embedding for Categorical Attributes
- Concatenate Layers
- LeakyReLU
- BatchNormalization
- RMSProp
- Kaggle API Submission
- Saving Model

### 2. Long Short-Term Memory (Encoder & Decoder)
#### a. Data Preparation for LSTM Model
- Simple Feature Engineering
- Label Encoder
- log1p Transform
- MinMax Scaler
- Reshaping (samples, timesteps, features)
- Saving Processed Data

#### b. LSTM Model
- Glorot Uniform
- LSTM Encoder & Decoder Parts
- RMSProp
- Predict Mechanism 
- Kaggle API Submission
- Saving Model

### 3. Neural Network Bottleneck Features
- Extract bottleneck features from the trained model for Boosting Methods

## Results

|     Models     | Private Score |  Public Score |
|:--------------:| -------------:| -------------:|
|    NN Model    |     0.529     |     0.486     |
|   LSTM Model   |     0.532     |     0.496     |
  