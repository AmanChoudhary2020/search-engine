# Scalable Search Engine

Built a scalable search engine using PageRank ranking system, a segmented inverted index of scraped web
pages created with Hadoop framework, and a distributed system for determining search results.

* Ranking based on both tf-idf and PageRank scoring
* Indexing implemented with MapReduce for scalability with larger corpus sizes

This project involved developing a series of MapReduce programs with Hadoop Streaming to create an inverted index of scraped Wikipedia articles. After generating the inverted index, I built an index server (a REST API) to manage individual segments of the index and created a server-side dynamic pages application that aggregates results from each of these segments and delivers search results to the user. **The frontend was developed using plain HTML, and the backend with Flask and MySQL**. 

This project taught me how to efficiently process large-scale data using Hadoop Streaming. I also explored page ranking systems and inverted indexes, and I learned to implement distributed system design techniques, such as sharding and replication, along with service-oriented architecture to scale dynamic web pages and improve web search capabilities.

