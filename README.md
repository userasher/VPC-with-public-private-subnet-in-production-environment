# VPC-with-public-private-subnet-in-production-environment
This project demonstrates how to create a VPC with public-private subnet and how to secure your application within the subnet in the production environment

according to this image is architectuer of our project:

![image](https://github.com/userasher/VPC-with-public-private-subnet-in-production-environment/assets/109350583/2971ed3f-9fc7-4818-bbb7-3f8779e4b7da)


prerequisites:

![image](https://github.com/userasher/VPC-with-public-private-subnet-in-production-environment/assets/109350583/afd85816-6334-486e-8a9e-ffae5ad09d1b)

you should also know how to create AWS vpc,configure it and creating EC2 instances,cinfigure it using aws website/console


What we are going to do in this project?
--> we are going to create a VPC having public and private subnets and we going to create it 
in 2 availablity zones.

general purpose good to know info. to understand this project:::

✅Route tables are those which define how to route the traffic in the particular subnet.

✅Elastic IP address is called static IP address which never changes that is even if  instance
goes down and comes back it remains the same.

✅NAT gateway will mask the IP address of your instance/application with the IP address of the subnet/NAT gateway 
for security of the instance /application.

What are auto scaling groups?

--> ✅Amazon EC2 Auto Scaling helps you ensure that you have the correct number of Amazon EC2 instances available to handle the load for your application. 

✅You create collections of EC2 instances, called Auto Scaling groups. You can specify the minimum number of instances in each Auto Scaling group, 
and Amazon EC2 Auto Scaling ensures that your group never goes below this size. 

✅You can specify the maximum number of instances in each Auto Scaling group, 
and Amazon EC2 Auto Scaling ensures that your group never goes above this size. 

✅If you specify the desired capacity, either when you create the group or at any time thereafter, 
Amazon EC2 Auto Scaling ensures that your group has this many instances.

✅If you specify scaling policies, then Amazon EC2 Auto Scaling can launch or terminate instances as demand on your application increases or decreases. 






