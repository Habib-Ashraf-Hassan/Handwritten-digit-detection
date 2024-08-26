# Handwritten-digit-detection
A project done on Handwritten digit detection to better understand ANN in Deep learning
## Some short notes
## Artficial Neural Network (ANN)
Neural network works similar to a brain, takes input somewhere, send it then decide what decision to take

### A neuron
Is made of functions:
- y = m*x + c: _Submission layer_
- z = 1 / (1 + e^-y): _Activation Function_

A problem where we wish to determine if someone has insurance or not, depending on someone's age

Here:
the _Age_ will be the _input_ and goes to the first part of the neuron(y = m*x + c)...m-part is the **weights** and c-part is the **Bias**
Then we get the value of y, then move to the activation function
and we calculate z-value, and check the ouput.
if z value(Activation value) is between 0 <= z < 0.5 then it is in **Inactive state / Off/ 0**

else if value is between 0.5 <= z <= 1 then it is in **Active state/ On/ 1**

**Weights**: the chances, strength of belief of how that feature affects to determine the output, the confidence in that feature

The more the neurons the more the accuracy, the more the hidden layers the more the accuracy

To see more projects on deep learning: **Go to Pantech solutions**

## Practical Implementation
## ANN project on Handwritten digit detection

### Libraries include:
- Tensorflow
- Keras

Deep learning is normally done on GPUs not CPUs, nowadays Tensorflow does contain Keras.
