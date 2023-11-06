# iac-terraform
1. Create a Provider for AWS.
2. Create an AWS key pair.
3. Create a VPC (Virtual Private Cloud in AWS).
4. Create a Public Subnet with auto public IP Assignment enabled in custom VPC.
5. Create a Private Subnet in customer VPC.
6. Create an Internet Gateway for Instances in the public subnet to access the Internet.
7. Create a routing table consisting of the information of Internet Gateway.
8. Associate the routing table to the Public Subnet to provide the Internet Gateway address.
9. Creating an Elastic IP for the NAT Gateway.
10. Creating a NAT Gateway for MySQL instance to access the Internet (performing source NAT).
11. Creating a route table for the Nat Gateway Access which has to be associated with MySQL Instance.
12. Associating the above-created route table with MySQL instance.
13. Create a Security Group for the WordPress instance, so that anyone in the outside world can access the instance by SSH.
14. Create a Security Group for Mysql instance which allows database access to only those instances who are having the WordPress security group created in step 9.
15. Creating a Security Group for the Bastion Host which allows anyone in the outside world to access the Bastion Host by SSH.
16. Creating a Security Group for the MySQL Instance which allows only bastion host to connect & do the updates.
17. Launch a Webserver Instance hosting WordPress in it.
18. Launch a MySQL instance.
19. Remote access to html page and perform some configuration.

![image](https://github.com/RAJanNAT619/iac-terraform/assets/41659947/afd1e67b-011a-40ed-89da-0f6071ebdf9e)


