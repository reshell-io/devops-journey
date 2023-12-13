## Load Balancing


### Steps:

- Create a VPC
- Create 2 Public Subnets
- Create 2 EC2 instance in different (public subnets)
- Inside EC2#1:
  - Deploy NGINX server and edit the configuration so it shows **Hello from EC2#1**
- Inside EC2#2:
  - Deploy NGINX server and edit the configuration so it shows **Hello from EC2#2**
- Create an Application Load Balancer (ALB) and point it to these two EC2 instances.
- Confirm in your browser that your application is accessible using the Load Balancer's DNS name.