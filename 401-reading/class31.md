# Class 31

[Home](https://daviey52.github.io/reading-notes/)

## Django REST Framework & Docker

Docker is a way to isolate and run entire applications. With docker, it does not matter that you are using a Mac, Windows, or Linux computer. The entire environment is isolated: programming language, software packages, database and more. With Docker we don’t have to mess with virtual environment.

Docker is just a Linux container which are a type of virtualization. The main advantage of these s Size and speed.
Virtual machines are used to isolate Python software package locally. Importantly is that virtual environments can only isolate Python packages. They still rely on a global, system-level installation of Python.

When you start with Docker, an image is a snapshot in time of what a project contains. A container is a running instance of the image.

Docker file is a list of instructions for creating an image. Images are made up of one or more layers.

Containers are a running instance of an image. Doccker-compose.yml controls ho to run the container.

Importantly, containers are stateless and ephemeral in nature. We can link the local filesystem through volume, but things become more complicated with database.

## Django for APIs

It is important to note that Django creates websites containing webpages, while Django REST Framework creates web APIs which are a collection of URL endpoints containing available verbs that return JSON
