---
title: Deep learning 
id: hessianfree
img: hessianfree.png
---

I am the author of the [hessianfree](https://github.com/drasmuss/hessianfree)
software package, which provides tools for training feedforward and recurrent
deep networks using [Hessian-free optimization](http://www.cs.toronto.edu/~jmartens/docs/Deep_HessianFree.pdf).  Hessian-free
is a powerful second order optimization method that has produced state-of-the-art
results in deep learning (particularly in the case of recurrent networks).  However, 
its main downside is its complexity -- it is difficult to implement, 
and therefore difficult to customize for a given application.

The `hessianfree` package is designed to make Hessian-free optimization
more accessible to anyone that wants to work with it.  It provides a simple
interface for building and training networks, and makes it easy to modify
the system (e.g., using custom nonlinearities, connectivity, or loss 
functions) without having to get involved in the internals of the optimization 
process.

* [Download the package](https://github.com/drasmuss/hessianfree)
* [Documentation](http://pythonhosted.org/hessianfree/)
