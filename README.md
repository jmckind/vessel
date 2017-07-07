# vessel

Kubernetes manifests for a simple LMS.

### Deployment

Deploy the rethinkdb cluster.

```
kubectl create -f rethinkdb.yaml
```

Deploy the deck application.

```
kubectl create -f deck.yaml
```

Deploy the captain application.

```
kubectl create -f captain.yaml
```

Deploy the middy application.

```
kubectl create -f middy.yaml
```
