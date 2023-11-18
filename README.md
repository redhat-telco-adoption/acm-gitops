# RHACM & GitOps Demo

## Prerequisites

- oc CLI
- Ansible

## Bootstrapping RHACM and Managed Clusters

1. Login to your openshift cluster
    
    ```oc login ...```
2. Create a file named `variables.yaml` in the `bootstrap/vars` directory. The file named `variables_template.yaml` can be used as reference for the available variables

## Deploying Workloads