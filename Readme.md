# build-pipeline-starter

Is a simple docker-compose file to get startet with your own local or remote build pipeline.

It contains an instance of each:
- gitea (git based version control system)
- Jenkins (build pipeline engine)
- Nexus (storing the created artifacts)
- Sonarqube (quality analysis and quality gate)
- trafik (firewall and server proxy)

At the end of this starter, each of these services should be aware of each other and the pipeline should work out of the box.

gitea will contain an examplatory project and Jenkins will contain a build pipeline for that 

## Installation

Use docker and docker-compose to setup all the containers. 

```bash
docker-compose up
```

## Usage

After the containers are started, you can use the applications on localhost and ports

```bash

```
