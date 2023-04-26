# More CRUD

## CRUD Basics

1. Which HTTP method would you use to update a record through an API?

    PUT. It is used to replace the entire resource or entity at the specified URL with a new version.

2. Which REST methods require an ID parameter?

    GET, PUT, PATCH, DELETE.

## CRUD API

1. What’s the relationship between REST and CRUD?

    RESTful APIs can implement CRUD ops by mapping HTTP methods to corresponding database methods. 
        - Create: use POST to create a new resource
        - Read: use GET to retrieve a resource
        - Update: Use PUT or PATCH to update a resource
        - Delete: Use DELETE to delete a resource
    
    RESTful principles can provide flexibility for web APIs and and CRUD operations can provide simple data management.

2. If you had to describe the process of creating a RESTful API in 5 steps, what would they be?

    1. Identify the resources to manage such as products, users, data.
    2. Define endpoints for each resource and use HTTP methods to specify operations.
    3. Data model design that represents each resource and relationships. Use JSON or XML.
    4. Implement APIs using a web framework or backend language like Node.js. Handle requests and responses in the endpoints.
    5. Test the API to ensure functionality and returning correct results.