# Container image that runs your code
FROM alpine:3.10

# Copies your code file from your action repository to the filesystem path `/` of the container
COPY entrypoint.sh /entrypoint.sh

# artifact are download into artifactPath by default. This means we have a folder called artifactPath, please change accordingly.

COPY artifactPath .
# Code file to execute when the docker container starts up (`entrypoint.sh`)
ENTRYPOINT ["/entrypoint.sh"]