# Intro

Consider two different image datasets that vary in terms of their domains or distributions (texture, viewpoint, appearence, etc). The smaller one being the labbeled and the larger, unlabeled. Can we train a model using these two datasets in a way that allows domain adaptation, i.e. by training on one data distribution and testing on a different one. [Adaptive matching](/adamatch.ipynb) can unify unsupervised domain adaptation, semi-supervised learning, and semi-supervised domain adaptation under one framework. Lets use our vision dataset to find out if it really improves the model performance when the labeled dataset is very small and both the dataset have similar distribution.

# References

https://arxiv.org/abs/2106.04732

https://keras.io/examples/vision/adamatch/

https://www.happywhale.com
