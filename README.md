
This repo holds the configuration for PostgreSQL


# Deployment

This repository is used by argocd to deploy PostgreSQL on eed-sw k8s luster

# Configuration Changes


# Common Tasks

Requires installation of the cnpg [kubectl plugin](https://cloudnative-pg.io/documentation/1.17/cnpg-plugin/#cloudnativepg-plugin)

### Get status of cluster


### Promote a replica to primary



### Destroy an instance


## Pg Sphere Extension

## Monitoring

We utilise the built in prometheus monitoring of cnpg and have a [live dashboard](https://grafana.slac.stanford.edu/d/z7FCA4Nnk/cloud-native-postgresql).

[Link to on how to calculate work mem](https://www.enterprisedb.com/postgres-tutorials/how-tune-postgresql-memory)
