# Micrograd from Scratch

A minimal, fully self-contained implementation of an automatic differentiation engine and neural network framework, built from first principles in Python.

---

## Overview

This project reimplements the core ideas behind modern deep learning systems in a highly simplified setting. It focuses on scalar-based automatic differentiation and backpropagation, providing an intuitive understanding of how neural networks learn.

The implementation is inspired by educational work in deep learning and is designed to prioritize clarity over performance.

---

## Features

* Scalar-valued automatic differentiation
* Dynamic computation graph construction
* Backpropagation via reverse-mode autodiff
* Simple neural network components (neurons, layers, MLP)
* Minimal dependencies (pure Python)



## Project Structure

* `micrograd.py` — core implementation of the Value class and autodiff engine
* `demo.ipynb` — examples and experiments demonstrating training and gradients

---

## Motivation

This project is part of a broader effort to build a deep, mechanistic understanding of machine learning systems.

In particular, it supports a transition toward **AI safety and interpretability research**, where understanding how models internally compute and represent information is essential.

---

## Learning Goals

* Understand backpropagation at a fundamental level
* Build intuition for computation graphs and gradients
* Develop a foundation for interpretability and model analysis

---

## Limitations

* Not optimized for performance or large-scale models
* Operates on scalar values (not tensors)
* Intended for educational and conceptual purposes only

---

## Future Work

* Extend to vector/tensor operations
* Add visualization of computation graphs
* Explore simple interpretability experiments on trained models

---

## Acknowledgments

Inspired by educational materials on neural networks and automatic differentiation.

---

## License

MIT License
