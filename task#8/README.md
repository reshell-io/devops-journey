## Automating Infrastructure using TF


### Steps:

- Create a VPC
- Create 2 Public Subnets
- Create 2 Private Subnets
- Create an EC2 inside the private subnet with no Public IP.
- Create a Security Group for your EC2 with SSH and HTTP ports open.
- SSH into EC2 inside the private subnet.


#### Questions

- How can you access an EC2 in a private subnet?
- What network components are required to access a private subnet?
- What is a Bastion Host?
- What is the use-case for private subnets vs public subnets?
