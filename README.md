# AWS VPC Networking Lab

## Project Overview

This project documents my hands-on experience building and configuring a Virtual Private Cloud (VPC) in Amazon Web Services (AWS).

The goal is to understand how AWS networking works in practice, including network segmentation, subnet design, routing, and the deployment of resources within a cloud environment.

The lab is also an opportunity to explore how network architecture and security configurations contribute to building a more secure and resilient cloud infrastructure.

## Project Objectives

The objectives of this project are to:

- Understand AWS VPC networking.
- Create public and private subnets.
- Configure route tables and an Internet Gateway.
- Deploy an Ubuntu EC2 instance.
- Apply basic cloud network security controls.

## AWS Services and Technologies

- **Amazon VPC:** Used to create an isolated virtual network.
- **Amazon EC2:** Used to deploy an Ubuntu virtual server.
- **Internet Gateway:** Configured to provide internet connectivity.
- **Amazon EBS:** Used for EC2 storage.
- **Security Groups:** Used to control network traffic.
- **AWS KMS:** Used for EBS volume encryption.
- **Ubuntu Server:** Operating system running on the EC2 instance.

## Network Architecture

### VPC Configuration

- VPC IPv4 CIDR: `10.0.0.0/16`
- Number of Availability Zones: 2
- Total number of subnets: 4
- Public subnets: 2
- Private subnets: 2
- Internet Gateway: Created and attached to the VPC.

The network was designed to distribute subnets across two Availability Zones, providing network segmentation and a foundation for building resilient cloud infrastructure.
