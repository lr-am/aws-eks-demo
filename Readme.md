# Deploy EKS cluster with Prometheus and Grafana using Terraform

## Requirements

* Terraform 
* aws cli

#### Steps to deploy EKS infraestructure

```bash
1.- Configure the subnet ids on eks.tf
2.- Apply the following commands with terraform:
    terraform init
    terraform apply
3.- Use the following command to get the kubeconfig of the cluster:
    aws eks update-kubeconfig --name eks_cluster_demo 
3.- After terraform execution, you will have an EKS cluster environment with Prometheus and Grafana 
    deployed
```
