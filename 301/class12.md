# CRUD

## Status Codes based on REST Methods

1. In your own words, describe what each group of status code represents:

    100’s = Informational that indicate that the initial part of a client request has been received by the server and is continuing to process the request.
    200’s = Success status codes. Server has successfully received and processed the request.
    300’s = Redirection that state the client must take further action to complete the request. Like a moved bookmark or link.
    400’s = Client error codes that say the server was unable to complete the request due to an error on the client side. Syntax error or bad request.
    500’s = Server error codes that say the server was unable to complete the request due to an error on the server side. Sometimes a maintenance or overload.

2. What is a status code 202?

    Accepted. Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. 

3. What is a status code 308?

    Permanent redirect. This tells the client to use another URL to access the resource and not use the current URL anymore.

4. What code would you use if an update didn’t return data to a client?

    204, no content.

5. What code would you use if a resource used to exist but no longer does?

    410, gone.

6. What is the ‘Forbidden’ status code?

    The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

## REST API

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

    Due to the sensitve nature of DB credentials, API keys, passwords, etc, it is best practice to do so and prevent exposure.

2. What is middleware?

    Software components or functions that are used to handle request and responses between the client and the servewr in a web app.

3. What does app.use(express.json()) do?

    A middleware function in the express.js for node.js that is used to parse incoming JSON data in the request body.

4. What does the /:id mean in a route?

    Router parameter that captures a variable portion of the route URL and assigns it to the id parameter in the request object.

5. What is the difference between PUT and PATCH?

    Put is used to update an entire resource, replacing contents with new. Patch is used to make partial updates to a resource.

6. How do you make a default value in a schema?

    Using the default property when defining a field.

7. What does a 500 error status code mean?

    Server side error that indicates the server was unavble to fulfill a valid request due to internal error.

8. What is the difference between a status 200 and a status 201?

    200(OK) means server has successfully processed the request. 201(Created) means the server has successfully created a new resource as a result of the request.