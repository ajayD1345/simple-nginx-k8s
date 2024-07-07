# simple-nginx-kubernetes

This project demonstrates how to deploy a simple Nginx web server on Kubernetes using Pods, Deployments, and Services.

## Directory Structure

simple-nginx-k8s/
├── create/
│ ├── nginx-pod.yml
│ ├── nginx-deployment.yml
│ └── nginx-services.yml
└── README.md


## Steps to Deploy

1. **copy code from github:**

   ```
   git clone https://github.com/ajayD1345/simple-nginx-k8s.git
   
   ```
2. **Navigate to your project directory:**

   ```
   cd simple-nginx-k8s
  
   ```
3. **Apply the Pod configuration:**

  ```
  kubectl apply -f create/nginx-pod.yml

  ```
4. **Apply the Deployment configuration:**

  ```
  kubectl apply -f create/nginx-deployment.yml

  ```
5. **Apply the Service configuration:**

  ```
  kubectl apply -f manifests/nginx-service.yaml

  ```
## Verify Deployments

- Check Pods:
  ```
  kubectl get pods

  ```
- Check Deployments:
  ```
  kubectl get deployments

  ```
- Check Services:
  ```
  kubectl get services
  ```
## Author
Hamed Ayojide
