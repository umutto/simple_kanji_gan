# simple_kanji_gan
Generating new Kanjis with keras using DCGAN in [Unsupervised representation learning with deep convolutional generative adversarial networks](https://arxiv.org/pdf/1511.06434.pdf) paper.


---
**Note:** For some reason I can't find a set of working hyperparameters. Started with the original hyper parameters, but did not work out. Currently testing it on MNIST dataset to make sure it is not domain dependant. Also although loss values point to bad hyper-parameter settings (d is converging so fast, g can not get any gradient updates etc...) my implementation may also be the problem. Currently this implementation does not work.
