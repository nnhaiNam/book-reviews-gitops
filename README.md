# book-reviews-gitops
## 📌 Overview
This repository contains Kubernetes manifests, Ingress configurations, Argo CD applications, and Slack alert rules used to deploy and manage the Book-Reviews Application using a GitOps approach.

## ⚙️ Components
+ 📁 Kubernetes Manifests: Deployments, Services, ConfigMaps, Namespaces, etc for each microservice in the application.
+ 🌐 Ingress Configurations: Ingress resources
+ 🚀 Argo CD Applications: Declarative Argo CD Application YAMLs to automate deployments.
+ 📊 Horizontal Pod Autoscaler (HPA): Auto-scales Pods based on CPU/memory usage to ensure optimal performance and resource utilization.
+ 🔔 Slack Alerts:
  PrometheusRule and Alertmanager configurations are used to trigger Slack notifications in the event of:

    ⚠️ High CPU or memory usage

    ❌ Node failures (Node Down)

    🚨 Other system-critical alerts



## 🔗 Source Code Repository
- 📁 [Book-Reviews](https://github.com/nnhaiNam/Book-Reviews.git)  
    _Contains the full source code of the application._

## 🔗 Terraform Repository
- 📁 [book-reviews-terraform](https://github.com/nnhaiNam/Terraform_K8S_Cluster.git)  
    _Contains Terraform code for provisioning AWS infrastructure including VPC, EC2, security groups, and other resources._
