# Visualising & understanding high-dimensional data

## Introduction

In this project I will explore a range of techniques for visualising & understanding very high dimensional datasets - which can be very challenging to use, observe & understand. Visualising higher dimensional datasets can have various purposes & objectives such as:

- Understanding the dataset & subject it represents better
- Preparing the data for machine learning algorithms

We will use the famous MNIST dataset of handwritten digit images which has 784 dimensions/features per image.
The techniques we will use to visualise this dataset will be:

- PCA (Principal components analysis)
- t-SNE (t-Distributed Stochastic Neighbour Embedding)
- TDA (Topological data analysis)

These are different techniques that aim to reduce down a datasets complexity to something easier to understand, either for humans or for machine learning algorithms (i.e. for classification).

## Key files 

- [Jupyter notebook of analysis](https://github.com/pranath/high_dim_data_vis/blob/master/high_dim_data_vis.ipynb)
- [Interactive topological network of MNIST digits dataset](https://pranath.github.io/high_dim_data_vis/tda_mnist_digits.html)

## Conclusion

In this project we explored 3 different techniques for visualising and understanding higher dimensional datasets.

We have seen how each of these has various strengths and weaknesses depending on the purpose and dataset you might have in question. None of these is a silver bullet that will solve all your problems on a particular project! However familarity with all 3 of these techniques could be extremely useful to have in a data scientists toolbox.
