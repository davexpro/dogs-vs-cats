## Dogs Vs. Cats

Competition: [Dogs vs. Cats Redux: Kernels Edition](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition)

Dogs Vs. Cats is a great case to learn how to use a deep-learning framework such as PyTorch, thus, I create this repo to record how I learn PyTorch.

There are two kind of methods to get the job done, one is `transfer learning`, another is to train on the features extracted by some nice pre-trained models.

## Transfer Learning

In this case, I use ResNet-152 to do the transfer learning which is easy to do, and get `0.05304` score as test result.

There are some great materials we can use:

[Transfer Learning tutorial - PyTorch Tutorial](http://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html)

[pytorch-cat-vs-dogs - GitHub Repo](https://github.com/desimone/pytorch-cat-vs-dogs/)

Based on materials above, we successfully completed transfer learning and get a moderate result.

## Feature Extraction

In this case, to do.

## Problem Encountered

### Train / Test Split

https://gist.github.com/kevinzakka/d33bf8d6c7f06a9d8c76d97a7879f5cb

### Multi-GPU Training

https://github.com/pytorch/examples/blob/master/imagenet/main.py#L85

http://pytorch.org/tutorials/beginner/former_torchies/parallelism_tutorial.html

## License

MIT License

Copyright (c) 2018 Dave Fang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
