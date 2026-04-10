# EC2 Basics

## What is EC2
EC2 stands for Elastic Compute Cloud. It provides virtual servers in AWS.

## Important terms
### Instance
A virtual machine running in AWS.

### Public IP
Used to access the instance from the internet.

### Private IP
Used for communication inside the VPC or internal network.

### Key pair
Used for secure SSH login to the instance.

### Security group
Acts like a firewall to control allowed inbound and outbound traffic.

## SSH example
`ssh -i mykey.pem ubuntu@<public-ip>`

## My notes
EC2 is one of the core AWS services and is commonly used to host applications.

