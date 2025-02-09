
# Neural Network Optimization

## Overview
Neural Network Optimization is a Java application designed to model and optimize neural networks. It provides functionality to build a neural network layer by layer, compute outputs given inputs, and find optimal inputs to minimize output magnitude.

## Classes

### `Layer`
This class represents a single layer within a neural network. Each layer contains a set of weights, biases, and an activation function flag (`relu`).

### `NeuralNetwork`
This class models the entire neural network comprising multiple layers. It includes methods to add layers, compute the network output, and perform optimization.

## Usage

### Compiling and Running
The application can be compiled and run using the provided shell script for Unix-like systems or batch file for Windows.

#### Unix-like Systems
Execute the `run_network.sh` script in your terminal:
```bash
./run_network.sh
```

#### Windows Systems
Run the `run_network.bat` file from Command Prompt:
```cmd
run_network.bat
```

### Input File
The application expects a file named `networks.txt` in the current working directory. This file should contain the configuration for one or more neural networks.

### Example `networks.txt` Structure
```
Layers: 1
Rows 1: 1
Cols 1: 1
Weights 1: [[3.0]]
Biases 1: [[4.0]]
Relu 1: false
Example_Input:[[1.0]]
Example_Output:[[7.0]]
```

## Features

- Load neural network configurations from a file.
- Compute neural network output for given inputs.
- Compare computed output with an example output to verify the network's function.

## Requirements

- Java Development Kit (JDK) to compile and run the application.
- Bash shell (for Unix-like systems) or Command Prompt (for Windows systems) to execute the provided script or batch file.




## To-Do List

- [ ] Implement visualization for the neural network architecture and training process.
- [ ] Add gradient descent optimization method.
- [ ] Implement Relu.


