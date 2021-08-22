# Class Thirteen

[Home](https://daviey52.github.io/reading-notes/)

1. In your own words, describe what each group of status code represents:

• 100’s = They are informational status code – they tell a client that the header part of the request has been received by the server

• 200’s = These are the success codes. They tell the client that the request was accepted

• 300’s =These are redirection code. They tell the client that the resource they are requesting is not available

• 400’s = These are client error code. They are all about invalid requests a client sent to a server

• 500’s = These are the server error codes. They are all about invalid requests a client sent to a server

.
2. What is a status code 202?
 This code tells the client that the request was valid, bit its processing will finish sometime in the future

3.What is a status code 308?
 This code tells the client to use another URL to access the resource and not the current URL anymore

4.What code would you use if an update didn’t return data to a client?
204

5.What code would you use if a resource used to exist but no longer does?
410

6.What is the ‘Forbidden’ status code?
403

Video

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  Because once we deploy the application, we will want to have it running on another server and not on our local host
2. What is middleware?
Code that run when the server gets request before it send it to a route
3. What does app.use(express.json()) do?
Allow use the server to accept JSON as a body
4. What does the /:id mean in a route?
It means it’s a parameter
5. What is the difference between PUT and PATCH?
Put updates all information at once while Patch update only information that get’s passed
6. How do you make a defalut value in a schema?
By creating a default property for the object in a schema

7. What does a 500-error status code mean?
Internal Server Error
8. What is the difference between a status 200 and a status 201?
Code 200 tells the client everything went well while 201 signals the backend-side resource creation and come along with a location header that defines the most specific URL for that newly created resource
