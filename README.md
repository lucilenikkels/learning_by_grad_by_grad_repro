# Reproduction of Learning to learn by gradient descent by gradient descent 

This optimizer is a reproduction of the paper [learning to learn by gradient descent by gradient descent](https://arxiv.org/pdf/1606.04474.pdf).
The optimizer uses Pytorch and is tested on quadratic functions and MNIST to compare the results from the paper to this code. We replicated the work from AdrienLE (https://github.com/AdrienLE/learning_by_grad_by_grad_repro) and made some improvements.

## Before you start
* Make sure your device has a GPU that supports CUDA.
* Make the project in a Conda environment.
* Use a version of Python 3.6.8 or higher.

## Installation

To install this project run the following commands in your terminal: 

```bash
git clone https://github.com/lucilenikkels/learning_by_grad_by_grad_repro.git
cd learning_by_grad_by_grad_repro
pip install -r requirements
```
Make sure to install latest versions of jupyter and notebook to make sure all images and status bars show.
