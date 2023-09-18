
This repo holds the configuration for PostgreSQL

# Documentaiontion
https://cloudnative-pg.io/

# Deployment

This repository is used by argocd to deploy PostgreSQL on eed-sw k8s luster

https://github.com/cloudnative-pg/cloudnative-pg/tree/main/docs/src/samples

# Common Tasks
kubectl apply -f cnpg-1.20.2.yaml

## Monitoring

We utilise the built in prometheus monitoring of cnpg and have a [live dashboard](https://grafana.slac.stanford.edu/d/z7FCA4Nnk/cloud-native-postgresql).

