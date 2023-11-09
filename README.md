# Deploying WordPress and MySQL On Deka Harbor

This repo shows a yaml code how to deploy a WordPress site and a MySQL database using Deka Harbor.

## Objectives
- Create PersistentVolumeClaims
- Create a kustomization.yaml with a Secret generator, MySQL resource configs, WordPress resource configs & Ingress resources with tls
- Use private registry (Deka Registry)
- Apply the kustomization
