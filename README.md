# Order Management Scripts
This repository has been setup to store Terraform scripts to setup order management infrastructure.

Following items need to be created:
* order-management-service ECR public repo
* IAM access management identity provider for github OIDC
* Role to assume to push image to ECR
* ECommerceECSCluster
* OrderManagementServiceTaskDefinition
* OrderManagementServiceECSService
* ECommerceECSClusterAutoScalingGroup
* ECommerceEC2KeyPair
* Postgres RDS Instance
* Network Interface?
* VPC/Subnets/Security Groups