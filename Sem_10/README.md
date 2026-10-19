# 🧠 Semana 10: Introduction to Neural Networks and the Perceptron

<span class="badge badge-blue">🧠 Neural Networks</span>
<span class="badge badge-green">🔗 Simple Perceptron</span>

---

## 🎯 Objectives

- Understand the fundamental concepts of Artificial Neural Networks (ANNs).
- Explain how artificial neurons process information to make predictions.
- Identify the main components of a neural network: inputs, weights, biases, activation functions, and outputs.
- Understand the architecture and operation of a Simple Perceptron.
- Explain how a perceptron learns by adjusting its weights and bias.
- Recognize the relationship between neural networks, optimization, and Gradient Descent.
- Identify the capabilities and limitations of single-layer perceptrons.

---

## 📌 Topics

- 🧠 Introduction to Artificial Neural Networks
  - What are Artificial Neural Networks?
  - Biological inspiration vs. artificial neurons
  - From traditional Machine Learning to Neural Networks
  - Basic neural network architecture
  - Input, hidden, and output layers
  - Applications of Neural Networks

- 🔗 The Artificial Neuron
  - Input features
  - Weights and their importance
  - Bias
  - Weighted sum
  - Activation functions
  - Producing an output

- ⚡ Activation Functions
  - Why activation functions are necessary
  - Step function
  - Sigmoid
  - ReLU
  - Introduction to nonlinear transformations

- 🎯 The Simple Perceptron
  - Perceptron architecture
  - Binary classification
  - Linear decision boundaries
  - The perceptron prediction process
  - The perceptron learning rule
  - Updating weights and bias
  - Learning from classification errors

- 🔄 How Does a Perceptron Learn?
  - Initialize weights and bias
  - Calculate the weighted sum
  - Apply the activation function
  - Compare predictions with actual labels
  - Calculate the prediction error
  - Update weights and bias
  - Repeat across training examples

- 🚧 Limitations of the Simple Perceptron
  - Linearly separable problems
  - AND and OR classification
  - The XOR problem
  - Why a single perceptron cannot solve nonlinear classification problems
  - Introduction to multilayer neural networks

- ⛰️ Connecting Neural Networks with Optimization
  - Learning as parameter adjustment
  - The role of the learning rate
  - Perceptron learning vs. Gradient Descent
  - From simple learning rules to neural network optimization

---

## 🧠 Activities

- 💬 Discuss how artificial neurons differ from biological neurons.
- 🧩 Identify the components of an artificial neuron using a visual diagram.
- 🔢 Manually calculate the output of a perceptron using inputs, weights, and bias.
- ⚡ Compare the behavior of different activation functions.
- 🎯 Visualize how a perceptron separates two classes using a linear decision boundary.
- 🐍 Implement a Simple Perceptron from scratch using Python and NumPy.
- 🔄 Visualize how the perceptron updates its weights during training.
- 🧪 Train a perceptron to solve the AND and OR logic problems.
- 🚧 Experiment with the XOR problem and discuss why a single perceptron cannot solve it.
- 📊 Compare the perceptron's predictions before and after training.
- 📝 Complete a short quiz about neural networks and perceptron learning.

---

> **💡 Weekly Challenge**
>
> Imagine you want to build a simple artificial neuron that decides whether a student passes or fails a course based on two inputs:
>
> - **Input 1:** Exam performance
> - **Input 2:** Assignment performance
>
> The neuron assigns different weights to these inputs and produces a binary prediction.
>
> **Questions:**
>
> - What do the weights represent in this problem?
> - How does the bias influence the prediction?
> - What is the role of the activation function?
> - How could the perceptron learn from incorrect predictions?
> - Why might a single perceptron be insufficient for more complex decision-making problems?