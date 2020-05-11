# GAN_mnist

In this project, I have generated MNIST hand-written digit images, using Deep Convolution GANs.

### Dependencies :
    1. Numpy
    2. Keras
    3. TensorFlow
    4. Matplotlib
    
    
## Model Architecture:

The whole adversarial algorithm uses 3 models :

### Generator :
    Used Up-Sampling layers and Conv2D layers to convert noise vector to (28,28,1) GrayScale image.
    
### Discriminator :
    Conv2D layers perform strided convolutions to generate feature vector, which in turn is used for classification.
    
### Generator Trainer :
    To implement the adversarial game, the discriminator weights need to be fixed. Hence a separate model for generator training is required.
    
    
## Results :

Before:
<br></br>
<img src='https://github.com/Rahul2k/GAN_mnist/blob/master/Before.png' >

After:
<br></br>
<img src='https://github.com/Rahul2k/GAN_mnist/blob/master/After.png' >
