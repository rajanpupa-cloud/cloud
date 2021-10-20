# Tips for creating config for terraform

- Create a new VPC
- Create two new public subnets - with proper cidr range
- Create two new private subnets - with proper cidr range
- Create security groups - to allow/disallow traffic - associate with instances
- create instances - databases in proper subnets
- create NAT Gateway/Instance to allow internet access to the private instances
- allow traffic for database group from the private security group
- 