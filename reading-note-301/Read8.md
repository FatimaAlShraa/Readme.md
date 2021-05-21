#  REST

Q1:  REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP.


Q2: REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

Q3:which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:https://adventure-works.com/orders/1

Q4:GET, POST, PUT, PATCH, and DELETE

Q5:Adopt a consistent naming convention in URIs

Q6:In general, it helps to use plural nouns for URIs that reference collections. It's a good practice to organize URIs for collections and items into a hierarchy. For example, /customers is the path to the customers collection, and /customers/5 is the path to the customer with ID equal to 5

Q7:  A successful GET method typically returns HTTP status code 200 (OK).tty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. Instead, you might want to denormalize the data and combine related information into bigger resources that can be retrieved with a single request.

Q8:If the resource cannot be found, the method should return 404 (Not Found)

Q9:If a POST method creates a new resource, it returns HTTP status code 201 (Created).

Q10:If the delete operation is successful, the web server should respond with HTTP status code 204






