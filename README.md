# KUBERNETES

Week 6 Assignment: Container Orchestration with Kubernetes

Assignment Overview
In this assignment, you will gain hands-on experience with Kubernetes by setting up a Kubernetes cluster using AWS EKS and Terraform. Additionally, you will explore Kubernetes manifests and Helm charts to deploy and manage containerized applications. You will also implement scaling strategies and set up monitoring and logging for your Kubernetes clusters.

Objectives
By the end of this assignment, you should be able to:
Understand the need for container orchestration and the architecture of Kubernetes.
Set up a Kubernetes cluster using AWS EKS and Terraform.
Deploy applications using Kubernetes manifests and Helm.
Manage and scale applications in Kubernetes.
Implement monitoring and logging for a Kubernetes cluster.

Prerequisites
Basic understanding of containerization and Docker.
Familiarity with Terraform for infrastructure as code.
Access to an AWS account.
Basic knowledge of YAML syntax.

Assignment Tasks

Task 1: Introduction to Kubernetes
Research and Explain:
Write a brief essay (300-500 words) on the need for container orchestration. Discuss the problems it solves and the benefits it provides.
Explain the architecture and components of Kubernetes. Your explanation should include:
Master node components (API Server, Scheduler, Controller Manager, etc.)
Worker node components (Kubelet, Kube-proxy, etc.)
Add-ons (DNS, Dashboard, etc.)

Task 2: Setting up a Kubernetes Cluster
Set Up AWS EKS with Terraform:
Follow the provided guidelines to set up a Kubernetes cluster on AWS EKS using Terraform.
Create a Terraform script that includes the necessary configurations to deploy an EKS cluster.
Document the steps you took, and include your Terraform configuration files in your submission.
Alternative Setup Using Minikube (Optional):
If you do not have access to AWS, set up a local Kubernetes cluster using Minikube.
Document the setup process and any challenges you encountered.

Task 3: Deploying Applications on Kubernetes
Create Kubernetes Manifests:
Write Kubernetes manifests (YAML files) for deploying a simple containerized application (e.g., a web server).
Include configurations for Deployment, Service, and ConfigMap.
Deploy your application to the Kubernetes cluster and verify that it is running correctly.
Using Helm for Application Management:
Install Helm on your Kubernetes cluster.
Create a Helm chart for the same application you deployed in the previous step.
Deploy the application using the Helm chart and compare it to the deployment using raw manifests.

Task 4: Managing and Scaling Applications in Kubernetes
Implement Scaling Strategies:
Configure horizontal pod autoscaling for your application.
Simulate a load on your application and observe the scaling behavior.
Document the steps and the observed behavior during scaling.
Set Up Monitoring and Logging:
Implement monitoring for your Kubernetes cluster using Prometheus and Grafana.
Set up logging using a logging solution like Elasticsearch, Fluentd, and Kibana (EFK) or any alternative.
Document your setup process and provide screenshots showing the monitoring 
and logging dashboards.
