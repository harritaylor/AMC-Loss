_______
# AMC-Loss: Angular Margin Contrastive Loss for Improved Explainability in Image Classification

## Overview
This is re-implementation of the AMC loss described in: [paper](https://arxiv.org/pdf/2004.09805.pdf)

## Requirements
* tensorflow>=1.12.0
* python>=3.6.0

## Image Classification
We use CIFAR10 classification as an example with a simple architecture. In order to reproduce the results described on the paper, please modify the hyperparameters in Train_AMC.py and then run python Train_AMC.py The users can also change the data to other dataset at their interest. This code contains visualization by Grad-CAM from here [https://github.com/Ankush96/grad-cam.tensorflow] and tSNE plot. 

## Visualization

Baseline model             |  AMC model
:-------------------------:|:-------------------------:
<img src="result/cifar10/Baseline/result_baseline.png" width="400">  |  <img src="result/cifar10/AMC/result_amc.png" width="400">
