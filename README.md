# machine learning
Machine learning is getting computers to program themselves.Any information or data sent to a computer is considered input. Data produced by a computer is considered output. In the machine learning community, input data is referred to as the *feature set* and output data is referred to as the *target*. The feature set is also referred to as the *feature space*. Sample data is typically referred to as *training data*. Once the algorithm is trained with sample data, it can make predictions on new data. New data is typically referred to
as *test data*. Machine learning is divided into two main areas: **supervised and unsupervised learning**.

We will learn 
1. What is Dummy Variables and One Hot Encoding 
2. Word to Vector (word2vec)

### What is Dummy Variables and One Hot Encoding
To use categorical variables in a machine learning model, you first need to represent them in a quantitative way. The two most common approaches are to one-hot encode the variables using or to use dummy variables.
[Article Link:](https://machinelearningmastery.com/one-hot-encoding-for-categorical-data/)

### Word to Vector (word2vec)
Machine learning models do not understand text. Text needs to be converted into a numerical form to be fed into your models. Word2Vec is a shallow, *two-layer neural networks* which is trained to reconstruct linguistic contexts of words. It takes as its input a large corpus of words and produces a vector space, typically of several hundred dimensions, with each unique word in the corpus being assigned a corresponding vector in the space. It comes in two flavors, the **Continuous Bag-of-Words (CBOW) model** and the **Skip-Gram model**
[Article Link:](https://towardsdatascience.com/word2vec-from-scratch-with-numpy-8786ddd49e72)