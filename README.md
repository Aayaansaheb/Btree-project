# Btree-project
📌 Energy Trading Record Management System for a Smart Grid
C | B-Trees | Data Structures

Developed a robust system to manage energy trading transactions between producers and consumers in a smart grid using B-Trees to enable efficient insertion, lookup, and range queries.

Modeled each transaction as a node containing transaction ID, buyer/seller IDs, energy amount, price, and timestamp.

Designed separate B-Tree structures for sellers and buyers, supporting quick access to:

Regular buyers (more than 5 transactions)

Total energy sold/purchased

Transaction history per entity

Implemented key functionalities:

Add/display transactions

Time-based queries and revenue calculation

Sorting buyer/seller pairs by number of transactions

Range queries on energy traded

Sorting buyers by total energy consumption

Optimized performance by leveraging B-Tree properties for structured storage and scalable querying of dynamic transaction records.
