# residual-learning-for-matconvnet

This is a implementation of residual learning (http://arxiv.org/abs/1512.03385) in matconvnet.

In this implementation, we presented 20/110 layers residual nets.

We got 8.82% test error in CIFAR-10, and it was very close to 8.75% test error in original paper.

![Training and Test error curve](http://i.imgur.com/xZbQAs1.png)

Usage:

1. Please install matconvnet ( https://github.com/vlfeat/matconvnet ), my version is beta17

2. Download those files and run cnn_cifar.m 
