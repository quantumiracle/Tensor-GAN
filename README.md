# Tensor Sparse Coding

- [1] F. Jiang, X.-Y. Liu, H. Lu, R. Shen. Efficient multi-dimensional tensor sparse coding using t-linear combinations. AAAI, 2018.

- The version of Python is in the repository `./2DSC`. Please run `main.py` to start. And the version of Tensorflow is in the repository `./2DSC/tensorflow`. Please run `train.py` to start. 

![image](https://github.com/hust512/Tensor-GAN/blob/master/pics/balloon_sc_result.png)

<div align=center>Figure 1. The experiment of tensor sparse coding.</div>

# Tensor GAN

## Introduction
- The codes are in the repository `./TGAN`.

## Architechture
<div align=center><img width="800" src="https://github.com/hust512/Tensor-GAN/blob/master/pics/arch.jpg"/></div>

<div align=center>Figure 2. The architechture of tensor GAN.</div>

<div align=center><img width="600" src="https://github.com/hust512/Tensor-GAN/blob/master/pics/dict.png"/></div>
<div align=center> Figure 3. The tensor dictionary.</div>

## Experiment
We have tested the high-quality image generation from a low-resolution image via tensor combined dictionary.

<div align=center><img width="400" src="https://github.com/hust512/Tensor-GAN/blob/master/pics/balloons_sr_result.png"/></div>

And the following pictures are the generated handwritten numbers from latent representations.

<div align=center><img width="400" src="https://github.com/hust512/Tensor-GAN/blob/master/pics/mnist.png"/></div>
