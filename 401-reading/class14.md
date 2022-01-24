# Class Fourteen

[Home](https://daviey52.github.io/reading-notes/)

## Matplotlib

Matplotlib provides a quick way to visualize data from python and publication-quality figures in many formats. It comes with a set of default setting that allows us to customize all kind of properties, a user can control the default of almost every property in matplotlib including, size, line width , axis, text and font properties.

Pyplot provides a convenient interface to the matplotlib object-oriented plotting library. It is modeled closely after Matlab.

Spines are lines that connect the axis tick mark and noting the boundaries of the data area. They can be placed at arbitrary positions.

A figure is the window in the GUI that has “Figure#” as title. They are numbered starting from 1 as opposed to the normal python 0.

With subplot, you can arrange plots in a regular grid. You do need to specify the number of rows and column and the number of the plot. Axes are also very similar to subplots though they allow placement of plots at any location.

The easiest way to make an animation in matplotlib is by declaring a FuncAnimation that will specify to matplotlb what is the figure to update. What is the update function and what is the delay between frames?
