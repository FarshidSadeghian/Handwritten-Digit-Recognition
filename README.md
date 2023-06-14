This project is an implementation of a handwritten digit recognition system using two fully connected artificial neural networks, built from scratch with the Numpy package. The project utilizes the MNIST dataset, which can be found at the following link: [MNIST Dataset](http://yann.lecun.com/exdb/mnist/).

## Overview

The project consists of two different implementations of fully connected artificial neural networks:

1. An implementation using iteration on matrices.
2. An implementation using Numpy matrices multiplication.

Both implementations are trained using stochastic gradient descent (SGD) to update the model parameters.

## Requirements

- Python 3.x
- Numpy

## Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/handwritten-digit-recognition.git
```

2. Install the required packages:

```
pip install -r requirements.txt
```

## Usage

1. Download the MNIST dataset from the [official website](http://yann.lecun.com/exdb/mnist/) and extract the files into the `data` folder.

2. Train the model using one of the two implementations:

- For the iteration on matrices implementation, run:

```
python train_iteration.py
```

- For the Numpy matrices multiplication implementation, run:

```
python train_numpy.py
```

3. After training, the model will be saved in the `models` folder.

4. To test the model on the test dataset, run:

```
python test.py
```

## Results

The performance of the model can be evaluated using various metrics such as accuracy, precision, recall, and F1-score. The results will be displayed after testing the model on the test dataset.
