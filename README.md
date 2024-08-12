# Screenshots

## CI deployment Pipeline
[https://github.com/namph-it98/project_03/blob/main/screenshots/CI.png
](https://github.com/namph-it98/project_03/blob/main/screenshots/CI.png)

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
[https://github.com/namph-it98/project_03/blob/main/screenshots/pods.png
](https://github.com/namph-it98/project_03/blob/main/screenshots/pods.png)

* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
[https://github.com/namph-it98/project_03/blob/main/screenshots/services.png
](https://github.com/namph-it98/project_03/blob/main/screenshots/services.png)



* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```

* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```

