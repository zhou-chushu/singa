# Convolutional Prototype Learning

We have successfully applied the idea of prototype loss in various medical image classification task to improve performance, for example detection thyroid eye disease from CT images. Here we provide the implementation of the convolution prototype model in Singa. Due to data privacy, we are not able to release the CT image dataset used. The training scripts `./train.py` demonstrate how to apply this model on cifar-10 dataset.

## run

At Singa project root directory `python examples/healthcare/application/TED_CT_Detection/train.py`

## reference

[Robust Classification with Convolutional Prototype Learning](https://arxiv.org/abs/1805.03438)
