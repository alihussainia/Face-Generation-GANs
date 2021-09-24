# Face-Generation-GANs

## Introduction
In this project, you'll use generative adversarial network DCGAN on a dataset of faces to generate new images of faces that look as realistic as possible!

The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, you'll be able to visualize the results of your trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.

<img src="https://video.udacity-data.com/topher/2018/November/5beb234e_processed-face-data/processed-face-data.png" />

<p align=center> <b>Processed CelebA face data.</b> </p>

## Getting the dataset

You'll be using the  <a href="http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html">CelebFaces Attributes Dataset (CelebA) </a> to train your adversarial networks.

This dataset is more complex than the number datasets (like MNIST or SVHN) you've been working with, and so, you should prepare to define deeper networks and train them for a longer time to get good results. It is suggested that you utilize a GPU for training. It contains over 200,000 celebrity images with annotations.
