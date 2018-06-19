---
title: Nengo DL
id_tag: nengo_dl
img: nengo_dl.png
---

I am the author/maintainer of [Nengo DL](https://www.nengo.ai/nengo-dl/introduction.html),
a package that integrates deep learning methods with the [Nengo](#nengo) neural modelling
environment.  Nengo DL allows Nengo models to be optimized using deep learning training 
methods, and improves the simulation speed of Nengo models on CPU or GPU.

Under the hood, Nengo DL is implemented using [TensorFlow](https://www.tensorflow.org/); 
it works by translating a Nengo model description into a symbolic TensorFlow
computation graph.  Nengo DL also allows users to insert TensorFlow code directly into
a Nengo model, allowing for the simulation of a wide variety of neural network architectures 
(such as convolutional neural networks).

* [Download Nengo DL](https://github.com/nengo/nengo-dl) (or `pip install nengo_dl`)
* [Documentation](https://www.nengo.ai/nengo-dl/index.html)
* [White paper](https://arxiv.org/abs/1805.11144)
