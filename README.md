# over-under-nginx

Simple configuration for building and running an nginx container to act as a reverse proxy for a web application.
The specific use case for this container is to be a reverse proxy for the over-under apis.

This container will be deployed (with others) via AWS Lightsail container service.

## Scripts
    * docker_build_image.sh - builds the docker image
    * docker_run_container.sh - runs the docker container

## Status
    * Currently container is configured for HTTP only