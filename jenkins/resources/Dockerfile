FROM jenkins/inbound-agent:latest

# Instalar o Podman
USER root
RUN apt-get update && \
    apt-get install -y podman

# Permissões do Jenkins
USER jenkins