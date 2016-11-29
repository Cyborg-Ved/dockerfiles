FROM ubuntu

RUN apt-get update -yq && \
    apt-get install curl -yq

HEALTHCHECK --interval=5s --timeout=3s CMD curl --fail http://localhost:80/ || exit 1