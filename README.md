# ML-TinyVGGModel

## Descrition
Image classification from the FashionMNIST dataset using the TinyVGG model in PyTorch

## Implementation

Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. 

Each training and test example is assigned to one of the following labels:

    0 T-shirt/top
    1 Trouser
    2 Pullover
    3 Dress
    4 Coat
    5 Sandal
    6 Shirt
    7 Sneaker
    8 Bag
    9 Ankle boot

Model is implemented using PyTorch. You can see architecure of the model on this [link](https://poloclub.github.io/cnn-explainer/).

This CNN consists of 2 convolutional blocks and one classifier block:
  1. Convolutional block 1:
        * Conv2D
        * ReLU
        * Conv2D
        * MaxPool2D
   2. Convolutional block 2:
        * Conv2D
        * ReLU
        * Conv2D
        * MaxPool2D
   3. Classifier block:
        * Flatten layer
        * Linear

## Author
- [@BrankoTrifkovic](https://www.linkedin.com/in/branko-trifkovic/)
