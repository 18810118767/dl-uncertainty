## Uncertainty in Deep Learning
Some code (TensorFlow) based on the paper:

A Kendall, Y Gal, “**What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision?**”, NIPS 2017 [arXiv](https://arxiv.org/abs/1703.04977)

__DISCLAIMER:__ This is __NOT__ the official repo. It is just based on my understanding of the paper. **Any feedback is welcome.**

I am training a simple autoencoder (regression) to reconstruct MNIST digits.

### Getting MNIST

Download MNIST:

`
./download.sh
`

Rescale and save in a python dictionary (possibly resize):

`
python prepro.py
`

## License
This repository is released under the MIT LICENSE.
