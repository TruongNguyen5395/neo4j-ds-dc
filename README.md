# Neo4j with Data Science setup
## To run this container
Build the container:

```
docker-compose build
```

Then start the container:
```
docker-compose up
```

- Jupyter Lab notebook: localhost:8888
- The Neo4j browser: localhost:7474 

(ID: neo4j / Password: 1234)

Stop by using:

```
docker-compose down
```

## Notes

- There are two Python packages that can be used to connect to Neo4j from within Python.  
  - `neo4j`(https://neo4j.com/docs/api/python-driver/current/): The official, Neo4j-supported Python driver
  - `py2neo`(https://py2neo.org/2021.0/): A community-developed driver with lots of solid documentation and examples out there
- There is a notebook in `notebooks/` for testing the connection of Jupyter notebook with Neo4j.


## References

- [Neo4j](https://neo4j.com)
  - [Awesome Procedures on Cypher (APOC)](https://neo4j.com/labs/apoc/)
  - [Cypher Manual](https://neo4j.com/docs/cypher-manual/current/)
  - [Cypher Reference Card](https://neo4j.com/docs/pdf/neo4j-cypher-refcard-stable.pdf)
  - [Graph Data Science (GDS) Library](https://neo4j.com/developer/graph-data-science/)
  - [Python Driver API Docs](https://neo4j.com/docs/api/python-driver/current/)

