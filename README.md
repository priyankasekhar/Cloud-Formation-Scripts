# Cloud-Formation-Scripts
Cloud formation scripts for setting up AWS environments

clf.txt consists of a cloudformation script for setting up an AWS environment with the following:
1. Two EC2 instances, one private and one public.
2. One VPC
3. Two public subnets
4. Two private subnets
5. Route Tables with the appropriate subnets associated with them
6. One internet gateway attached to the VPC
7. Creating security groups and attach it to the instances
8. Elastic Load Balancer and configure the health check
9. Creating a NAT gateway.
