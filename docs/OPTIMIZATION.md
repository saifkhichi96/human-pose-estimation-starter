# Neural Network Optimization

This document describes various optimization methods for neural networks and provides a curated list of resources o help you get started with each technique.

## Pruning

Pruning is a technique for reducing the number of parameters in a neural network by removing the weights of the least important connections. This can be done by setting the weights of these connections to zero, or by removing the connections entirely. Pruning is a form of network compression, and can be used to reduce the size of the model and improve inference speed.

- MIT HAN Lab Lecture on Pruning and Sparsity ([I](https://www.youtube.com/watch?v=sZzc6tAtTrM), [II](https://www.youtube.com/watch?v=fWP3Q6tNtYU))


## Quantization

Quantization is a technique for reducing the precision of the weights and activations in a neural network. This can be done by reducing the number of bits used to represent each weight or activation, or by using a lower precision floating point format. Quantization is a form of network compression, and can be used to reduce the size of the model and improve inference speed.

- MIT HAN Lab Lecture on Quantization ([I](https://www.youtube.com/watch?v=AlASZb93rrc), [II](https://www.youtube.com/watch?v=3nqUFSSJYKQ))


## Neural Architecture Search

Neural architecture search (NAS) is a technique for automatically finding the best neural network architecture for a given task. This can be done by searching over a large space of possible architectures, or by using reinforcement learning to learn the best architecture directly from the data.

- MIT HAN Lab Lecture on Neural Architecture Search ([I](https://www.youtube.com/watch?v=NQj5TkqX48Q), [II](https://www.youtube.com/watch?v=PFitZnPIKoc), [III](https://www.youtube.com/watch?v=_cvn9pflblk))
- [AutoML and Literature on NAS](https://www.automl.org/automl/literature-on-neural-architecture-search/)


## Knowledge Distillation

Knowledge distillation is a technique for training a neural network by distilling the knowledge of a larger, more accurate network into a smaller, less accurate network. This can be done by training the smaller network to mimic the predictions of the larger network, or by training the smaller network to predict the same soft labels as the larger network.

- MIT HAN Lab Lecture on Knowledge Distillation ([I](https://www.youtube.com/watch?v=tT9Lnt6stwA))
- [Awesome Knowledge Distillation](https://github.com/dkozlov/awesome-knowledge-distillation)
- [knowledge-distillation-pytorch](https://github.com/haitongli/knowledge-distillation-pytorch)

## Other Resources

- [Intel® Neural Compressor](https://github.com/intel/neural-compressor)
