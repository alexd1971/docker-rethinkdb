# Run RethinkDb in Docker container

This Dockerfile allows to build docker image of RethinkDb server based on original [RethinkDb image](https://store.docker.com/images/rethinkdb). But unlike original image it allows to run `rethinkdb dump` and `rethinkdb restore` commands inside the container what makes no need to have RethinkDb client locally installed
