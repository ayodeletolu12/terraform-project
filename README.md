# This terraform project deploys an Apache web server on an EC2 instance in AWS cloud

## The Entire cloud infrastructure was provisioned on AWS using Terraform

### terraform init, terraform plan, terraform apply and terraform destroy

#### Below are highlights of resources provisioned for this project

1. `Create VPC`
2. `Create Internet gateway`
3. `Create custom Route table`
4. `Create subnet`
5. `Associate subnet with Route table`
6. `Create security group to allow port 22, 80, 443 (ssh, http, https)`
7. `Create a Network interface with an IP in the subnet that was created in step 6`
8. `Assign an elastic IP to the network interface created in step 9`
9. `Create Ubuntu server and install and enable Apache2 web server`