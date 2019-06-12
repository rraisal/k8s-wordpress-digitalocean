# k8s-wordpress-digitalocean

kubectl apply -f wordpress-secrets.yml
kubectl apply -f pv-claim.yml
kubectl apply -f wordpress-db.yml
kubectl apply -f wordpress-web.yml
kubectl apply -f wordpress-web-service.yml
kubectl apply -f wordpress-db-service.yml
