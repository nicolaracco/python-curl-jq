# Python + Curl + JQ Docker image

[Image on Dockerhub](https://hub.docker.com/r/gawaine/python-curl-jq)

Docker image I needed to run commands on Drone CI pipelines

Example usage: `docker run -v $PWD:/app gawaine/python-curl-jq sh /app/ci/validate_version_on_registry.sh`