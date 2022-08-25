# Using CQL

## Learning Goals

- Understanding syntax differences between SQL and CQL

## Introduction

Cassandra, like many NoSQL systems, tries to provide commonality with SQL so that users are able to migrate fairly easily to a new system.
Cassandra uses a syntax called CQL(Cassandra Query Language), which is very familiar if you are coming with previous SQL experience. There
are some major core differences between the two, but they are far more similar than different.


One of the major contributors to the Cassandra project, and the developers for the Cassandra Spring Driver is Datastax.
They have great client documentation that works well as a guided tour for CQL. Be aware though that all the examples don't work perfectly. You may run across inconsistancies and typos as you try to
follow through.

- [Datastax CQL Guide](https://docs.datastax.com/en/cql-oss/3.3/cql/cql_using/useAboutCQL.html)

Go ahead and run through the following sections of this guide. They should cover the major differences between SQL and CQL, and take about an hour to run through.

- [Creating and updating a keyspace](https://docs.datastax.com/en/cql-oss/3.3/cql/cql_using/useCreateKeyspace.html)
- [Creating a table](https://docs.datastax.com/en/cql-oss/3.3/cql/cql_using/useCreateKeyspace.html)
- [Creating advanced data types in tables](https://docs.datastax.com/en/cql-oss/3.3/cql/cql_using/useCreateKeyspace.html)
- [Batching data insertion and updates](https://docs.datastax.com/en/cql-oss/3.3/cql/cql_using/useBatchTOC.html)


There is also authoritative documentation on the Cassandra site for reference. There is no need to read though this at this time, but be aware that it exists.

- [CQL Reference](https://cassandra.apache.org/doc/latest/cassandra/cql/index.html)
