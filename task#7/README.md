## Automate application deployment on VM using TF


### Steps:

- Create EC2 using Terraform.
- Find a way to push code (provided in this folder) into EC2 when terraform creates the EC2.
- Find a way to execute code on EC2 when terraform creates EC2.
- All the above steps should happen from a Terraform script. No manual intervention should be required to deploy the application.
- Your application should be accessible via your browser when you point it to <ip>:<port>. 
