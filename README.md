# Image Colorization

Deep learning models for grayscale-to-color image translation

![Demo](./Code/demo.png)

## Problem

- Colorizing gray-scaled images is a challenging task because a single gray value can correspond to multiple possible color
- Color values must be realistic and reasonable

## Solution

- Design a Resnet-18 encoder - Unet decoder architectures to preserve spatial information
- Applies GAN-based models to generate more realistic and vivid colors

## Tech
- Python
- PyTorch
- Resnet, U-net, GAN

## Result
<p align="center">
  <b>Before</b><br>
  <img src="Code/before.png" width="400"><br><br>
  <b>After</b><br>
  <img src="Code/after.png" width="400">
</p>
