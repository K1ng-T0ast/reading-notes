# MongoDB and Mongoose

## Nosql and sql

1. List 5 difference between SQL and NoSQL

    - SQL databases are called relational databases (RDBMS) and NoSQL databases are non-relational or distributed databases
    - SQL databases are table based databases whereas NoSQL are document based, key-value pairs, graph databases or wide-column stores.
    - SQL databases ahave predefined schema whereas NoSQL have synamic schema for unstructured data.
    - SQL databases are vertailly scalable whereas NoSQL are horizontally scalable. SQL are scaled by hardware and NoSQL by increasing database servers.
    - SQL databases use SQL (structured query language) for defining and manipulating data and NoSQL databases are query focused on collections of documents. UnQL or unstructured query language.

2. What kind of data is a good fit for an SQL database?

    Web data, transactional data, customer, data, inventory data, medical data...

3. Give a real world example

    Web data: user accounts, content management, site analytics

4. What kind of data is a good fit for a NoSQL database?

    Document data, graph data, time series data, key-value data, object data...

5. Give a real world example

    Time-series data: sensor data, stock market data, website traffic data

6. Which type of database is best for hierarchical data storage?

    NoSQL as it follows the key-value pair way of storing data similar to JSON data. Highly preferred for large data sets.

7. Which type of database is best for scalability?

    Depends, SQL because you can manage load by increasing hardware component power and NoSQL because you can add a few more servers.

## SQL vs NoSQL continued, MongoDB

1. What does SQL stand for?

    Structured query language

2. What is a relational database?

    One that organizes data into one or more tables, each consisting of a set of rows and columns. Tables are related to each other based on common attributes or keys.

3. What type of structure does a relational database work with?

    One or more tables, each table has defined structure with fixed set of columns that represent specific attributes of the data and a fixed set of data types that define the format of the data.

4. What is a ‘schema’?

    A logical structure that defines the organization and format of data in a database.

5. What is a NoSQL database?

    While relational databases store data in tables with a predefined schema, NoSQL databases store data in a more flexible and unstructured format, often using documents, key-value pairs, graphs, or other data models.

6. How does it work?

    NoSQL databases often provide APIs or query languages that allow users to interact with the data in a flexible and efficient way. For example, in a document-oriented database, users may use a query language to search for documents based on specific fields or values. In a key-value store, users may use simple operations such as "get", "put", and "delete" to access and manipulate data.

7. What is inside of a MongoDB database?

    A MongoDB database consists of one or more collections, each of which contains a set of documents. A document is a set of key-value pairs that represent a single instance of data. Similar to JSON, can contain nested structures and arrays.

8. Which is more flexible - SQL or MongoDB? and why.

    MongoDB due to its document-oriented data model and dynamic schema.

9. What is the disadvantage of a NoSQL database?

    Data consistency, complexity, limited query capabilites, lack of standardization, learning curve.