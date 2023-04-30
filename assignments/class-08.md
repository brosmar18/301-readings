## What does REST stand for?
REST stands for Representational State Transfer.
## REST APIs are designed around a ____.
Around a resource.
## What is an identifier of a resource? Give an example.
An identifier is a unique reference (typically a URL) that points to a specific resource in a REST API.
**Example**: https://api.example.com/users/1234 (Here, "1234" is the unique identifier for a specific user in the "users" resource collection.)
## What are the most common HTTP verbs?
The most common HTTP verbs are GET, POST, PUT, PATCH, DELETE, and OPTIONS.
## What should the URIs be based on?
URIs shoule be based on resources (nouns) and not actions (verbs).

URI (Uniform Resource Identifier) is a string of characters that identifies a name or a resource on the internet. It is used to locate and access web resources like web pages, files, or services.
## Give an example of a good URI.
A good URI example: https://api.example.com/orders/5678 (This URI represents a specific order with the identifier "5678" in the "orders" resource collection.)
## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
A ‘chatty’ web API means that the API requires a large number of small requests between the client and server to accomplish a simple task.

This is generally considered a bad thing, as it can lead to increased latency and reduced performance, especially in scenerios with high network overhead or slow connections. It is better to design APIs that require fewer, more substantial requests to complete tasks.
## What status code does a successful GET request return?
A successful GET request returns a status code of 200 (OK).
## What status code does an unsuccessful GET request return?
An unsuccessful GET return typically returns a status code oof 404 (Not Found) if the resource is not avaialabe, although there coould be other status codes depending on the specific issue.
## What status code does a successful POST request return?
A successful POST request returns a status code of 201 (Created) when a resource is created as a result of the request.
## What status code does a successful DELETE request return?
A successful DELETE request returns a status code of 204(No content) indicating that the resoource has been deleted and no further infoormation is available.
