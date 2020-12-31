# Image-Denoising-with-Deep-CNNs

Use deep Convolutional Neural Networks (CNNs) with PyTorch, including investigating DnCNN and U-net architectures. 

## Model Architecture

1. DnCNN



2. UDnCNN


3. DUDnCNN (Dilated U-shaped DnCNN)

Each convolution placed after `k` pooling and `l` unpooling in the network, should be replaced by a dilated filter with 2^(k−l) − 1 holes. This can be achieved with the dilation optional argument of `nn.Conv2d`. Make sure set up the argument padding accordingly to maintain tensors with the same spatial dimension during the forward propagation.



## Testing Environment  

* Pytorch version: `1.0.0`
* CUDA version: `9.0.176`
* Python version: `3.6.8`
* CPU: Intel(R) Xeon(R) CPU E5-2630 v4 @ 2.20GHz
* GPU: GeForce GTX 1080 Ti (11172MB GRAM)
* RAM: 32GB



