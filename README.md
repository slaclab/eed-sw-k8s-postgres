# eed-sw-k8s-postgres
Deployment of Postgres database into eed-sw kubernetes cluster


kubectl apply -f ns.yaml
kubectl apply -f users-secret.yaml
kubectl apply -f operator.yaml
kubectl apply -f cr.yaml

kubectl get secrets cluster1-users -o yaml -o jsonpath='{.data.postgres}' | base64 --decode | tr '\n' ' ' && echo " "