# Class Nine

[Home](https://daviey52.github.io/reading-notes/)

## Dunder methods

In python special methods are a set of predefined methods you can use to enrich your classes

__init__ dunder is used as a constructor. The constructor normally takes care of setting up the object

Two main ways to providing a string representation of objects include
__repr__: the official “string” representation of an object
__str__: the “informal” or nicely printable string representation of an object.

To iterate over transactions in reversed order you can implement the __reversed__ special method:

  When you would add your object to a builtin (int, str, …) the __add__ method of the builtin wouldn’t know anything about your object. In that case you need to implement the reverse add method (__radd__) as well.

A context manager is a simple “protocol” (or interface) that your object needs to follow so it can be used with the with statement.

## Basic statistic in Python

Probability seeks to answer what is the chance of an event happening?

Thus, given enough data, statistics enables us to calculate probabilities using real-world observations.

In probability, the normal distribution is a particular distribution of the probability across all of the events.

If we make many estimates, the Central Limit Theorem dictates that the distribution of these estimates will look like a normal distribution.

The Three Sigma rule dictates that given a normal distribution, 68% of your observations will fall between one standard deviation of the mean. 95% will fall within two, and 99.7% will fall within three.

The Z-score is a simple calculation that answers the question, “Given a data point, how many standard deviations is it away from the mean
