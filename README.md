# Task 5: Build a Kubernetes Cluster Locally with Minikube

## Objective
Deploy and manage containerized apps using Kubernetes.

## Tools Used
- Minikube
- kubectl
- Docker Desktop

## Steps Followed

1. Installed Docker Desktop, Minikube, and kubectl on Windows.
2. Started the Minikube cluster with the Docker driver.
3. Created `deployment.yaml` to set up a sample app.
4. Created `service.yaml` to expose the app through NodePort.
5. Checked pods and services with `kubectl get`.
6. Scaled the deployment to 4 replicas using `kubectl scale`.
7. Reviewed pod logs and details with `kubectl describe` and `kubectl logs`.

## Outcome
I successfully deployed and scaled a Kubernetes app locally. I confirmed that the service was accessible and the pods were healthy.

## Screenshots
_Add screenshots of `kubectl get pods`, `kubectl get services`, and browser access to the app._