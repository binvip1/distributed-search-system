# DISTRIBUTED SEARCH SYSTEM

### ABOUT
- This is a scalable distributed system that allows user to search for keywords to find the matching documents.
- Use Apache Zookeeper for master/workers architecture and to communicate between nodes.
- Use TF-IDF algo to rank score of the documents.

### HOW TO RUN
- Clone this repo.
- Download Apache Zookeeper.
- Create znodes in Zookeeper: coordinators_service_registry, workers_service_registry, election.
- Start Zookeeper server.
- Start frontend.
- Run 4 nodes in backend with 4 ports.

### Frontend
- distributed-search-frontend

### Backend
- distributed-search
