---
title: BackPropagation
author: Arya Bhattarai
  - 211617
theme:
  name: terminal-light
---

Backpropagation
===

<!--end_slide-->

Introduction
===

<!--pause-->
## What it is

- a method for computing the gradient

<!--pause-->
## What it is not

- not the complete algorithm through which neural networks learn

<!--end_slide-->
History
===


1. The underlying calculus, the **chain rule** was invented in the 17th century by Leibniz 

2. Gradient Descent was first used as a technique for iteratively approximating the solution to optimization problem in the 19th century

3. Geoffrey Hinton, David E. Rumelhart, Ronald J. Williams introduced the
  Backpropagation algorithm in their paper
  `Learning Representations by Back-Propagating Errors`

<!--end_slide-->
Significance
===
-


<!--end_slide-->
Architecture
===
-


<!--end_slide-->
Mathematical Model
===
- dL/dy = dy/dw


<!--end_slide-->
Algorithm
===
<!--incremental_lists: true-->
1. initialize weights and biases
2. perform forward pass
3. calculate error/loss
4. perform backward pass to compute gradients
5. update weights and biases using gradient descent
6. repeat 2-5 until convergence


<!--end_slide-->
Source Code
===
-


<!--end_slide-->
Application Areas
===
Backpropagation is an algorithm used to train all kinds of neural networks,
which are used in:

- Image Recognition (CNNs)
- Natural Language Processing (RNNs)
- Finance
- Healthcare


<!--end_slide-->
References
===
1. Rumelhart, D. E., Hinton, G. E., Williams R. J., _Learning representations by
   back-propagating errors_
2. "Deep Learning" by Ian Goodfellow, Yoshua Bengio, and Aaron Courville
