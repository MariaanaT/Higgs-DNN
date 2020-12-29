# Searching Higgs boson with neural networks

This work aims to replicate work presented in the article *Baldi, P., P. Sadowski, and D. Whiteson. “[Searching for Exotic Particles in High-energy Physics with Deep Learning.](https://arxiv.org/pdf/1402.4735.pdf)” Nature Communications 5 (July 2, 2014).* 

The abstract of the article states that "*Collisions at high-energy particle colliders are a traditionally fruitful source of exotic particle discoveries. Finding these rare particles requires solving difficult signal-versus-background classification problems, hence machine learning approaches are often used. [...] Using benchmark datasets, we show that deep learning methods need no manually constructed inputs and yet improve the classification metric by as much as 8% over the best current approaches. This demonstrates that deep learning approaches can improve the power of collider searches for exotic particles.*"

As in the original article, both shallow and deep neural networks are trained so that their behavior and accuracy can be compared. The aim was to replicate original work as closely as possible, but some modifications were needed especially for the deep neural network architecture to achieve similar accuracy as in the orinal work. Main reason for this is that the work desctibed in the article uses Pylearn2 to train neural networks, but Tensorflow and Keras are used in this work.

The dataset used in the original article, and used in this work as well, can be downloaded from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/HIGGS). Dataset description can be found from the article and in the notebooks here. See also [code in GitHub](https://github.com/uci-igb/higgs-susy) used in the original article.
