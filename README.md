# Deep Learning Course Homeworks

This repository contains the completed homework assignments for the Deep Learning course at SUT, instructed by Dr. Soleymani.


### HW1: Deep Learning Basics
- **Optimization Methods**: 
This notebook explores several optimization methods commonly employed in deep learning tasks and assesses their effectiveness using two test functions.

- **NN From Scratch**:
In this notebook, we will implement fully connected networks using a modular approach. We will implement a `forward` and a `backward` function for each layer. The `forward` function will receive inputs, weights, and other parameters and will return both output and a `cache` object storing data needed for the backward pass. The backward pass will receive upstream derivatives and the `cache` object and will return gradients with respect to the inputs and weights.

- **Pytorch Basics**:
This notebook will walk you through many of the important features of PyTorch.


### HW2: Convolutional Neural Networks
- **Vanilla CNN**: 
In this notebook, we will learn about CNN's basics by working on a problem of great importance in computer vision: classifying images of cats and dogs :).

- **ResNet and U-Net**:
In this notebook, we will implement the `ResNet18` and `U-Net` using PyTorch, and use them for image classification and colorization on the CIFAR10 dataset.

- **YOLO**:
In this notebook, we will implement the YOLO object detection algorithm using PyTorch. YOLO is a real-time object detection system that can recognize multiple objects in an image while also predicting their bounding boxes.


### HW3: RNNs & Transformers
- **RNN**:
In this notebook, we will implement both a vanilla RNN and an LSTM using PyTorch. Additionally, we will develop a sentiment analysis model by simply adding a linear layer to the hidden vector of an LSTM.

- **Simple GPT**:
The objective of this notebook is to create and train a decoder-only model, which is a custom and scaled-down version of GPT, using a dataset consisting of dialogues from the TV series Friends.

- **MLM and Sequence Classification with BERT**:
In this notebook, we use the "rotten_tomatoes" dataset from `HuggingFace`, which contains movie reviews, to perform two tasks: Masked Language Modeling (MLM) and building a classifier to differentiate between positive and negative reviews. We utilize a smaller, customized version of BERT to ensure efficient and feasible training.

To be completed ...