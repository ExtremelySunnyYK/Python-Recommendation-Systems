
# Things to try out
Python


[http://surpriselib.com/](http://surpriselib.com/)

[https://github.com/benfred/implicit](https://github.com/benfred/implicit)

This project provides fast Python implementations of several different popular recommendation algorithms for implicit feedback datasets:

[https://github.com/lyst/lightfm](https://github.com/lyst/lightfm)

LightFM is a Python implementation of a number of popular recommendation algorithms for both implicit and explicit feedback, including efficient implementation of BPR and WARP ranking losses. It's easy to use, fast (via multithreaded model estimation), and produces high quality results.

It also makes it possible to incorporate both item and user metadata into the traditional matrix factorization algorithms. It represents each user and item as the sum of the latent representations of their features, thus allowing recommendations to generalise to new items (via item features) and to new users (via user feature)

[https://github.com/caserec/CaseRecommender](https://github.com/caserec/CaseRecommender)

Case Recommender is a Python implementation of a number of popular recommendation algorithms for both implicit and explicit feedback. The framework aims to provide a rich set of components from which you can construct a customized recommender system from a set of algorithms. Case Recommender has different types of item recommendation and rating prediction approaches, and different metrics validation and evaluation.

[https://github.com/PreferredAI/cornac](https://github.com/PreferredAI/cornac)

Cornac is a comparative framework for multimodal recommender systems. It focuses on making it convenient to work with models leveraging auxiliary data (e.g., item descriptive text and image, social network, etc). Cornac enables fast experiments and straightforward implementations of new models. It is highly compatible with existing machine learning libraries (e.g., TensorFlow, PyTorch).

Rexy (rec-sy) is an open-source recommendation system based on a general User-Product-Tag concept and a flexible structure that has been designed to be adaptable with various data-schema. There are a lot of methods and ways that Rexy has used to recommend the products to users. This includes general recommendations like Top products, event based recommendations and Novel products that the user might be interested in. There are other recommendations that are directly related to the user's activities or other users that have a similar behavior to the given user.

[https://github.com/tensorflow/ranking/](https://github.com/tensorflow/ranking/)

TensorFlow Ranking is a library for Learning-to-Rank (LTR) techniques on the TensorFlow platform. It contains the following components:

- Commonly used loss functions including pointwise, pairwise, and listwise losses.
- Commonly used ranking metrics like [Mean Reciprocal Rank (MRR)](https://en.wikipedia.org/wiki/Mean_reciprocal_rank) and [Normalized Discounted Cumulative Gain (NDCG)](https://en.wikipedia.org/wiki/Discounted_cumulative_gain).
- [Multi-item (also known as groupwise) scoring functions](https://arxiv.org/abs/1811.04415).
- [LambdaLoss](https://ai.google/research/pubs/pub47258) implementation for direct ranking metric optimization.
- [Unbiased Learning-to-Rank](http://www.cs.cornell.edu/people/tj/publications/joachims_etal_17a.pdf) from biased feedback data.

[https://github.com/maciejkula/spotlight](https://github.com/maciejkula/spotlight)

Spotlight uses PyTorch to build both deep and shallow recommender models. By providing both a slew of building blocks for loss functions (various pointwise and pairwise ranking losses), representations (shallow factorization representations, deep sequence models), and utilities for fetching (or generating) recommendation datasets, it aims to be a tool for rapid exploration and prototyping of new recommender models.

[https://github.com/PreferredAI/tutorials/tree/master/recommender-systems](https://github.com/PreferredAI/tutorials/tree/master/recommender-systems)

[https://github.com/PreferredAI/cornac/blob/master/README.md#installation](https://github.com/PreferredAI/cornac/blob/master/README.md#installation)

### **Benchmarking Recommender Systems**

It is very difficult to benchmark recommender systems, not only because getting good datasets is hard, but different methods and algorithms have different advantages and disadvantages that are difficult to expose.

Here is a list of some benchmarking tools:

1. [TagRec](https://github.com/learning-layers/TagRec) Tag Recommender Benchmarking Framework
2. [RiVaL](http://rival.recommenders.net/) an open source toolkit for recommender system evaluation. Some results are posted [here](http://alans.se/blog/2014/rival/).
3. [Idomaar](http://rf.crowdrec.eu/) is a reference framework for recommender algorithm testing. It is developed in the framework of the [CrowdRec](http://crowdrec.eu/) project.

### Best praciticees

[https://microsoft-recommenders.readthedocs.io/en/latest/](https://microsoft-recommenders.readthedocs.io/en/latest/)

References

[https://github.com/ExtremelySunnyYK/recommendation_engine](https://github.com/ExtremelySunnyYK/recommendation_engine)