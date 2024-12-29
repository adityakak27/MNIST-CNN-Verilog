# MNIST-CNN-Verilog

*FPGA-Based CNN for MNIST Digit Recognition*

A fully synthesizable implementation of a Convolutional Neural Network (CNN) in Verilog for inference, designed for FPGA deployment. This project achieves 95% accuracy on the MNIST handwritten digit recognition dataset.

# Overview

This project implements CNN inference in hardware, demonstrating how modern machine learning algorithms can be efficiently deployed on FPGA platforms. The design uses pre-trained weights and biases loaded through .mif files, focusing purely on the inference stage of the neural network.


![Image Title](https://github.com/adityakak27/MNIST-CNN-Verilog/blob/main/Web_Photo_Editor.jpg)



# Features

High Accuracy Implementation: Achieves around 95% accuracy on the MNIST handwritten digit recognition dataset for 1000 samples, whereas the accuracy is closer to 98% at smaller batch sizes (~100)

Complete Hardware Design: Neural network architecture fully implemented in Verilog:

Layers, neurons and activation function modules implemented 

Fully synthesizable codebase

Validated through behavioral simulations

Pre-trained weights and biases loaded through .mif files


The entire implementation is done purely in hardware description language (Verilog), demonstrating the capability of processing neural networks directly on FPGA hardware without requiring external processors or software layers.
