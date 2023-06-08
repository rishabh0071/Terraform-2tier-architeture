# Terraform-2tier-architeture

📋 Our Plan: Deploying a Two-Tier Application Architecture in AWS Using Terraform as Infrastructure as Code

📋 Why Terraform? - While it is possible to manually create each component of our infrastructure using the AWS console, we have chosen to leverage Terraform as our Infrastructure as Code tool. With Terraform, we can write code that automates the deployment of the entire infrastructure with just a few clicks, streamlining the process significantly.

We will deploy the following components:

🛠 Custom VPC
🛠 Configuration of 2 public subnets
🛠 Configuration of 2 private subnets
🛠 Provisioning of Internet Gateway and NAT Gateway
🛠 Association of public route table
🛠 Association of private route table
🛠 Launching 2 EC2 instances with bootstrapped Apache in public subnets
🛠 Launching 1 RDS MySQL micro instance in a private subnet
🛠 Setting up security groups for the web tier and database tier
🛠 Configuration of Load Balancer with LB Target and Listener
