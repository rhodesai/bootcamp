![RAIL Logo](images/rail_logo_gradient.png)

**Welcome, RAILer!**
The purpose of this guide is to get you up to speed *as fast as possible* in the tools that RAIL tends to use.
The folders in the repo contain tutorials, mostly in *Jupyter Notebook* format (formerly known as *iPython Notebook*).
**If you're familiar with Jupyter Notebooks,** then we recommend going through the interactive Notebooks for the lessons you need.
**If you're *not* familiar with them,** then first install and get to know them.

We tend to use the standard Python data science & machine learning stack:

1. **Development: Jupyter Notebooks** – an interactive, easy-to-share interface for creating "Notebooks" of code and results that anyone else can download and interact with. We recommend this over working on flat files.
2. **Data: Pandas** – a Python library that makes loading, cleaning, exploring, and analyzing data really easy.
3. **Machine Learning: Scikit-Learn and others** – Scikit-learn contains a lot of pre-made, well-tested machine learning algorithms. Most of the key ones can be called with the same methods: `model.fit(X, y)` and `model.predict(X_test)`.
    - Other libraries we've used: *TensorFlow* (mostly for deep learning), *Keras* and *PyTorch* (deep learning), *Edward* (probabilistic modeling – advanced level.)

We've also included some extra reading on machine learning, to build your intuition about:

1. What types of machine learning are there?
2. When is each type used?

## Contents
### 1. Jupyter Notebooks

Check out the `Jupyter Notebooks Introduction` folder to learn how to install and use Jupyter Notebooks.

### 2. Pandas Cookbook

Check out the `Pandas Cookbook` folder for [Julia Evans'](https://jvns.ca) phenomenal sequence of 9 Pandas tutorial notebooks ([taken from this repo](https://github.com/jvns/pandas-cookbook)).
If you can do these, you'll be moving pretty fast.
Highly recommended.

### 3. Machine Learning Cookbook

#### Beginner Conceptual Introductions
- [Basic ML Concepts](https://machinelearningmastery.com/basic-concepts-in-machine-learning/) – a high-level overview of Week 1 of Pedro Domingos' [great Coursera course.](https://www.coursera.org/specializations/machine-learning)
- [Types of Machine Learning](https://medium.com/towards-data-science/types-of-machine-learning-algorithms-you-should-know-953a08248861) – a high-level overview of what *supervised, unsupervised, semi-supervised, and reinforcement learning* are.
- [Types of Algorithms](https://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/) – a clustering (ha) of types of common machine learning algorithms.
- [Flowchart: Choosing algorithms](http://scikit-learn.org/stable/tutorial/machine_learning_map/) – while *not comprehensive*, this offers useful intution about when to choose a type of algorithm.
- [Visualized: Decision Trees](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) – a **beautiful!** introduction to basic concepts, decision trees, and the learning process.

#### Notebooks

1. `1. Concepts - Machine Learning` - a set of notebooks to introduce you to applying a subset of ML concepts. I recommend looking at the PDF guides for conceptual learning and the notebooks for implementation. (Credit to [John Wittenauer](https://github.com/jdwittenauer/ipython-notebooks))
2. `2. Example - Titanic Survival` - an exercise where you'll predict the likelihood of survival for people onboard the *Titanic* using real data. This is a famous introductory example! (Credit to [Andrew Conti](https://github.com/agconti/kaggle-titanic))
3. `3. Tools - Scikit-learn Tutorial` - a set of notebooks to introduce you to various tools within *scikit-learn*. (Credit to [Jake Vanderplas](https://github.com/jakevdp/sklearn_pycon2015))



### 4. Extra Resources

- [The Stanford/Andrew Ng Machine Learning Course](https://www.coursera.org/learn/machine-learning) – a number of RAILers (strategists *and* engineers) have done this course during their RAIL project and found it both fascinating and useful.
- [Python/Numpy Tutorial](http://cs231n.github.io/python-numpy-tutorial/) – if you've never used NumPy before, or want to understand Python, I recommend this tutorial. (Built for the Stanford Convolutional Neural Network class.)
- [Python](http://www.python.org/) is the common programming language that we use. It is *both* functional and object-oriented. You will probably find that object-oriented is cleaner and easier to debug, while functional is faster to write.
- [NumPy](http://www.numpy.org/), or *Numeric Python*, is the fundamental Python library for scientific computing. It allows you to do things like really easy manipulate data, analyze matrix-style data, and do linear algebra.
- [SciPy](https://www.scipy.org/), or *Scientific Python*, is a collection of libraries (including NumPy) that contains sophisticated scientific computing functions. For example, `scipy.stats` contains some advanced statistical functions that NumPy doesn't have.