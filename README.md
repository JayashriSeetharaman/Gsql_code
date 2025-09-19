
# What is Tigergraph?
### TigerGraph is a scalable graph database and analytics platform designed for handling and analyzing large volumes of interconnected data. It's particularly known for its Native Parallel Graph (NPG) technology, which allows it to perform real-time, deep-link analytics on massive datasets, with trillions of edges and hundreds of terabytes of data. Unlike traditional databases that store data in tables, TigerGraph stores data as a graph structure consisting of vertices (entities) and edges (relationships). The platform's native query language, GSQL, is optimized for graph analytics and enables complex queries and algorithms.




How TigerGraph Creates a Knowledge Graph
Creating a knowledge graph with TigerGraph involves several key steps:

Define the Schema: The first step is to design the schema for your knowledge graph. Using TigerGraph's GraphStudio visual interface or GSQL, you define the types of vertices (e.g., Person, Movie, Company) and edges (e.g., ACTED_IN, WORKS_AT, FRIENDS_WITH) that will represent your data. This process involves specifying the attributes for each vertex and edge.



Map and Load Data: Once the schema is defined, you can load your data into the graph. TigerGraph can ingest data from various sources, including CSV files, databases, and data streams. You map the data from your source files to the vertices and edges in your schema. TigerGraph's parallel processing capabilities enable high-speed data loading.


Query and Analyze: With the data loaded, you can use GSQL or other APIs to query and analyze the knowledge graph. GSQL is a powerful, SQL-like language that supports complex traversals (multi-hop queries), pattern matching, and the execution of graph algorithms like PageRank and community detection. This is where you can uncover hidden relationships and gain insights from your interconnected data.


