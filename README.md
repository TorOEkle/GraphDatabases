# GraphDB
This branch is for demo and learning GraphDB. Look at other branches for Neo4j, RDFox and SQL.
To spin up a container with GraphDB run following command.

```bash
podman run -p 127.0.0.1:7200:7200 --name graphdb-instance-name -t ontotext/graphdb:10.6.1
```

Now is GraphDB available at <http://localhost:7200/>


To run refine run one of either commands
```bash
docker-compose up -d

podman run -d -p 7333:7333 --name refine ontotext/refine:latest
```

Then refine is available at <http://localhost:7333>

When finish working you can stop it by running 

```bash
podman stop refine
```


