# Optimization using PyTorch

The link for [optimization in PyTorch](https://docs.pytorch.org/docs/stable/optim.html).
The algorithms are available in [PyTorch optimization methods](https://docs.pytorch.org/docs/stable/optim.html#algorithms).

## How the image classification methods were trained
The following link describes how PyTorch trained the different classification methods using 8 GPUs, with different batch sizes, learning rates as detailed
in [PyTorch GitHub for vision classification](https://github.com/pytorch/vision/tree/main/references/classification).

## Adjusting the learning rate
The primary website from [Pytorch: Adjusting the learning rate](https://docs.pytorch.org/docs/stable/optim.html#how-to-adjust-learning-rate).
Some important methods include:
* A nice tutorial can be found at [A (Very Short) Visual Introduction to Learning Rate Schedulers (With Code)](https://medium.com/@theom/a-very-short-visual-introduction-to-learning-rate-schedulers-with-code-189eddffdb00)
* [Step learning rate scheduler](https://docs.pytorch.org/docs/stable/generated/torch.optim.lr_scheduler.StepLR.html).
* [Reduce the learning rate when we reach a plateau](https://docs.pytorch.org/docs/stable/generated/torch.optim.lr_scheduler.ReduceLROnPlateau.html). 
