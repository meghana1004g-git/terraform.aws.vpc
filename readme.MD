# Terraform AWS vpc

This module creates following resources

1.VPC
2.IGW with VPC association
3.Subnets -> public,private,database
4.Route tables -> public,private,database
5.Associations and Routes
6.EIP
7.NAT gateway
8.VPC peering with default VPC on condition
9.Route tables entries through peering


## Inputs
Project-(Required) string type. User should pass the project name
Environment-(Required) string type. User should pass the environment, values should be one of dev, prod, qa and uat

## Outputs

