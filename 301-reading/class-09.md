# Class Nine

[Home](https://daviey52.github.io/reading-notes/)

1. What is functional programming?
According to Wikipedia, functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
2. What is a pure function and how do we know if something is a pure function?
Pure functions has two concepts
• It returns the same results if given the same argument
• It does not cause any observable side effect

3. What are the benefits of a pure function?
Pure functions are stable, consistent and predictable

4. What is immutability?
It can not change after it is created

5. What is Referential transparency?
If a function consistently yields the same result for the same input

1.What is a module?
Modules are code that is split into categories due to certain functionality, so that it makes it easier for other developers or ourselves to understand what is happening in smaller chucks of codes that when everything is dumped into one file.
2. What does the word ‘require’ do?
Require allows us to introduce functionality of another module into a module in which it was not defined or written in
3. How do we bring another module into the file the we are working in?
Make sure we first export the file and then use require to bring it in (Require(‘./-.js’))
4. What do we have to do to make a module available?
Export it
