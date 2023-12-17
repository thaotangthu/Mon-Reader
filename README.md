This project is to predict if the page is being flipped using a single image.

A regular CNN model with Bayesian Optimization and a vision transformer (VGG16) are executed, however, since the dataset is small in size, the power of vision transformer is not clearly noticeable.
**0.95** and **0.98** are the accuracy scores achieved by CNN and VGG16, and both models all gain f1 scores of **>=0.94** on two classes. In terms of computation effort, VGG16 is more efficient.
