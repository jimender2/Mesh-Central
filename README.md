# Mesh Central In Docker

This is a docker compose file that could be used to manage several computers using either the Mesh Central Agent or Intel AMT.

Mostly using the Mesh Central to test out Intel vPro capibilities.


## Instructions

**Pre-requisites**: have Docker and Docker-Compose installed on your machine.

Clone the repository to your computer and open the repository in your favorite terminal.

Run the following command

    docker-compose up -d

This should start the Mesh Central Docker container and the mongodb container as well.  The mongodb container is optional but recommended easier data persistence and performance.

## Helpful Links

https://meshcentral.com/info/

https://meshcentral-community.com/doku.php?id=reference:config

https://hub.docker.com/r/typhonragewind/meshcentral
