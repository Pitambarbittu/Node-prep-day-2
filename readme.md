# What are the different types of HTTP requests?

### http protocol is used to make network requests from the nodejs.there are different types of http methods--
1. GET-used to read or fetch data from the server.
2. POST-it is used to send data or content to the server.
3. PUT-used to modify data on the server.
4. DELETE-delete the resource at the server at the specified location.

# Explain the concept of middleware in Node.js.

* middleware is a function which has access to request object,response object and next function in application's request-response cycle.
* middleware can be used to perform many tasks like--
* call next middleware in stack
* execute any code
* make changes to request and response object
* end request-response cycle.
* can be used to add logging and authentication functionality

# Explain CORS.

### CORS stands for cross origin resource sharing.interaction or any data sharing between two server which has different origins(protocol,domain or host,port) is blocked by CORS policy.to enable it,we install cors as a module and use it in our application as a global middleware so that it is automatically applied for all the routes.

# What is Express. how it helps you to create a backend application.

* express is fast,unopinionarted and minnimalist web framework built on top of nodejs that provides broad features for building web and mobile applications.it helps manage server and routes better.
* it helps to create a backend application because--
* -fast server side development which saves a lot of time.
* -provide template engines for building dynamic content on web pages.
* -it is fast to link with database.

# Explain min 5 status codes gets used in Backend development.

* http status codes are messages or three digit response from server that tells us how things went when it received the request to view a certain webpage.they are a means of communication between server and the browser.
### they can be splitted into 5 catef=gories----
1. informational response(100-199)
2. successful response(200-299)
3. redirectional response(300-399)
4. client error response(400-499)
5. server error response(500-599)
* most encountered status code is 404(requested resource was not found)

# Difference between HTTP and HTTPS.

* both http and https are protocols using which information or data is exchanged between the server and the browser.
* difference between the two is-------------
* https is more secure than http.
* http is faster than https
* http default prt is 80,which https default port is 443
* http doesnot improve search ranking like https does.
* http works at application layer while https works at transport layer.