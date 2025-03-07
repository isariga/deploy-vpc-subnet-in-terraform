# deploy-vpc-subnet-in-terraform

Terraform allows you to define and deploy an AWS VPC with subnets using infrastructure as code. 
It automates network provisioning, ensuring consistency, scalability, and easy management of cloud resources.

Step 1: Configure AWS CLI
Before using Terraform, configure your AWS credentials.
Install AWS CLI
    aws --version
Configure AWS CLI
    aws configure
    ![aws configure](https://github.com/user-attachments/assets/da925e75-0934-4539-9df5-2c3a1ef2e8d3)

Step 2: Install Terraform
Download Terraform from Terraform Download.
Install Terraform and verify
    terraform -version

Step 3: Create a Terraform Project Directory
Create a new directory and navigate into it
Create a main.tf file

Step 4: Write Terraform Configuration for VPC and Subnet
Open main.tf and add the following Terraform code![code](https://github.com/user-attachments/assets/6d7539f2-adcd-406c-9944-f1c25e5005ee)

Step 5: Initialize Terraform
    terraform init![init](https://github.com/user-attachments/assets/7191b99a-6de2-4d15-8772-baff78d9b531)

Step 6: Validate and Plan Terraform Configuration
    terraform validate
    terraform plan

Step 7: Apply Terraform to Create VPC and Subnet
    terraform apply![3resources](https://github.com/user-attachments/assets/1fc7ad3b-ded4-43e5-8a1c-c8925dc6da70)

Step 8: Verify the Deployment
Check your AWS Management Console
Go to VPC Dashboard → Your VPCs
![vpc](https://github.com/user-attachments/assets/07c56c5b-e013-480a-a279-497976fb7fc4)
Go to Subnets to see the created subnet
![subnets](https://github.com/user-attachments/assets/8dac5693-5382-410a-9e0a-5f41f343b54c)

Step 9: Destroy Terraform Resources
    terraform destroy![destroy](https://github.com/user-attachments/assets/34f51cb7-d65e-4834-b6cb-505db945a133)
