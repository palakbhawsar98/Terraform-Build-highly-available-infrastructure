# Build highly available infrastructure using Terraform

This project involved the creation of a virtual private cloud (VPC) and associated infrastructure using the Infrastructure as Code tool, Terraform. The aim was to create a reliable and scalable environment to host a static website.
To achieve this, I first created a VPC and then created subnets in two different availability zones. I also set up a NAT gateway and an internet gateway to enable communication between the VPC and the internet. In addition, I created EC2 instances in each of the subnets, with Apache server installed using user data scripts to host the static website.

For step by step implementation, follow this [article](https://palak-bhawsar.hashnode.dev/terraform-create-vpc-subnets-and-ec2-instances-in-multiple-availability-zones)

![vpcnew drawio](https://github.com/palakbhawsar98/Terraform-Build-highly-available-infrastructure/assets/69889600/d59c8547-63e1-4535-bc56-757faa0a54d0)

![terra drawio](https://github.com/palakbhawsar98/Terraform-Build-highly-available-infrastructure/assets/69889600/783c315e-1cec-4cb0-8879-3f3c304a9b26)


