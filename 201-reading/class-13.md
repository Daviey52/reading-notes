# class Thirteen

[Home](https://daviey52.github.io/reading-notes/)

## Local Storage

* Persistent local storage is of the areas where native client applications have held  an advantage over web applications. For these native applications, the operating system typically provides an abstraction layer for storing and retriving application specific data like preference or runtime state.

* Cookies were invented early in the web's history, and indeed they can be used for persistent local storage of small amounts of data. Though they have three potential dealbreaking downside

1. Cookies are included with every HTTP request, therefor slowing down your web application by needlessly transmitting the dame data over and over
2. Cookies are included with every HTTP request, thereby sending data unencripted over the internet unless the entire web application is served over SSL
3. Cookies are limited to about 4 KB of data - this is enough to slow down your application, but not enough to be terribly usefull

* with HTML 5 , it is able to offe

1. a lot of storage space on the client side
2. They persist beyound a page refresh
3. It is not transmitted to the server

* HTML5 storage is simply a way for web pages to store named key/value pair locaaly, within the client web browser. this data persists even after closing the browser or refreshing the browser. It is implimented natively in web browser, meaning it is available even when third-party browser plugin are not.

* HTML5 Storage is based on named key/value pair. the stored data is based on a named key that you can use to retrieve the data using the same key. Stored data can be any type including strings , Booleans , floats and interger. Though this data gets stored as a string.

* The main limitation of HTML5 storage is that it has a 5 megabytes storage limitation. for strings this can be significant but when storing floats or integers, this is limited since each digit is stored as a character.
