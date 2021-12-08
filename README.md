This terraform project deploys an EC2 instance on AWS cloud

Create VPC
Create Internet gateway
Create custom Route table
Create subnet
Associate subnet with Route table
Create security group to allow port 22, 80, 443 (ssh, http, https)
Create a Network interface with an IP in the subnet that was created in step 6
Assifn an elastic IP to the network interface created in step 9
Create Ubuntu server and install and enable Apache2 web server