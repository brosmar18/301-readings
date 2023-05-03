# Reading: CRUD

- In your own words, descxribe what ach group of status code represents: 
  - 100's: Inidicates that the server received the request and is continuing to process it. 
  - 200's: Indicates that the request was successfuly received, understood, accepted, and the server has successfully completed the request operation. 
  - 300's: Indicate that the requested resource has been moved or has multiple representations. The clioent must take further action, such as following a new URL, to complete the request. 
  - 400's: Indicate that the client made a bad request, and the server cannot or will not process it. Client may need to modify the request before resubmitting. 
  - 500's: Indicate that the server failed to fulfill a valid request, and the issue lies within th server itself. 
- What is a status code 202? 

​	This code indicates taht the request has been accepted for processing, but the processing has not been completed. 

- What is a status code 308? 

This status code indicates that the requested resource has been permanetly moved to a new URL, and the clieent should use a new URL for future requests. 

- What code would you use if an update didn't return data to a client? 

If an update didn't return data to a client, you would use status code 204 (No Content), which indiates that the request has been successfuly processed, but there's no data to send back. 

- What code would you use if a resource used to exist but no longer does? 

If a resource used to exist but no longer does, you would use status code 410 (Gone), which indictes that the requested resource is no longer available and will not be available again. 

- What is the "forbidden" status code? 

The forbidden status code is 403. Indicates that the client does not have permission to access the requested resource, even though the server understood the request. 

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?

We need to pull our MongoDB database string out of our sever and put it into our `.env` to enhance security and maintainability. Storing sensitive info like database connections strings in a `.env` file prevents accidental exposure of the credentials in the codebase or version control systems, and it allows for easy configuration changes without modifying the code itself. 

- What is middleware?

Middleware is a function or a set of functions that sit between the client's request and the server's response in a web app. It can intercept, modify, or process reequests and responses, enabling tasks such as authentidcation, logging, or data parsing. 

- What does app.use(express.json()) do?

`app.use(express.json())` is a middleware function that enables Express to parse incoming JSON data in the request body, making it accessible through the `req.body` object in the route handlers. 

- What does the /:id mean in a route?

The `/:id` in a route is a route parameter, which acts as a placeholder for a dynamic value (in this case, an "id") that the client can provide in the URL. It allows the sever to handle requests for specific resources based on the provided 'id'. 

- What is the difference between PUT and PATCH?

PUT updates an entire resource with the provided data, replacing the existing data, while PATCH allows for partial updates, modifying only the spedcified fields in the resource. 

- How do you make a default value in a schema? 

You can use the `default` property when defining a filed in the schema. For example, ina Mongoose schema: `filename: { type: String, default: 'defaultValue'}`. 

- What does a 500 error status code mean?

It means th3ere's an Internal Server Error, indicating that the server failed to process a valid request due to an issue within the server itself. 

- What is the difference between a status 200 and a status 201?

A status 200 (OK) indicates a successful general request, while status 201 (Created) is specifically used to indicate that a request to create a new resource has been successfully completed, and the resourrce has been created on the server. 