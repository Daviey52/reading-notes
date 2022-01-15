# Class Eleven

[Home](https://daviey52.github.io/reading-notes/)

## JupterLab

jupyterLab is a next generation web-based user interface for project Jupyter. It enable users to work with documents and activities such as Jupyter notebooks, text editors , terminal and custom components in a flexible, integrated and extensible manner.

You can arrange multiple documents and activities side by side in the work area using tabs and splitters.

JupiterLab also provide a unfied model for viewing and handling data formats. Some of the mainly used formats include, images, cvs , json , pdf among others.

JupiterLab will eventually replace Jupyter Notebook. Throughout this transition, the same notebook document format will be supported by both the classic Notebook and JupyterLab.

## Numpy

Numpy is commonly used python data analysis package. It can speed up workflow, withother packages in the python ecosystems like scikit-learn. Numpy is used by almost every data analysis or machine learning package.

In a NumPy array, the number of dimensions is called the rank, and each dimension is called an axis. So the rows are the first axis, and the columns are the second axis.

One of the limitations of NumPy is that all the elements in an array have to be of the same type, so if we include the header row, all the elements in the array will be read in as strings.
It’s possible to use NumPy to directly read csv or other files into arrays. We can do this using the numpy.getfromtxt function function.

Unless the arrays that you’re operating on are the exact same size, it’s not possible to do elementwise operations.
We can use te numpy.ravel function to turn an array into a one-dimensional representation.
