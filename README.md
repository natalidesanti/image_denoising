# A mini tutorial on Image Denoising Techniques

The goal of **image denoising** is to recover a _clean version_ of an image $x$ from a _noisy observation_ $y$, 
whith _noise_ $\nu$. 
Mathematically, this relationship is described by:
\begin{equation}
 y = x + \nu
\end{equation}
An _image denoiser_ should be able to produce a cleaned version $\hat{x}$ that closely resembles the original clean 
image $x$, by effectively reducing the noise present in the observed image $y$.

In this tutorial we pass through **traditional** to more **sophisticated** image denoising techniques.

I will show how to work with the handwritten digits from [MNIST](https://keras.io/api/datasets/mnist/),
to include a **Gaussian noise** on their images, and build a series of methods to denoise those images.

## Material

Here you can find:
* An introduction on image denoising with examples of traditional filters
* A Multi Layer Perceptron Autoencoder Denoiser
* A Convolutional Neural Network Autoencoder Denoiser
* Variational Autoencoder Denoiser

## References and supplementary material

[1] FAN, L. et al. Brief review of image denoising techniques. Visual Computing for Industry, Biomedicine, and Art, v. 2, 2019.

[2] Tian, C. et al. Deep Learning on Image Denoising: An overview. arXiv e-prints, p. arXiv:1912.13171, dez. 2019.

[3] Chollet, F. [Building Autoencoders in Keras](https://blog.keras.io/building-autoencoders-in-keras.html)

[4] de SANTI, N. S. M. Machine learning methods for extracting cosmological information. 2024. doi: [10.11606/T.43.2024.tde-15072024-101341](https://www.teses.usp.br/teses/disponiveis/43/43134/tde-15072024-101341/en.php).

## Contributing
Pull requests are welcome!

## License
[GNU](https://choosealicense.com/licenses/gpl-3.0/)
