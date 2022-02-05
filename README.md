# Image-Classification-on-CIFAR-100

## Data and File Description

For data used in Hand Made Model: The files can be downloaded from https://www.kaggle.com/c/sjsu-cmpe-258-fa21-lab1/data

For data used in Transfer Learning Model: The files can be downloaded from https://www.kaggle.com/c/sjsu-cmpe-258-fa21-lab1-t/data

The data consists of 32x32 RGB image each represented as an array of 3072 elements between 0 and 255. To reassemble the images, each 3072 long array can be directly reshaped into a (32,32,3) matrix.

## Implementation

1. Hand Made Deep Convolutional Neural Network
2. Transfer Learning

## Results

Achieved the following accuracies:

A. Hand Made Model:
1. Train accuracy: 0.9614
2. Validation accuracy: 0.5080
3. Test accuracy: 0.49333

B. Model using Transfer Learning:
1. Train accuracy: 0.7138
2. Validation accuracy: 0.4390
3. Test accuracy: 0.4400

## Startup:
1. Download the .ipynb file.
2. Open the file in Google Colab.
3. Download the kaggle .json file (API KEY) and upload it in *cell 2*. 


## Requirements:
1. Python 3.7 or higher.
2. Tensorflow 2 or higher.
3. pip version 19.0 or higher.
4. GPU: NVIDIA Tesla K80 or higher.

## Note:
1. Takes time to train the model.
