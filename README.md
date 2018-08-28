# MNIST

## Goal:
Given the image of a handwritten digit, recognise it.



## Data:
MNIST dataset was used.

It consisted of 60,000 train samples and 10,000 test samples, with 10 classes ranging from 0 to 9.



## Model:
A 5-layer convolutional neural network was designed as follows:
2 convolutional layers, 1 dense layer and 1 output layer.

Categorical crossentropy loss with adam optimizer was used.

Validation data of 10% of the train data was used during the training process.



## Result:
After 50 epochs,
- Train accuracy: 99.77%
- Validation accuracy: 99.43%
- Test accuracy: 99.52%

- ROC-AUC score: 0.999978
