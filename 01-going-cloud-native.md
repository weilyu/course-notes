# Course 1: Going Cloud-Native

## Overview

Six Advantages and Benefits of Cloud Computing

- Trade capital expenses for variable expense
- Benefit from massive economies of scale
- Stop guessing capacity
- Increase speed and agility
- Stop spending money on running and maintaining data centers
- Go global in minutes

Things need to consider while choosing the region
- Latency
- Cost
- Compliance
- Service availability (some regions may have some new services you want to try)

Region -> Availability zone

## Compute

Services
1. Elastic Compute Cloud (ED2)
2. Lightsail
3. Lambda (run code without provisioning or managing servers)
4. AWS Container Services
   - Amazon Elastic Container Service (Amazon ECS)
   - Amazon Elastic Container Service for Kubernetes (Amazon EKS) 
   - AWS Fargate

## Network
Virtual Private Cloud (VPC) structure
- [Subnets](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html), may be in different AZs
- Internet Gateway (IGW) with route table
- Load balancer (ELB)
- Virtual Private Gateway (VGW)

[CIDR Notation](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing)

## Storage

Services
- S3: object-level storage
- RDS: block-level storage
- [EFS](https://aws.amazon.com/ebs/?ebs-whats-new.sort-by=item.additionalFields.postDateTime&ebs-whats-new.sort-order=desc)