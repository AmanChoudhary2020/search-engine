# Scalable Search Engine

Built a scalable search engine using PageRank ranking system, a segmented inverted index of scraped web
pages created with Hadoop framework, and a distributed system for determining search results.

* Ranking based on both tf-idf and PageRank scoring
* Indexing implemented with MapReduce for scalability with larger corpus sizes

This project involved developing a series of MapReduce programs with Hadoop Streaming to create an inverted index of scraped Wikipedia articles. I built an index server (a REST API) to manage a segment of the inverted index, and created a server-side application that aggregates results from each of the index servers and delivers search results to users. The frontend was developed using plain HTML, and the backend was implemented with Flask and MySQL. I gained experience in processing large-scale data with Hadoop Streaming, understanding page ranking systems and inverted indexes, and utilizing distributed system design and service-oriented architecture to scale dynamic pages and web search.

