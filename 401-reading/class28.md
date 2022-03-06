# Class 28

[Home](https://daviey52.github.io/reading-notes/)

## Django Forms

Django forms provides a framework that allows developers to define forms and their fields programmatically and the use these objects to both generate the form HTML code and handle much of the validation and user interaction.
Django form handling include:

1. Display the default form the first time it is requested by the user
2. Receive data from a submit request and bind it to the form
3. Clean and validate the data
4. If invalid data, re-display the form with the populated values and error message for the problem fields.
5. If all data is valid, perform required actions e.g. save, update, delete
6. Once all actions are complete, redirect user to another page.

There are a lot of different form fields including, charField , BooleanField , DateField.

Django creates generic editing views for creating, editing and deleting views based on models. Not only do these handle the view behavior, but they automatically create the form class for you from the model.
