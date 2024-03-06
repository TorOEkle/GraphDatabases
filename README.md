# GraphDB
This branch is for demo and learning GraphDB. Look at other branches for Neo4j, RDFox and SQL.
To spin up a container with GraphDB run following command.

```bash
podman run -p 127.0.0.1:7200:7200 --name graphdb-instance-name -t ontotext/graphdb:10.6.1
```

Now is GraphDB available at <http://localhost:7200/>