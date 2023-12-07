This is code for the Final Project ECE 8803 by Mehak Arora

It is largely based on two github repositories:

1. https://github.com/BIRD-TAO/GNTPP/tree/main
2. https://github.com/ksharmar/AMDN-HAGE-KDD21/tree/master

To Run Experiments use the Interactive.ipynb notebook

{dataset} can be replaced by `[mooc, retweet, stackoverflow, yelp, synthetic_n5_c0.2, sepsis]`.

{encoder} can be replaced by `[LSTM, Attention]`.

{decoder} can be replaced by `[CNF, Diffusion, GAN, ScoreMatch, VAE, LogNorm, Gompt, Gaussian, Weibull, FNN, THP, SAHP]`.


References:

```
@article{
lin2022GNTPP,
title={Exploring Generative Neural Temporal Point Process},
author={Haitao Lin and Lirong Wu and Guojiang Zhao and Pai Liu and Stan Z. Li},
journal={Transactions on Machine Learning Research},
year={2022},
url={https://openreview.net/forum?id=NPfS5N3jbL},
note={}
}
```
