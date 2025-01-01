# DL-from-Scratch-Self-Study
Yasuhiko Saito
It's for self-studying on Yasuhiko Saito's book.

## Summary

### Chapter 1: Intro to Python

* Basic Python3 syntax
* Intro to two libraries: NumPy & matplotlib
  * NumPy: Element-wise operations, i.e., +,-,*,/,**; Broadcast: operations between different shapes(vector,matrix,tensor) of array
  * Matplotlib: Data Visualization & Graph

### Chapter 2: Perceptron(1957, Frank Rosenblatt)

* Perceptron has parameters(inputs), weights(W1, W2) and bias(theta/b)
* Inputs have their weights. The more weight one input has, the more important one input is
* XOR: non-linear space(multiple perceptrons); AND, NAND, OR: linear space(single perception)
* We can build a computer by using XOR gate(multi-layer perceptron can express computer, theoretically)
* Advantage: we can express complicated functions via perceptron
* Disadvantage: We need to set parameters, weights, and bias ourselves, not by computer

### Chapter 3: Neural Network

* Activation function will convert ($$\vec{x}$$,w,b)
