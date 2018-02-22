Continual Learning using auto-encoders
One of the most important unsolved issues in Machine Learning is learning concepts incrementally. For this project we will try a novel idea of creating auto-encoders to detect if there has been a change in the setting we find ourselves in.

Target Journal/Conference: IEEE Transactions on Neural Networks and Learning Systems

References:

Keras Autoencoder
Kirkpatrick, James, et al. "Overcoming catastrophic forgetting in neural networks." Proceedings of the National Academy of Sciences (2017): 201611835.
Goodfellow, Ian J., et al. "An empirical investigation of catastrophic forgetting in gradient-based neural networks." arXiv preprint arXiv:1312.6211 (2013).
Data:

MNIST dataset
CIFAR10 dataset
Tasks

Create three or more tasks of MNIST digits by permuting the pixels (i.e shuffling the images) in a fixed way for each task and save the new datasets in a file. Do the same with CIFAR10 data.
Instantiate n of keras/neural network autoencoders and associate an instance of a classifier with each one.
Send data in batches and pick the auto-encoder with the lowest error - train the autoencoder and the associated classifier with that batch.
Evaluate the setup in all tasks.
Redo the above experiment with an increased amount of autoencoders (n + 1).
Create new autoencoders on the fly if all the the already instantiated autoencoders errors are too high.
