# iac-terraform
Create a Provider for AWS.
Create an AWS key pair.
Create a VPC (Virtual Private Cloud in AWS).
Create a Public Subnet with auto public IP Assignment enabled in custom VPC.
Create a Private Subnet in customer VPC.
Create an Internet Gateway for Instances in the public subnet to access the Internet.
Create a routing table consisting of the information of Internet Gateway.
Associate the routing table to the Public Subnet to provide the Internet Gateway address.
Creating an Elastic IP for the NAT Gateway.
Creating a NAT Gateway for MySQL instance to access the Internet (performing source NAT).
Creating a route table for the Nat Gateway Access which has to be associated with MySQL Instance.
Associating the above-created route table with MySQL instance.
Create a Security Group for the WordPress instance, so that anyone in the outside world can access the instance by SSH.
Create a Security Group for Mysql instance which allows database access to only those instances who are having the WordPress security group created in step 9.
Creating a Security Group for the Bastion Host which allows anyone in the outside world to access the Bastion Host by SSH.
Creating a Security Group for the MySQL Instance which allows only bastion host to connect & do the updates.
Launch a Webserver Instance hosting WordPress in it.
Launch a MySQL instance.
Remote access to html page and perform some configuration.
![image](https://github.com/RAJanNAT619/iac-terraform/assets/41659947/afd1e67b-011a-40ed-89da-0f6071ebdf9e)


