# MongoDB
A NoSQL Database that stores data in flexible, JSON like document called BSON (Binary Object Notations)
Unlike relational databases MySQL doesnt use tables, row, and columns with rigid schema and offers a dynamic structure.
## Core Conepts
- **Document** - The basic unit of data in MongoDB. It is a set of key-value pairs, the values can be of any data type including document, array or array of documents.
- **Collection** - A group of documents. Collections dont enforce a schema, meaning the documents within a single collection can have different fields.
- **Database** - A container for collections.
## Key Features
- **Flexible Schema** - No need to pre-define the structure of data. Can add new fields to documents, and different documents in the same collection can have different fields.
- **Horizontal Scalability** - MongoDB is designed to scale out, not just up. This means we can distribute the data across multiple servers **(Sharding)** to handle massice data loads, a process that is often more complex with relational databases.
- **Indexing** - MongoDB supports various types of indexes, which are crucial for optimizing query performance. We can create indexes on any field, including nested documents and arrays.
- **High Availability** - Through replica sets, MongoDB provides automatic failover and data redundancy. A replica set is a group of MongoDB servers that hold identical data. If the primary server fails, a secondary server is automatically promoted to primary, ensuring continuous operation.
