# AWS VPC: Public and Private Subnets

## Aim
To create a Virtual Private Cloud (VPC) containing one public subnet and one private subnet using the AWS Management Console.

## AWS Region
Asia Pacific (Mumbai) — `ap-south-1`

## Configuration
- VPC CIDR: `10.0.0.0/16`
- Public subnet CIDR: `10.0.1.0/24`
- Private subnet CIDR: `10.0.2.0/24`

## Procedure
1. Sign in to the AWS Management Console.
2. Open the VPC service.
3. Create a VPC.
4. Create one public subnet and one private subnet.
5. Attach an Internet Gateway to the VPC.
6. Add the route `0.0.0.0/0` to the Internet Gateway in the public route table.
7. Associate the public subnet with the public route table.
8. Associate the private subnet with the private route table.
9. Verify the subnet and route table configurations.

## Result
The VPC with public and private subnets was configured using the AWS Management Console. The configuration should be verified using the uploaded screenshots.

## Screenshots
The repository contains screenshots of the VPC, subnet list, public route table, and private route table.
