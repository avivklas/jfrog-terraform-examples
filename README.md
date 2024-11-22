# Terraform Playground
This repository contains a collection of Terraform configurations that I use to learn and experiment with Terraform.

## Install Terraform
Follow the [Install Terraform](https://developer.hashicorp.com/terraform/install) page to install Terraform on your machine.

## Setting up Terraform with Artifactory
The recommended way to manage Terraform state is to use a remote backend.
Some of the repository examples use JFrog Artifactory as the remote backend (commented out).

To set up Terraform with Artifactory, follow the instructions in the [Terraform Artifactory Backend](https://jfrog.com/integration/terraform-artifactory-backend/) documentation.

## Examples
1. Create an [AWS VPC and EC2 Instance](1.aws-vpc-and-ec2)
2. Deploy [Nginx in Kubernetes](2.kubernetes-nginx)
3. Install [JFrog Artifactory with Helm](3.artifactory-install)
4. Manage [JFrog Artifactory configuration](4.artifactory-config) with the [Artifactory Provider](https://github.com/jfrog/terraform-provider-artifactory)
5. Create an [AWS EKS (Kubernetes) cluster](5.aws-eks)
6. Install [JFrog Artifactory in AWS with Terraform](6.artifactory-aws-install) using RDS, S3, and EKS. This uses the [Artifactory Helm Chart](https://github.com/jfrog/charts/tree/master/stable/artifactory) to install Artifactory
7. Install [JFrog Artifactory and Xray in AWS with Terraform](7.jfrog-platform-aws-install) using RDS, S3, and EKS. This uses the [JFrog Platform Helm Chart](https://github.com/jfrog/charts/tree/master/stable/jfrog-platform) to install Artifactory and Xray
