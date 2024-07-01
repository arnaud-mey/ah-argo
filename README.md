# AH-ARGO

This repository contains the manifests to deploy the hello-app.

## Structure

- `./apps` contains the ArgoCD application for the hello-app
- `./hello-app` contains the manifests of the hello-app. There is a kustomize base and a `prod` overlay that specifies the image tag for the production environment


