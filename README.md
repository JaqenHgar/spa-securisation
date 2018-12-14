# POC of SPA securisation

The goal of this projet is to demonstrate how to manage authentication and habilitations with a SPA host on a tomcat server calling an API hosted in a fatjar.



# Pre-requisites

- Docker
- Docker-compose


# Composition

The project is composed of 3 containers:

- One containing Keycloak which will be our solution to implement OIDC standard
- One front container exposing an SPA (Angular)
- One back exposing an API based on a Spring Boot fatjar
