# Portainer Server

Container [Portainer Server](https://www.portainer.io/) permettant de contrôler une instance [Docker](https://www.docker.com/) locale.

Peut être utilisé avec [des agents](https://github.com/SergeBregliano/docker-portainer-agent).

## Sécurité

L'installation d'un serveur Portainer ne doit pas être exposée au public. L'accès au serveur doit être faite soit sur un réseau local, soit au travers d'un tunnel SSH.

## Installation

Copie des sources dans le répertoire ``portainer_server`` :

```shell
git clone https://github.com/SergeBregliano/docker-portainer-server.git portainer_server
```

Lancer le système de mise à jour :

```shell
sh ./updateStack.sh
```

### Connexion au serveur Portainer

Le port exposé par le serveur Portainer est le **9443**.

```http
https://localhost:9443/
```

