# Multi-fidelity classification using Gaussian processes: accelerating the prediction of large-scale computational models

Machine learning techniques typically rely on large datasets to create accurate classifiers. However, there are situations when data is scarce and expensive to acquire. This is the case of studies that rely on state-of-the-art computational models which typically take days to run, thus hindering the potential of machine learning tools. In this work, we present a novel classifier that takes advantage of lower fidelity models and inexpensive approximations to predict the binary output of expensive computer simulations. We postulate an autoregressive model between the different levels of fidelity with Gaussian process priors. We adopt a fully Bayesian treatment for the hyper-parameters and use Markov Chain Mont Carlo samplers. We take advantage of the probabilistic nature of the classifier to implement active learning strategies. We also introduce a sparse approximation to enhance the ability of themulti-fidelity classifier to handle large datasets. We test these multi-fidelity classifiers against their single-fidelity counterpart with synthetic data, showing a median computational cost reduction of 23% for a target accuracy of 90%. In an application to cardiac electrophysiology, the multi-fidelity classifier achieves an F1 score, the harmonic mean of precision and recall, of 99.6% compared to 74.1% of a single-fidelity classifier when both are trained with 50 samples. In general, our results show that the multi-fidelity classifiers outperform their single-fidelity counterpart in terms of accuracy in all cases. We envision that this new tool will enable researchers to study classification problems that would otherwise be prohibitively expensive. 

This paper is currently under review. We will soon upload the codes once the paper is published.

- Francisco Sahli Costabal, Paris Perdikaris, Ellen Kuhl, Daniel E. Hurtado. [Multi-fidelity classification using Gaussian processes: accelerating the prediction of large-scale computational models](https://arxiv.org/abs/1905.03406). arXiv preprint arXiv:1905.03406 (2019).

## Citation
```
@article{sahli2019multi-fidelity,
  title={Multi-fidelity classification using Gaussian processes: accelerating the prediction of large-scale computational models},
  author={Sahli Costabal, Francisco and Perdikaris, Paris and Kuhl, Ellen and Hurtado, Daniel E.},
  journal={arXiv preprint arXiv:1901.04878},
  year={2019}
}
```
