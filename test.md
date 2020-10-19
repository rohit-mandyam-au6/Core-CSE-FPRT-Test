## Questions and Answers

## What is the CAP theorem? Differentiate between forward proxy and reverse proxy.
A) The CAP theorem, also called as Brewer's theorem, states that, for a distributed data store, it is only possible to provide two out of the three things at the same time and they are Consistency, Availability and Partition tolerance.
A forward proxy is like a middle-man that the client puts forward between itself and any server. The reverse proxy, also like the forward proxy, is at the other end which is like a middle-man that the server puts forward between itself and any client.

## What is Caching and what are the different types of cache. What are the different ways to update cache?
A) - Caching is the process of storing copies of files in a cache, or temporary storage location, so that they can be accessed more quickly. This means a cache is a temporary storage location for copies of files or data, but the term is often used with respect to Internet technologies.
The different types of caching are :- 
 - Web Caching
 - Data caching
 - Output Caching
 - Distributed Caching

## What is HTTP? Differentiate between HTTP and TCP. Differentiate between GET, POST, PUT and PATCH.
A) HTTP means Hyper Text Transfer Protocol. It allows the fetching of resources, such as HTML documents. It is the foundation of any data exchange on the Web and it is a client-server protocol.
HTTP is a Hypertext Transfer Protocol, whereas TCP is Transmission Control Protocol. HTTP is utilized to access websites, while TCP is a session establishment protocol between client and server. HTTP is faster in comparison to TCP. HTTP is useful for transfer of smaller documents like webpages, whereas, TCP is useful to setup connection for data transfer. HTTP is Stateless but not session less and TCP is a Connection-Oriented Protocol. HTTP uses port 80 and TCP uses no port.
The most commonly used HTTP verbs POST, GET, PUT, DELETE are similar to CRUD (Create, Read, Update and Delete) operations in database.
 - create - POST -  is mostly utilized to create new data.
 - read - GET -  is the simplest type of HTTP request method. It instructs the server to transmit the data identified by the URL to the client. GET request is read-only.
 - update - PUT -  is most-often utilized for updating the data.
 - delete - DELETE - used to delete a resource identified by a URI.

## Explain how DNS works.
A) Each device that is connected to the internet has its unique address called IP address which is denoted by numbers, for eg : 192.168.1.1 and this is used by devices to find each other on the internet. But it is difficult for humans to understand using numbers.
So something called DNS comes into the picture. DNS means Domain Name Server. Its work is to make it easy for humans by translating domain names to IP addresses so browsers can load the web pages. Now, it becomes easier for human beings to go to a particular website without they themselves trying to understand and memorize which IP address is meant for which device.

## Differentiate between SQL and NO-SQL database.
A) SQL is implemented in RDBMS (Relational Database Management System) whereas No-SQL is implemented in non-relational or distributed database system.
SQL DBs have predefined or a fixed schema, while, No-SQL DBs have dynamic schema.
SQL DBs are are vertically scalable whereas No-SQL DBs are horizontally scalable.
SQL DBs are not fit for hierarchical data storage  while No-SQL DBs are fit for hierarchical data storage. This is because NoSQL follows the key-value pair storage method that is similar to JSON data.
Complex queries can be performed on SQL DBs whereas they cant be performed on No-SQL DBs.

## Differentiate between normalization and denormalization.
A) In normalization Non-redundant and consistent data are stored in a schema while in denormalization data are combined to execute the query quickly.
In normalization, data redundancy and inconsistency is reduced and in denormalization, redundancy is added for quick execution of queries.
Data integrity is maintained in normalization while Data integrity is not maintained in denormalization.
The number of tables in normalization is increased and in denormalization the number of tables in decreased.

## Differentiate between RPC and REST.
A) REST is best described to work with the resources, where as RPC is more about the actions.
REST stands for Representational State Transfer. It is a simple way to organize interactions between systems. RESTful applications commonly use HTTP requests to create and post data, read data and delete data. Thus, REST can use HTTP for all four CRUD (Create,Read,Update,Delete) operations.
RPC is basically used to communicate across the different modules to serve user requests.