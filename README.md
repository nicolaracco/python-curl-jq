# Python + Curl + JQ Docker image

Docker image I needed to run commands on Drone CI pipelines

Example usage: `docker run -v $PWD:/app nicolaracco/python-curl-jq sh /app/ci/validate_version_on_registry.sh`