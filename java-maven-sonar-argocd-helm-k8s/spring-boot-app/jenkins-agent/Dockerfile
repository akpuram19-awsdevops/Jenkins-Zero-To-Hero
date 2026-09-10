FROM docker:27-cli AS docker-cli

FROM maven:3.9-eclipse-temurin-21
COPY --from=docker-cli /usr/local/bin/docker /usr/local/bin/docker
