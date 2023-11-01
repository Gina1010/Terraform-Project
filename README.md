# terraform-Project

#### Date: 30/10/2023
#### Date: 31/10/2023
#### Author :Gina Tetteh
#### Purpose : To create a simple infrastructure using Terraform.
 This repository is used to demonstrate the use of Terraform in creating and managing infrastructure on cloud platforms and in this our project we used AWS

 # objective of this project
 Creating a secure VPC environment in AWS using Terraform where an EC2 instance is running an Nginx web # server. The EC2 instance should reside within a private subnet and should be accessible to the outside ## world via a load balancer. Traffic to the EC2 instance should be routed through a NAT gateway.

# Files that were created
    data.tf
    provider.tf
    variables.tf
    ec2.tf
    main.tf
    outputs.tf0
    store.tf
    vpc.tf

# To deploy this infrastructure;

   download and instatll terraform by adding the path to your system environent variables

   Fork or clone the repository to your local environment
   
   Move into the cloned repository, ceate a branch and switch to it
   
   Change directory into the src directory, which contains the main.tf file
   
   Go through the code and read the comments, and modify the code as necessary
   
   Run terraform init, to initialize the terraform provider configuration
   
   Run terraform plan, and terraform apply to have the resources created
   
   Run terraform destroy to destroy all resources after you're done


  # configuration of the 22 resources provisioned

    VPC
    Public Subnet 1
    Public Subnet 2
    Private Subnet
    NAT Gateway
    Internet Gateway
    Load Balancer
    Load Balancer Listener
    Elastic IP (eip)
    Target Group
    Route Table Association 1
    Route Table Association 2
    Route Table 1
    Route Table 2
    Target Group Attachment
    EC2 Instance
    Instance Security Group 1
    Load Balance Security Groups 2
    SSM Parameter Store 1
    SSM Parameter Store 2
    SSM Parameter Store 3
    SSM Parameter Store 4
    
#### CONCLUSION###
    This is a successfully completed setting up of a VPC and running EC2 instances on your private network and have the Application Load Balancer to route the traffic to           the instances.
    i also tested the NGINX server running on the EC2 instance.

  
    

    



