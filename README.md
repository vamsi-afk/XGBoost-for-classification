# XGBoost-for-classification
XGBoost is an algorithm that has recently been dominating applied machine learning and Kaggle competitions for structured or tabular data.

XGBoost is an implementation of gradient boosted decision trees designed for speed and performance.
It is an implementation of gradient boosting machines created by Tianqi Chen, now with contributions from many developers. It belongs to a broader collection of tools under the umbrella of the Distributed Machine Learning Community or DMLC who are also the creators of the popular mxnet deep learning library.

Tianqi Chen provides a brief and interesting back story on the creation of XGBoost in the post Story and Lessons Behind the Evolution of XGBoost.

XGBoost is a software library that you can download and install on your machine, then access from a variety of interfaces. Specifically, XGBoost supports the following main interfaces:

Command Line Interface (CLI).
C++ (the language in which the library is written).
Python interface as well as a model in scikit-learn.
R interface as well as a model in the caret package.
Julia.
Java and JVM languages like Scala and platforms like Hadoop.
XGBoost Features
The library is laser focused on computational speed and model performance, as such there are few frills. Nevertheless, it does offer a number of advanced features.

Model Features
The implementation of the model supports the features of the scikit-learn and R implementations, with new additions like regularization. Three main forms of gradient boosting are supported:

Gradient Boosting algorithm also called gradient boosting machine including the learning rate.
Stochastic Gradient Boosting with sub-sampling at the row, column and column per split levels.
Regularized Gradient Boosting with both L1 and L2 regularization.
System Features
The library provides a system for use in a range of computing environments, not least:

Parallelization of tree construction using all of your CPU cores during training.
Distributed Computing for training very large models using a cluster of machines.
Out-of-Core Computing for very large datasets that don’t fit into memory.
Cache Optimization of data structures and algorithm to make best use of hardware.
Algorithm Features
The implementation of the algorithm was engineered for efficiency of compute time and memory resources. A design goal was to make the best use of available resources to train the model. Some key algorithm implementation features include:

Sparse Aware implementation with automatic handling of missing data values.
Block Structure to support the parallelization of tree construction.
Continued Training so that you can further boost an already fitted model on new data.
XGBoost is free open source software available for use under the permissive Apache-2 license.

Why Use XGBoost?
The two reasons to use XGBoost are also the two goals of the project:

Execution Speed.
Model Performance.
