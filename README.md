# POC:  network analysis without ES

Code related to Jira'S ticket /BP-18177

## How to start the project ?

- Install docker compose
- run docker compose up --build  at the root level
- to reset neo4j docker-compose down --volumes

## Getting stated
    Backend :  http://0.0.0.0:8000/docs
    neo4j UI : http://0.0.0.0:7474/browser    (default user - pwd)
    frontend : http://0.0.0.0:8080

## About the  User - Actor -  Network study case
    - tristan  PDF  for the study case
[PDF](https://drive.google.com/file/d/1YyBkmV_cKvXzEnV_IwWBNk8QItkS-lQ-/view?usp=sharing)


## Neo4j cheatsheet
    Delete all : MATCH (n) DETACH DELETE n
    Select all :  MATCH (n) RETURN n

## Some reading :
https://singerlinks.com/2020/10/should-i-use-py2neo-or-the-native-python-driver-to-access-neo4j/
https://github.com/neo4j-examples/movies-python-bolt
https://github.com/elena/py2neo-quickstart





