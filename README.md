# Terraform-AWS-3tier-Architecture_Project

Deploy a three-tier architecture in AWS using Terraform.

 ## Requirements-

1. AWS account
2. AWS CLI
3. Terraform
4. GitHub account
5. Git
6. Visual studio code

## Production Network-
1. Design and build a 3 tier architecture 
2. Create 6 subnets out of which 2 should be public with names subnet A & B and should be private subnet C,D,E & F.
3. Launch instances in all subnets and name them as per the subnet that they have been launched in. 
4. Allow Subnet C & Subnet D to send internet requests
5. Datbase connect to Subnet E & Subnet D
6. LoadBalancer connect to Subnet A & Subnet B
7. Manage security groups and NACLs
8. build resources in AWS using Terraform

## Steps-
1. Launched an EC2 Instance for creating the server and enabled Auto Scaling on these instances.
2. Used VPC for creating private cloud, vpc resources such as subnets, routables, igw, nat gateway
3. Created an RDS Instance with database configuration.
4. S3 for storing the logs of the application
5. Configured security groups, networking, and traffic rules between EC2 and RDS.
6. Automated infrastructure by using Infrastrcture as a code (IAC) to that is terraform.
 
## Deployment-
2. create a simple address book application that is accessible from your browser, connect to using the Database endpoint, use terraform to create various AWS services such as VPC with public and private subnets, NAT gateways, security groups, RDS, ALB, SNS, ASG, and route 53.
3. Also use DevOps tools such as GitHub, Git, visual studio code, and AWS CLI to complete this project. This project helps to become efficient in Terraform, learn infrastructure as code (IaC) and how to build resources in AWS using Terraform.
4. deploy a three-tier architecture in AWS using Terraform.

### Project Diagram-

![alt text](https://github.com/Sharadp2124/Terraform-AWS-3tier-Architecture/blob/main/Terraform-AWS-3tier-Architecture%20Diagram.png).
