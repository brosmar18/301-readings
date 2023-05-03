# Reading: More CRUD

- Which HTTP method would you use to update a record through an API?

To update a record throuogh an API, you would typically use the HTTP PUT or PATCH method. PUT is used for updating an entire resource with the provided data, while PATCH allows for patial updates, modifying only specified fields in the resource. 

- Which REST methods require an ID parameter?
  - GET: for retrieving a specified resource. 
  - PUT: for updating a specified resource. 
  - PATCH: for partially updating a specific resource. 
  - DELETE: for removing a specific resource. 

- What’s the relationship between REST and CRUD?

  REST is an architectural style for designing networked applications, while CRUD represents the basic operations for managing data in a database. 

- If you had to describe the process of creating a RESTful API in 5 steps, what would they be?
  - Identify resources: Determine the main resources (entities) your API will manage, such as users, products or orders. These resources will be the basis fo your API endpoints. 
  - Define endpoints and HTTP methods: Design the URI structure for your resources, and map the appropriate HTTP methods to perform CRUD operations on each resource. 
  - Implement request handling: Write the code for handling incoming HTTP requests, parsing any data sent by the client, and performing the corresponding CRUD operations on the resource. 
  - Implement response generation: After processing the request, generate appropriate responses with relevant HTTP status codes and, if necessary, data in a standardized format such as JSON.
  - Apply best practices: Ensure your API follows RESTful principles and best practices, such as statelessness, using proper HTTP status codes, and adhering to a consistent naming convention for URIs and methods. 



