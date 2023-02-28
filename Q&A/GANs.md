1. What is mode collapse in GANs?
- Sometimes, the generator only generates a handful of sample varieties. This is called mode collapse.

2. DCAGN (Deep Convolutional Generative Adversarial Network):
- To ensure the stable training of GANs on image data
  + Getting rid of fully connected layers and only using convolution layers
  + Using strided convolution layers to perform downsampling, instead of using pooling layers
  + Using ReLU/leakyReLU activation functions instead of Tanh between hidden layers
