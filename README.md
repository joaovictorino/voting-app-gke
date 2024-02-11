# Sample voting application hosting with Google Kubernetes Engine (GCP)

Requirements

- GKE cluster (https://github.com/joaovictorino/terraform-gke)

Deploy web application

```sh
kubectl apply -f k8s
```

Get HTTP application ports and external IPs

```sh
kubectl get svc -n laboratorio
```

And then access the application in browser!
