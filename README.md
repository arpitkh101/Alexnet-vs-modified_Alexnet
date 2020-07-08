# Alexnet vs modified_Alexnet

## Alexnet Aachitecture
<img src="/architecture/image.png" alt="Alexnet architecture"/>



## Simple Alexnet
- Trained Alexnet on CIFAR-10 dataset using Pytorch initialized with pre-trained weights
- 63% accuracy was obtained from the classification model after training for 10 epochs

## Modifications
- Features were extracted from the 2nd linear layer of the trained model having output dimensions of 4096
- Extracted features were classified using different machine learning models such as Random Forests, K Nearest Neighbours, etc.
- Best classification accuracy of 69% was obtained from Random Forests outperforming simple Alexnet.
