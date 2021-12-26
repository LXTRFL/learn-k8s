# Learn K8s and Ingress

You can use Minikube for local development. You need to activate the ingress plugin in minkube.

```
$ minikube addons enable ingress
```

We use [traefik](https://doc.traefik.io/traefik/v1.7/user-guide/kubernetes/) as an ingress controller.
