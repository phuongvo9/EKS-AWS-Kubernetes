# EKS-AWS-Kubernetes
Hands on Elastic Kubernetes Service
Elastic Kubernetes Service (EKS) is a fully managed Kubernetes service from AWS. In this tutorial, we will work with the AWS CLI & console, using eksctl and kubectl to launch an EKS cluster, provision a Kubernetes deployment and pod running instances of nginx, and create a LoadBalancer service to expose our application over the internet.

## Steps
1 Create an IAM user|K8S admin that have permission to run EKS cluster
2 Prepare an EC2 instance: to execute the commands to the EKS cluster (Create EC2, update AWS CLIv2, install eksctl & kubectl command line)
3 Use eksctl to create EKS cluster
4 Create Deployment (Pod | Nginx) and expose the deployment with Load Balancer service
5 Shut down worker node to see how the cluster responds

# Article
https://jackvo9.medium.com/
