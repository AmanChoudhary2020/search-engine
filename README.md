# Scalable Search Engine

Built a scalable search engine using PageRank ranking system, a segmented inverted index of scraped web
pages created with Hadoop framework, and a distributed system for determining search results.

* Ranking based on both tf-idf and PageRank scoring
* Indexing implemented with MapReduce for scalability with larger corpus sizes

This involved creating a pipeline of MapReduce programs to create a segmented inverted index, building a index server (ie REST API) that’s responsible for a segment of the inverted index, and a server-side dynamic pages app that accumulates results from each of the index servers and returns the information back to the user. The frontend was written in plain HTML, and the backend with Flask and MySQL. Learned about Hadoop streaming (create and run Map/Reduce jobs with any executable as the mapper + reducer), page ranking system, inverted index, and how to use a distributed system design to scale the system. 
