# Class 3

[Home](https://daviey52.github.io/reading-notes/)

Whenever we need to open a file, we need to know the file path, which is a string that represents the location of a file. Some of the common paths are
Folder Path – this is the folder location on the file system, where other folder are separated by a forward slash.
File name is the name of a file
Extension is the end of the file path. This is used to indicate file type.
One of the major challenges faced when working with file data is how to represent a new line or the ending of  a new line. Another main problem is the encoding of byte data. Encoding is the translation of data from byte to human readable characters. This is normally done by assigning a numerical value to represent a character.

.readline () method is used to iterate through each line. This method usually return a list where each element in the list represents a line in the file.
Exceptions
Syntax errors normally occur when a parser detects an incorrect statement
Exception error occur when syntactically correct python code results in an error. The last message normally indicate what type of exception error you ran into.
Instead of waiting for a python program to crash we can make an assertion. Meaning we assert a certain condition and if it is met the program can continue. If the condition turns to be false the program throw an assertion error.
Try and error blocks are used to catch and handle exception. Python will execute code that follows the try statement as a normal part of the program. The code that follows the except statement is response to any exception in the preceding try clause.
