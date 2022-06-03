---
title: Keras LMU
id_tag: keras-lmu
img: lmu.png
img-circle: true
---

I am the maintainer of [KerasLMU](https://www.nengo.ai/keras-lmu), an
implementation of 
[Legendre Memory Units](https://proceedings.neurips.cc/paper/2019/file/952285b9b7e7a1be5aa7849f32ffff05-Paper.pdf)
for the [Keras](https://keras.io/)/[Tensorflow](https://www.tensorflow.org/) framework.
KerasLMU provides an optimized implementation of LMUs within the standard Keras
RNN layer API, allowing LMUs to be integrated into any Keras model.

Legendre Memory Units (LMUs) are a new type of recurrent neural network architecture
that can offer provably optimal representation of time-series information. The theory
underlying LMUs is complex, but KerasLMU encapsulates that complexity in order to 
provide components that can be used as a drop-in replacement for things like LSTMs or 
GRUs. This makes it easy for users to explore the advantages of LMUs, using the same
modelling approaches they are already familiar with.

* [Download KerasLMU](https://github.com/nengo/keras-lmu) (or `pip install keras-lmu`)
* [Documentation](https://www.nengo.ai/keras-lmu)
* [Learn more about LMUs](https://proceedings.neurips.cc/paper/2019/file/952285b9b7e7a1be5aa7849f32ffff05-Paper.pdf)
