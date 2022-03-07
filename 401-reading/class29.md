# Class 29

[Home](https://daviey52.github.io/reading-notes/)

## Django Custom User Model

Official Django documentation recommends use of a custom user model as opposed to the included User model authentication. The main reason for this recommendation is that it provides far more flexibility down the line.

There are two ways to create a custom user. AbstractUser and AbsstractBaseUser. In both case we can create a subclass that extends the functionality though AbstractBaseUser will require much more work.

It is super helpful to create a superuser than can be used to log into admin for the main purposes of testing out the functionality of our login and log out.

DjangoX is an open-source Djanog starter framework that includes a customer user model, email/password by default instead of username/email/password, social authentication and more.
