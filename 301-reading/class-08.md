# Class Eight

[Home](https://daviey52.github.io/reading-notes/)

• API Design Best Practices

1. What does REST stand for?
It’s an architectural style for building distributed stytems based on hypermedia
2. REST APIs are designed around a resource

3. What is an identifer of a resource? Give an example.
An identifier of a resource is a URI that uniquely identifies that resource. For instance in a customer order, it might look like this <https://adventure-works.com/orders/2>

4. What are the most common HTTP verbs?
GET, POST, PUT, PATCH and DELETE

5. What should the URIs be based on?
URIs should be based on nouns and not verbs

6. Give an example of a good URI.
<https://adventure-works.com/orders>

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
It having more request meaning a bigger load to handle. ‘Chatty’ web APIs expose a large number of small resources. Chatty web API should be avoided as it is a bad thing.
8. What status code does a successful GET request return?
Returns HTTP status code 200 (ok)

9. What status code does an unsuccessful GET request return?
 Returns HTTP status code 404 (Not Found)
10. What status code does a successful POST request return?
Returns HTTP status code 201 (created)

11. What status code does a successful DELETE request return?
Returns HTTP status code 204 (No Content)

Reference: <https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design>
