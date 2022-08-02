# The Classification of Optical Galaxy Morphology Using Unsupervised Learning Techniques
![GitHub](https://img.shields.io/github/license/Virodroid/galaxy-cluster) [![arXiv](https://img.shields.io/badge/arXiv-2206.06165-b31b1b.svg)](https://arxiv.org/abs/2206.06165)
## Abstract
The advent of large scale, data intensive astronomical surveys has caused the viability of human-based galaxy morphology classification methods to come into question. Put simply, too much astronomical data is being produced for scientists to visually label. Attempts have been made to crowd-source this work by recruiting volunteers from the general public. However, even these efforts will soon fail to keep up with data produced by modern surveys. Unsupervised learning techniques do not require existing labels to classify data and could pave the way to unplanned discoveries. Therefore, this paper aims to implement unsupervised learning algorithms to classify the Galaxy Zoo DECaLS dataset without human supervision. First, a convolutional autoencoder was implemented as a feature extractor. The extracted features were then clustered via k-means, fuzzy c-means and agglomerative clustering to provide classifications. The results were compared to the volunteer classifications of the Galaxy Zoo DECaLS dataset. Agglomerative clustering generally produced the best results, however, the performance gain over k-means clustering was not significant. With the appropriate optimizations, this approach could be used to provide classifications for the better performing Galaxy Zoo DECaLS decision tree questions. Ultimately, this unsupervised learning approach provided valuable insights and results that were useful to scientists.

## Citation
E. Fielding, C. N. Nyirenda and M. Vaccari, "The Classification of Optical Galaxy Morphology Using Unsupervised Learning Techniques," 2022 International Conference on Electrical, Computer and Energy Technologies (ICECET), 2022, pp. 1-6.
