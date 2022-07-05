# Cityscapes Image Segmentation

### Semantic Segmentation of Images with Deep Learning


> deep-learning computer-vision cnn encoder-decoder autoencoder unet keras tensorflow


This is an implementation of the pix2pix UNet architecture for image segmentation. 

A UNet is a CNN encoder-decoder architecture where layers in the encoder are connected to corresponding layers in the decoder, ensuring better reconstruction of the input. A pix2pix model combines a UNet and a CNN classifier to form a Generative Adversarial Network. This model yields good results in image segmentation tasks.

---

### Dataset
The dataset used was the [Cityscapes Image Pairs](https://keras.io/api/applications/efficientnet/#efficientnetb0-function) dataset, which was originally built to train Autonomous Self-Driving Cars.

---
### Model
![UNet Architecture](pix2pix%20arch.png)

---
### Sample Outputs
Below are some outputs after training. The left column is the expected translation of the image, the middle column is the input image, and the right column is the translation predicted by the model. These are low-resolution and may be difficult to see. 

> ![Output 1](outputs/1.png)

> ![Output 2](outputs/2.png)

> ![Output 3](outputs/3.png)

> ![Output 4](outputs/4.png)

> ![Output 5](outputs/5.png)

> ![Output 6](outputs/6.png)

> ![Output 7](outputs/7.png)

> ![Output 8](outputs/8.png)


