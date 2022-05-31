# CNN-Manual-Calculation

CNN Manual Calculation using Ms. Excel and PyTorch

This repository is created because of my concern with the existance of modern deep learning libraries in Python (TensorFlow, Keras, PyTorch, etc).
With the current libraries, people can easily and instantly created deep neural network architecture and build the model without need to know the mathematical process behind neural network algorithm.

This repository contains my step-by-step calculation of CNN algorithm in one epoch, from the forward propagation until the weight update of each layers. The data used for this calculation is a simple pre=defined 5x5 Tensor data that created for this specific calculation. The initial weights of each layers also already pre-defined for the calculation purpose.

The PyTorch notebook in this repository is used as a validation of my manual calculation result. The notebook is just a one epoch training using same data, same layer architecture, and same initial weight with my manual calculation. The notebook will print every steps from the calculation, from the forward propagation, loss calculation, backward propagation, and update weight.

In the end, I successfully validates my manual calculation result. My final results from the manual calculation have the same value with the results from PyTorch.
