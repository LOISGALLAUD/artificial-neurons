# **Artificial Neuron Network**

### In this repository you will find Jupyter Notebooks containing the note i took from online ressources and code to build a **Perceptron** and a **Artificial Neuron Network** from scratch using Python.

---

## **Artificial Neuron Network**

**Artificial neurons** are the basic unit of a neural network and are the building blocks of **neural networks**. They are inspired by the biological neurons in the human brain.

|<img src="https://www.tibco.com/sites/tibco/files/media_entity/2021-05/neutral-network-diagram.svg" align="right" width=500>|
|:---:|
|**Artificial Neuron Network**|


They take in a set of inputs, perform some calculations on them and produce an output. The output is then passed to the next layer of neurons, and so on.
* The first layer of neurons is called the input layer.
* The last layer of neurons is called the output layer.
* The layers in between are called hidden layers. The number of hidden layers and the number of neurons in each hidden layer is a hyperparameter.

The number of neurons in the input layer is determined by the number of features in the dataset and the amount of neurons in the output layer is determined by the number of classes in the dataset.

---

## **Perceptron**

In machine learning, the **perceptron** (or McCulloch-Pitts neuron) is an algorithm for supervised learning of **binary classifiers**. A binary classifier is a function which can decide whether or not an input, represented by a vector of numbers, **belongs to some specific class**. It is a type of linear classifier, i.e. a classification algorithm that makes its predictions based on a linear predictor function combining a set of weights with the feature vector.

The perceptron algorithm dates back to the late 1950s and was the first **neural network** implemented in a computer system. It was intended to be a machine implementation of a **neuron** in a human brain. In the modern sense, the perceptron is an algorithm for learning a binary classifier called a threshold function: a function that maps its input **x** (a real-valued vector) to an output value **f(x)** (a single binary value).
**w** is a vector of real-valued weights, **w · x** is the dot product **∑i wi xi**, where **xi** is the **i**th element of **x**, and **b** is the bias. The bias shifts the decision boundary away from the origin and does not depend on any input value.

|<img src="https://i0.wp.com/datascientest.com/wp-content/uploads/2021/04/perceptron-formule.webp?fit=768%2C290&ssl=1" align="right" width=500>|
|:---:|
|**Perceptron**|

By repeatedly assiociating perceptrons together, we can create a network of perceptrons. This network is called a **neural network**.

---

[Loïs GALLAUD](https://github.com/LOISGALLAUD) - 2023