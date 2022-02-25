# Project-Configure a VPC

## Create a VPC in AWS cloud with public and private subnet

In this project I built an Amazon Virtual Private Cloud and deployed AWS resources in it.

- First I built a Virtual Private Cloud(Amazon VPC) and create a public  and private subnet, Internet Gateway(IGW) and a Network Translation Gateway(NAT).
- Next configure the route table associated with private subnet to connect securely to the internet through a NAT gateway
- Then configure the route table associated with public subnet to connect directly to the Internet Gatway(IGW) for the internt bound traffic.
- Lanuch and configure a Bastion host instance in public subnet to connect to the resources in the private subnet
- Launch an EC2 instance in the private subnet.
- Check and evaluate the internet connectivity of the EC2 instance

![VPC](https://user-images.githubusercontent.com/15687491/155752219-eeec5b21-61a8-4e97-9de1-dc4f2765a31a.png)

