# AWS VPC and EC2 Instance Provisioning Using Terraform
This project focuses on automating the setup of AWS infrastructure using Terraform. I have created a custom Virtual Private Cloud (VPC) with a CIDR block of 10.0.0.0/16, configured a public subnet within that VPC, and attached an internet gateway to enable internet access. A route table has been created and associated with the subnet to manage routing. Additionally, I set up a security group that allows SSH access on port 22, ensuring secure remote access to the instance. Finally, an EC2 instance is launched inside the configured subnet using these settings.

The main purpose of this project is to practice and demonstrate the use of Infrastructure as Code (IaC) with Terraform, ensuring a consistent and repeatable way of provisioning AWS resources. By using Terraform, managing cloud infrastructure becomes more efficient and automated, reducing manual steps and human error.

Technologies used in this project include Terraform and several AWS services such as VPC, EC2, Subnets, Internet Gateway, Route Tables, and Security Groups.

To use this setup, install Terraform and configure the AWS CLI with your credentials. Clone the repository, initialize Terraform using the terraform init command, and then apply the configuration with terraform apply. Terraform will automatically create all the resources as defined in the configuration files.

Make sure your AWS account has the necessary permissions and billing setup before running this project.
