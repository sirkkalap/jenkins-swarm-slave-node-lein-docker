jenkins-swarm-slave-node-lein-docker
====================================

Jenkins Swarmer slave with nodejs and Leiningen build elements

# Running

```bash
    docker run --rm --link jenkins-master:jenkins \
    sirkkalap/jenkins-swarm-slave-node-lein-docker:latest \
    -username jenkins -password jenkins -executors 1
```

# Building

```bash
    docker build -t sirkkalap/jenkins-swarm-slave-node-lein-docker .
```
