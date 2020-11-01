# Elastic Compute Cloud (EC2)

Offers Scalable computing capacity that allows a business subscriber to run app and program


### Benefit
- Elastic Web-Scale
  - Increase or decrease in minutes
- Completely Controlled
- Flexible Cloud Hosting
- Integrated 
  - Works with most services as S3, RDS, VPC
- Reliable 
- Secure
- Inexpensive
- Easy to start


### Features
- EC2 virtual computing is instance
- Preconfigured templates are AMI (Amazon Machine Image)
- Diverse processor capacity , memory, storage and networking for instances called instance type
- Secure login info using Key Pairs
- Persistent storage volumes for data using EBS (Elastic Block Store) known as Amazon EBS volume
- Multiple physical locations for resources  for EBS called region and AZ
- A firewall to specify source protocol , port and IP range that can reach the instances by using Security Group
- Storage volume for temporary data that’s deleted when instance stops known as instance store volume
- Hibernation for EC2 instance gives u to launch EC2 instance , setting up as desired, hibernate them and bring them back to life when needed 
- Metadata, known as tags, can be create and assign to Amazon EC2



## EC2 Instance Type
- Current Generation
- Previous Generation 


- General Purpose
- Compute Optimized
- Memory Optimized
- Storage Optimized
- Accelerated Computing
  

## Amazon Machine Image (AMI)
- Provide the information required to launch an instance,  which is a virtual server in the cloud
- AMI includes
  - Template for the root volume for instance (OS, application server & application)
  - Launch permission, controls which AWS account can use the AMI to launch
  - A block device mapping that specifies the volumes to attach to the instance when launched
- Snapshot of your
- Four Types of AMI

- EC2 & EBS should be in the same region and AZ

## Amazon Elastic Block Store (EBS)
- Provides persistent, highly available, consistent, low-latency block storage volume for use with EC2
- Each EBS volume is automatically replicated within AZ to protect you from component failure, offering high availability and durability.
- High performance volume
  - SSD, HDD
- Availability (99.999%)
- Encryption
  - Data at rest & Data in transit
- Snapshot
  - Protect data by creating point in time snapshot of EBS
- Access Managemnet 
  - Flexible access control policies allows to specify who can access which EBS
- Elastic Volume
- EC2 is hosted in multiple locations world-wide (Location composed of regions and AZ) 
- Resources arent replicated across regions unless user do so specifically

## EC2 Security Group
- SG act as virtual Firewall  to control traffic for one or more instance 
- When Instance launched , it associated with one or more SG
- User can add rules to each SG to allow to and from traffic
- User can modify the rule for SG
- Applied to all instance that are associated with this SG


## EC2 Elastic IP 
- Elastic IP  address is Static IPv4 address designed for dynamic cloud computing
- An elastic IP is associated with AWS Account
- User can mask the failure of an instance or software by rapidly remapping the address to another instance 
- Dont support IPv6
- 
## EC2 Pricing
- On-demand
  - Pay as you Use 
- Spot instance
  - Allow to request spare EC2 capacity for up to 90% off the on-demand price
  - 24 HOURS leased time, 3 -4 minute to termination time
- Reserved 
  - For Longer time
- Dedicate
  - For Hardware 
  - Dedicated host is a physical EC2 server for use
- Saving Plan
  - Flexible pricing model 
  - Offers lower prices on EC2, regardless of instance family, size, OS, tenancy or AWS region
- Per Second Biling
  - Pay only what is in use.
