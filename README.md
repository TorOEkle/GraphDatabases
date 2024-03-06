# Neo4j
This branch is for demo and learning neo4j.

To spin up a container with graph data science library run following command. 

```bash
podman run -it --rm `
  --publish=7474:7474 --publish=7687:7687 `
  --user="$(id -u):$(id -g)" `
  -e NEO4J_AUTH=none `
  --env NEO4J_PLUGINS='["graph-data-science"]' `
  neo4j:latest
```