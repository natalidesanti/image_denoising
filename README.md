# A simple example of an image denoising

**Image denoising** is a simple example of an autoencoder, using [MNIST](https://keras.io/api/datasets/mnist/) dataset, inspired into Francois Chollet [tutorial](https://blog.keras.io/building-autoencoders-in-keras.html).


## What is an image denoising?

An **image denoising** is an algorithm that learns _what_ is noise (in some _noisy image_) and _how_ to remove it, based into the _true signal_ / _original_ (image without noisy). The results are images very close to the true ones.

## Image denoising using autoencoders

**Autoencoders** are based on _Neural Networks (NNs)_ and are known as **Convolutional Neural Networks** (**CNNs** or **convnets**). A **convnet** is a __Deep Learning algorithm__ which takes an input image, assign importance (learnable weight, biases and retains spatial relationships in the data into each one of theirs layers) to various aspects/parts in the image and is able to differentiate/reconstruct the same.

The **autoencoder** compreehends an _encoder_ and a _decoder_. The **encoder** does the _encoding process_, i.e., transforms the image into a _compressed representation_ at the same time that starts the noisy reduction. Then, the _compressed representation_ goes to **decoder** that performs the _decoder process_, restoring the image to its true and recognizable shape. At the end of the process, we remove almost all noise in the image.

## Contributing
Pull requests are welcome!

## License
[GNU](https://choosealicense.com/licenses/gpl-3.0/)
