ARG VERSION

FROM ghcr.io/cms-enterprise/batcave/workflow-engine:${VERSION}

COPY entrypoint.sh /entrypoint.sh

# Code file to execute when the docker container starts up (`entrypoint.sh`)
ENTRYPOINT ["/entrypoint.sh"]
