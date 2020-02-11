## This is a Nginx Deployment Test for Kubernetes

```
kubectl apply -f nginx_deployment.yaml
kubectl apply -f nginx_node_port.yaml
kubectl apply -f nginx-ingress.yaml
```
### Test the Nginx nginx_deployment

http://127.0.0.1 or

We can edit hosts file to have the entries like below:

127.0.0.1 nginx.example.com

http://nginx.example.com
