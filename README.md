# spring-security
Demo to learn Spring Security


###To Implement Basic Authorization using Spring Security

![](BasicAuth.png)

Let’s suppose a client want to send some requests to a server in order to perform some CRUD operations or to view some data. With basic auth if the client just 
sends a request it will get 401 status code meaning unauthorized from the server. This is because with basic auth you need to specify the username and password inside of 
the request header. So, every single request that a client sends to the server it needs to specify user name and password. The username and password is encoded as base64 inside
of the request header then the server does some validations to check whether the user exists and if the user exists it checks the password and then if the password matches that 
the server knows about then the server sends a status code with whatever the client has requested. Basic Auth is actually good when a client has to make some request to an
external APIs.
