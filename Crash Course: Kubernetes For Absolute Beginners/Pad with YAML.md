# YAML in Kubernetes
<br>Sample:
```

      apiVersion: v1
      kind: Pod
      metadata:
        name: myapp-pod
        labels:
          app: myapp
          type: front-end
      spec:
        container:
          - name: nginx-container
            image: nginx

```

CMD: $ ```kubectl create -f <pod_name>.yml```
