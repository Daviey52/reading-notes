# Class 27

[Home](https://daviey52.github.io/reading-notes/)

## Using Models

Django web application access and manage data by use of python objects referred to as models. Models define the structure of stored data, including field type and also maximum size, selection list options, default values, help text for documentation.
Once we have a clear picture of a model to use for our Django project including the data we will store and the relationship between the different object, we need to think about the relationships. Django allows us to define relationships that are one to one , one to many and many to many.
Models are defined in an application’s models.py file. They are implicated as subclasses of Django models and can include fields, methods and metadata. A model can have an arbitrary number of fields, of any type.
One of the most useful features of metadata is to control the default ordering of records returned when you query the model.
A model can also have methods. Minimally, in every model you should define the standard python class method __str__() to return a human-readable string for each object.
Once you have defined a model class it can be used to create, update or delete records and to run queries to get all records or particular subset of records.

## Django Admin

Django Admin can use models to automatically build a site area, that you can use to create, view, update and delete records. This can save you a lot of time during development, making it easy to test you model and evaluate if you have the right data. Admin can also be useful for managing data in production depending on type of website.
In order to log into the admin site we need a user account with staff status enabled. In order to view and create records we also need this user to have permissions to manage all our object.
