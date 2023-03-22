# DISTRIBUTED SEARCH SYSTEM

### ABOUT
- This is a scalable distributed system that allows user to search for keywords to find the matching documents.
- Use Apache Zookeeper for master/workers architecture and to communicate between nodes.
- Use TF-IDF algo to rank score of the documents.

### Frontend
- distributed-search-frontend

### Backend
- distributed-search

### How to run
- Download Apache Zookeeper https://zookeeper.apache.org/releases.html
- Start Zookeeper server.
- Create election znode.
- mvn clean package for front-end and back-end.
- For front-end: run jar file: java -jar target/...-SNAPSHOT-jar-with-dependencies.jar
- For back-end: run jar file like front-end but with multiple ports to simulates a cluster.
- Open port 9090 to interact with client-side.
