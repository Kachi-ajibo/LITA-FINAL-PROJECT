# LITA FINAL PROJECT
 Building a Scalable Web Infrastructure for "SmartShop" using the AWS infasructure.
### summary of this project
SmartShop is a fictional mid-sized retail company that wants to expand its
business by launching an online store. As they anticipate an increase in web traffic due to
marketing campaigns and seasonal sales, SmartShop requires a robust and reliable web
infrastructure to ensure smooth customer experiences.
As a cloud practitional, i'm commited to building a scalable web infastructure tailored to meet the need of Smart Shop and my goals are to build infastructure that:
  support anticipated growth with flexible resource allocation.
• Ensure high availability and consistent user experience.
• Implement strong security measures to protect customer data.
• Be cost-effective and optimized for performance
Walk with me through this process.
### created a security group
security group is a virtual firewall that controls traffic to and from Amazon EC2 instances. 
I created a Security Groups to control inbound and outbound traffic to my EC2 is instances.Allow HTTP (port 80) and HTTPS (port 443) traffic from the internet and alsoo Restrict SSH (port 22) access to your IP addresses only
Below are pictorial illustration of my  security group.
![security group](/Security-group.png)
### created a Network ACLs
Network ACLs are a layer of security that acts as a firewall for my VPC Subnet
They control incoming and outgoing traffic based on rules that I define.
I defined the outbound and inbound rule to  Allow HTTP (80) and SSH (22).
Below is an image.
![Network ACLs](/Network-Config.png)
### Launched an EC2 instance.
 EC2 Instance is a virtual server in the cloud that provides computing resources, such as CPU,memory,and storage.
 I used an Amazon Machine Image (AMI)  Amazon Linux 2 and a VPC that can allow traffic from anywhere in association with a public subnet.
 This Ec2 instance is configured to meeet the need of Smart shop in the most unique way possible.
 Below is an image of it.
 ![EC2 Instance](/EC2-Instance.png)
 ## Tested my EC2 instance to Comfirm it is working. I did this by running the public IP address on my broswer.
 ![Apache](/Apache.png)
 
 