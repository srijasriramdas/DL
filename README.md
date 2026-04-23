# DL

Deep Learning Lab – 
Assignment (Fashion MNIST)

## Overview
This project implements various Deep Learning models and techniques using the Fashion MNIST dataset. It includes Perceptron, MLP, CNN, optimization methods, regularization techniques, autoencoders, and sequence models.

## Dataset
Dataset: Fashion MNIST
Image Size: 28 × 28 (grayscale)
Classes: 10 categories

---
### Week-wise Implementation and Observations

## Week 1–3: Perceptron and MLP

Observations:

Learning rate significantly affects performance
High learning rate leads to unstable training
Low learning rate results in slow convergence
Best learning rate is around 0.001
Increasing epochs improves accuracy initially but may cause overfitting
Proper selection of hidden layers improves performance

## Week 4: Optimization Techniques
Optimizers used:

SGD
Momentum
Nesterov
Adagrad
RMSProp
Adam
Observations:

SGD converges slowly and is less stable
Momentum improves convergence speed
RMSProp stabilizes training
Adam gives the best overall performance

## Week 5: Regularization Techniques
Techniques used:

L2 Regularization
Dropout
Early Stopping
Noise Injection
Data Augmentation
Ensemble
Observations:

Dropout effectively reduces overfitting
L2 improves generalization
Early stopping prevents unnecessary training
Ensemble methods provide the best accuracy

## Week 6: CNN Implementation
Observations:

CNN performs better than MLP for image data
Convolution layers extract spatial features
Pooling reduces dimensionality and computation
Accuracy improves significantly compared to MLP

## Week 7: Pre-trained Architectures
Models used:

LeNet
AlexNet
VGG
Observations:

Deeper models perform better
VGG provides the highest accuracy
LeNet is simpler but less accurate

## Week 8: Advanced Architectures
Models used:

Inception
ResNet
Observations:

Inception captures multi-scale features
ResNet avoids vanishing gradient problem
ResNet provides better performance and stability

## Week 9: Feature Map Visualization
Observations:

Early layers detect edges and simple patterns
Deeper layers detect complex features
CNN automatically learns hierarchical representations

## Week 10: Guided Backpropagation
Observations:

Highlights important pixels influencing predictions
Helps in understanding model decisions
Improves interpretability of CNN

## Week 11: Autoencoders
Types implemented:

Undercomplete
Overcomplete
Denoising
Sparse
Observations:

Undercomplete autoencoder compresses data
Denoising autoencoder removes noise effectively
Sparse autoencoder learns important features


## Final Conclusion
CNN performs best for image classification tasks
Adam optimizer provides the best performance
Regularization is essential to prevent overfitting
Deeper architectures improve accuracy
Attention-based models enhance sequence learning
Result Summary
Model	Performance
Perceptron	Low
MLP	Moderate
CNN	High
VGG/ResNet	Very High
Final Statement
Deep Learning models achieve high performance when properly tuned. CNN and advanced architectures significantly improve accuracy on image datasets like Fashion MNIST.
