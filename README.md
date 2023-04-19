# MongoDB

## What is MongoDB ?
MongoDB is a type of database that can store data in a flexible way, similar to how you would write data in a document. Unlike traditional databases,
it does not need a fixed structure for storing data. Instead, it allows you to store data in a format that works best for your application.
MongoDB is used by many modern web and mobile applications to store and manage their data.

![image](https://user-images.githubusercontent.com/129948378/233044098-e77acb64-21d2-46b6-8381-a16c38133f80.png)

## What are NoSQL databases? How do they differ from SQL?
NoSQL databases are a type of database that store and retrieve data in a flexible and scalable way. 
They do not use fixed structures like SQL databases, but instead use different data models to store data.
NoSQL databases are designed to handle big data challenges and are highly scalable and available. SQL databases, on the other hand, use a fixed schema and are better suited for applications that require strong consistency and ACID properties.

## Why is MongoDB popular? What is it’s history? 
MongoDB is popular because it's easy to store and retrieve data in a flexible way without predefined tables or schemas. 
It can handle a lot of data and traffic and is optimized for high performance. It's open-source, integrates well with modern technologies, and has great community support.

MongoDB was founded in 2007 and released its first version in 2009. It quickly became popular and is now one of the most widely used NoSQL databases. MongoDB has continued to add new features and expanded its product offerings, including Atlas and Realm.

## MongoDB architecture for storing data

![image](https://user-images.githubusercontent.com/129948378/233046695-9b9db41a-c1f1-4239-8b09-29ca201b26d9.png)

- Application

The application is the program or software that interacts with the MongoDB database to store, retrieve, and manipulate data. The application communicates with the MongoDB database using a driver.

- Driver

A driver is a software library or module that provides a programming interface for the application to interact with the MongoDB database. MongoDB supports drivers for many programming languages, including Java, Python, Node.js, and PHP.

- Mongo Shell 

The Mongo Shell is a command-line interface that allows developers and administrators to interact with the MongoDB database directly. It provides a JavaScript-based environment for querying the database, managing collections, and performing administrative tasks.

- Mongos

Mongos is a component of MongoDB's sharding architecture. It is responsible for routing queries and write operations to the appropriate shards, which are separate instances of the database that store subsets of the data. Mongos acts as a query router and load balancer, ensuring that queries are distributed evenly across the shards.

- Machines ( shards )

MongoDB can be deployed on a single machine or on a cluster of machines, depending on the size and requirements of the application. A single machine deployment is suitable for small-scale applications, while a cluster deployment provides scalability, availability, and fault tolerance for larger applications.

## What is seeding in MongoDB?

Seeding in MongoDB is the process of adding initial data, such as default or sample data, to a database. This is important because it helps ensure data integrity, maximise database performance, and provide default values for applications. Seeding can be done using scripts or tools, and it's useful when a database is first created, when data needs to be reset or updated, or for testing and development purposes.
