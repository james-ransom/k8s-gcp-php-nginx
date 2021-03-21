# k8s-gcp-php-nginx

Example of K8S PHP NGINX and a GIT checkout to a volume. 

## Setup ## 

```
kubectl apply -f php_deployment.yaml
kubectl apply -f php_service.yaml
kubectl apply -f nginx_deployment.yaml
kubectl apply -f nginx_configMap.yaml
kubectl apply -f dir_volume.yaml
```
