# Usa la imagen oficial de Alpine Linux
FROM alpine:latest

# Actualiza los repositorios e instalar las aplicaciones básicas
RUN apk update && \
    apk upgrade && \
    apk add \
    nano \
    vim \
    git \
    curl \
    wget \
    bash

# Comando por defecto al iniciar el contenedor
CMD ["/bin/bash"]
