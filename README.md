# condconv.pytorch

PyTorch implementation of Conditional Convolution in [CondConv: Conditionally Parameterized Convolutions for Efficient Inference](https://arxiv.org/abs/1904.04971).

<p align="center"><img src="fig/condconv_layer.png" width="600" /></p>

* CondConv layer and CondConv-equipped MobileNetV2 is supported (pre-trained model release is not in the recent plan).
* Dynamic batch inference is supported (implemented by group convolution).

# Citation

```bibtex
@incollection{NIPS2019_8412,
title = {CondConv: Conditionally Parameterized Convolutions for Efficient Inference},
author = {Yang, Brandon and Bender, Gabriel and Le, Quoc V and Ngiam, Jiquan},
booktitle = {Advances in Neural Information Processing Systems 32},
editor = {H. Wallach and H. Larochelle and A. Beygelzimer and F. d\textquotesingle Alch\'{e}-Buc and E. Fox and R. Garnett},
pages = {1307--1318},
year = {2019},
publisher = {Curran Associates, Inc.},
url = {http://papers.nips.cc/paper/8412-condconv-conditionally-parameterized-convolutions-for-efficient-inference.pdf}
}
```

