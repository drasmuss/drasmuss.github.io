---
title: Keras Spiking
id_tag: keras-spiking
img: keras_spiking.png
img-circle: true
---

I am the lead developer/maintainer of 
[KerasSpiking](https://www.nengo.ai/keras-spiking), a library that makes it easy to 
build spiking deep networks within the [Keras](https://keras.io/) framework. 
With KerasSpiking users do not need to switch to a different library to 
build/train/deploy spiking neural models; they can do it all from within Keras, using 
exactly the same approach they are familiar with for non-spiking models.

KerasSpiking works by wrapping any standard Keras nonlinearity. For example, users can
apply the spiking wrapper to a ReLU activation function, and the result would be
analogous to an Integrate-and-Fire spiking neuron. That spiking layer can then
be freely combined with any other Keras layer, enabling the construction of
complex deep networks containing spiking components. The models can be trained using
any of the standard Keras optimizers (KerasSpiking will use an approximation to
compute the gradients of the spiking neurons that takes into account the discretization
effect of spikes).

* [Download KerasSpiking](https://github.com/nengo/keras-spiking) (or `pip install keras-spiking)
* [Documentation](https://www.nengo.ai/keras-spiking)
* [Read about the underlying theory](https://arxiv.org/pdf/2002.03553.pdf)
