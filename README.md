# Project-Configure a Virtual Private Cloud (VPC)

### The steps below outline the steps involved to create a VPC with public and private subnet and launch an Amazon EC2 instance. Create bastion host instance in public subnet to access the resources securely in the private subnet

**Step 1: Create a VPC using AWS Management Console** 

- VPC can be by created using VPC wizard with predefined configurations or can be created manually

**Step 2: Create a public and private subnet, Internet Gateway(IGW) and a Network Translation Gateway(NAT)**

**Step 3: Configure the route tables**

- Configure the route table associated with private subnet to connect securely to the internet through a NAT gateway
- Configure the route table associated with public subnet to connect directly to the Internet Gatway(IGW) for the internt bound traffic.

**Step 4: Launch and configure a bastion host instance**

- Lanuch and configure a Bastion host instance in public subnet to securely connect to the resources in the private subnet

**Step 5: Launch and EC2 instance**

- Launch an EC2 instance in the private subnet

**Step 6: Check the connectivity of the EC2 instance**

- Check and evaluate the internet connectivity of the EC2 instance

<p align="center">
  <img src="https://user-images.githubusercontent.com/15687491/155752219-eeec5b21-61a8-4e97-9de1-dc4f2765a31a.png" alt="Architecture Diagram of the VPC with subnets"/></p>
<p align="center"> 
  <em>Architecture Diagram of the VPC with subnets</em>
</p>
