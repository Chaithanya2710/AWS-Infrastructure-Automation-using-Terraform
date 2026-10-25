\# AWS Terraform Infrastructure Projects



A collection of hands-on Infrastructure as Code (IaC) projects built using \*\*Terraform\*\* and \*\*Amazon Web Services (AWS)\*\*. These projects demonstrate cloud infrastructure provisioning, networking, compute, storage, and Terraform state management.



\## Projects



\### 1. EC2 Instance Provisioning

\- Provision AWS EC2 instances using Terraform.

\- Configure instance parameters and SSH key pairs.

\- Manage infrastructure through Terraform configuration files.



\### 2. S3 Bucket

\- Create and manage Amazon S3 buckets.

\- Upload objects to S3 using Terraform.

\- Manage storage resources as Infrastructure as Code.



\### 3. S3 Static Website Hosting

\- Configure Amazon S3 for static website hosting.

\- Upload website files using Terraform.

\- Manage website resources through configuration files.



\### 4. VPC and Networking

\- Create an Amazon Virtual Private Cloud (VPC).

\- Configure public and private subnets.

\- Provision EC2 instances and security groups.

\- Configure Internet and NAT gateways for network connectivity.



\### 5. Terraform State Locking

\- Explore remote Terraform state storage using Amazon S3.

\- Configure state locking to help prevent concurrent state modifications.

\- Manage Terraform backend configuration.



\## Technologies Used



\- \*\*Cloud:\*\* Amazon Web Services (AWS)

\- \*\*Infrastructure as Code:\*\* Terraform

\- \*\*Version Control:\*\* Git and GitHub

\- \*\*Operating System:\*\* Linux / Ubuntu

\- \*\*Services:\*\* EC2, S3, VPC, Security Groups, Internet Gateway, NAT Gateway



\## Prerequisites



\- An AWS account

\- Terraform installed

\- AWS CLI installed and configured

\- Git installed



\## Getting Started



1\. Clone the repository:



&#x20;  ```bash

&#x20;  git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git

&#x20;  ```



2\. Navigate to the required Terraform project directory.



3\. Initialize Terraform:



&#x20;  ```bash

&#x20;  terraform init

&#x20;  ```



4\. Validate the configuration:



&#x20;  ```bash

&#x20;  terraform validate

&#x20;  ```



5\. Review the planned changes:



&#x20;  ```bash

&#x20;  terraform plan

&#x20;  ```



6\. Create the infrastructure only after reviewing the plan:



&#x20;  ```bash

&#x20;  terraform apply

&#x20;  ```



7\. Clean up resources when finished:



&#x20;  ```bash

&#x20;  terraform destroy

&#x20;  ```



> \*\*Note:\*\* Review each project's configuration and prerequisites before running Terraform. Some projects may require additional setup or resource names to be configured.



\## Security Notes



\- Never commit AWS access keys, secret keys, passwords, or private SSH keys.

\- Terraform state files may contain sensitive information and should not be committed.

\- Restrict security group rules to trusted IP addresses where possible.

\- Review AWS costs before creating resources, particularly NAT gateways and running EC2 instances.

\- Configure backend resources before using remote state locking.



\## Learning Objectives



\- Practice Infrastructure as Code using Terraform.

\- Provision and manage AWS resources.

\- Understand AWS networking and storage.

\- Learn Terraform state and backend management.

\- Apply version control practices to cloud infrastructure projects.



\## Disclaimer



This repository is intended for learning and demonstration purposes. Review all configurations before deploying resources in a production environment.

