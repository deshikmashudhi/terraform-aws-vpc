### VPC

This module is going to create
* VPC
* Internet gateway
* 2 Public subnets
* 2 Private subnets
* 2 Database subnets

### Inputs
* cidr_block(Required) - User has to provide cidr block
* enable_dns_hostnames(Optional) - User can provide enable_dns_hostnames, ***default is true***
* enable_dns_support(Optional) - User can provide enable_dns_support, ***default is true***
* common_tags(Optional) - User can provide common tags for all resources, default is empty.
* vpc_tags(Optional) - User can provide vpc tags for vpc resources, default is empty.
* igw_tags(Optional) - User can provide internet gateway tags for internet gateway resources, default is empty.
* public_subnet_cidr(Required) - User must provide a list of 2 public subnet CIDR.
* public_subnet_names(Required) - User must provide a list of 2 public subnet names.
* azs(Required) - User must provide 2 az.
* private_subnet_cidr(Required) - User must provide a list of 2 private subnet CIDR.
* private_subnet_names(Required) - User must provide a list of 2 private subnet names.
* database_subnet_cidr(Required) - User must provide a list of 2 database subnet CIDR.
* database_subnet_names(Required) - User must provide a list of 2 database subnet names.