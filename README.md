# Rafale2 by Mihai BOSIICA

## Etape 0 : Organisation du travail

// TODO

## Install

Required:  

- docker
- docker-compose

Pour vos OS respectifs vous pouvez les installer en suivant ces documentations:  

- [Docker engine](https://docs.docker.com/engine/install/)
- [Docker compose](https://docs.docker.com/compose/install/)

Commandes utiles:

```bash
# Lancer en background
docker-compose up -d
# Lancer un des services en background
docker-compose up -d backend
# Voir les logs de tous les containers
docker-compose logs -f
# Voir les logs d'un container spécifique
docker-compose logs -f backend
# Voir les 500 dernières lignes de logs
docker-compose logs -f --tail 500
```

## Launch

Et c'est tout, vous pouvez lancer la db et le backend avec cette commande:

```bash
docker-compose up -d
```

Le swagger est accessible sur -> <http://localhost:8888/swagger_ui/>
