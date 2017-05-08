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


CloudFormation_openvpn.txt is a template for setting up OpenVPN with the necessary configuration.

Allows the user to select the target environment, any existing key pair for SSH purpose, Subnets to attach with the EC2 instance, choose the VPC to attach with the EC2 instance, instance type, IP CIDR range

The script maps the instance type to the existing AMI in the region, opens up specific ports in the security groups for the OpenVPN. 

Finally, the script outputs the instanceID, Availability zone, DNS Name and IP address of the newly created instances. 


