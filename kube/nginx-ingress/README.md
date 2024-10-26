# nginx-ingress

```sh
kubectl apply -f nginx.yaml
kubectl port-forward service/nginx-service 8080:80

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.11.2/deploy/static/provider/cloud/deploy.yaml
```


```sh
# /etc/hosts
127.0.0.1 myapp.example.com

curl http://myapp.example.com:8080
```