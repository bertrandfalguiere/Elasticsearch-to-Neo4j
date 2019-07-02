# Elasticsearch-to-Neo4j

This is a small project to transfer data from an Elasticsearch database to a Neo4j database.

-Wait, what? Impossible! The data structures are not the same! You can import data from Neo4j to ES, losing the data traversal optimisation of Neo4j, but you can't store the ES highly nested documents on Neo4j, right?

Well yes and no. You need to make some choices for sure. This is a generic tool. It won't fit all use case because choices were made.
(detail below).

Does it work? Sometime.
Is it fast and optimised? No.
Is it a quick dirty snippet? Yes.
Is it well documented? Hell no. (Sorry)
