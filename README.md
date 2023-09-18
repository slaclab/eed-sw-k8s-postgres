
This repo holds the configuration for PostgreSQL


# Deployment

This repository is used by argocd to deploy PostgreSQL on eed-sw k8s luster

# Configuration Changes


# Common Tasks
kubectl apply -f cnpg-1.20.2.yaml


### Get status of cluster


### Promote a replica to primary



### Destroy an instance


## Pg Sphere Extension

## Monitoring

We utilise the built in prometheus monitoring of cnpg and have a [live dashboard](https://grafana.slac.stanford.edu/d/z7FCA4Nnk/cloud-native-postgresql).

[Link to on how to calculate work mem](https://www.enterprisedb.com/postgres-tutorials/how-tune-postgresql-memory)
