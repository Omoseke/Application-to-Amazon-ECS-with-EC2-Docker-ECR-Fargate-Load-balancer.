# Application-to-Amazon-ECS-with-EC2-Docker-ECR-Fargate-Load-balancer.
This project describes how to deploy a web application to Amazon Elastic Container Service (ECS) using various tools such as Elastic Cloud Compute (EC2), Docker, Elastic Container Registry (ECR), Application Load Balancer in AWS.
The following are requirements to get started with the project. 
Create an AWS account.
PuTTy: Download and install puTTy.
cd terraform
terraform init
terraform plan -var-file=terraform.tfvars
terraform apply -var-file=terraform.tfvars
