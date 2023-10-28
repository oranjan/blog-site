# Pulse-blog your thoughts 

**Project Description:** simple blog site where you can add your blog post with a title. 

## What I learnt about:

- [HTTP Methods](#http-methods)
- [REST API](#rest-api)
- [Fetch API](#fetch-api)

## HTTP Methods

HTTP methods, or HTTP verbs, are used to specify the desired action when making requests to a server. The most commonly used HTTP methods include:

1. **GET** - Used to retrieve data from a server. It should not have any side effects on the server.

2. **POST** - Used to send data to a server to create a new resource.

3. **PUT** - Typically used to update an existing resource on the server. It replaces the entire resource.

4. **PATCH** - Used to partially update a resource on the server. It only modifies the specified fields.

5. **DELETE** - Used to request the removal of a resource from the server.

Each of these methods has specific use cases in RESTful API design.

## REST API

A REST API (Representational State Transfer Application Programming Interface) is a set of rules and conventions for building and interacting with web services(b/w clieant and server). Key principles of a REST API include:

1. **Resources:** Everything is a resource, and each resource is uniquely identified by a URL.

2. **HTTP Verbs:** Use HTTP methods to perform CRUD (Create, Read, Update, Delete) operations on resources.

3. **Stateless:** Each request from a client to the server must contain all the information necessary to understand and fulfill the request.

4. **Uniform Interface:** A consistent way to interact with resources, including standard naming conventions and response formats.

5. **Client-Server Architecture:** Separation of concerns between the client and server, allowing for scalability and flexibility.

6. **Stateless Communication:** No client context should be stored on the server between requests.

Understanding these principles is essential for designing and consuming RESTful APIs.

## Fetch API

The Fetch API is a modern JavaScript interface for making network requests (HTTP requests) to servers. It provides a more powerful and flexible way to work with HTTP than older technologies like XMLHttpRequest. Key concepts of the Fetch API include:

1. **Fetching Data:** Use the `fetch()` function to send HTTP requests and retrieve responses from servers.

2. **Promises:** Fetch returns a Promise, making it easy to handle asynchronous operations.

3. **Request and Response Objects:** Interact with HTTP requests and responses as objects, allowing you to access headers, data, and more.

4. **Handling Errors:** Handle network errors and bad responses gracefully.


