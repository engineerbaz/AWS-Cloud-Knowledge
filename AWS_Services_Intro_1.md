
Total 165+ services covering Compute, Networking, Security, business application, IoT and etc

# COMPUTE

## EC2:
- ElasticCompute Cloud EC2 for any compute service of RAM & CPU 
- Could be on Windows or Linux

## LightSail
- Both LS & EC2 are compute service but the difference is 
  - Complete package (including CPU, RAM. HDD, networking )
  - No scaling in LS
  - LS is only public
  - Monthly charges

- VPS server on an hourly basis with complete package (CPU, RAM, HDD, data OUT service) 
- LS is fixed-configuration and no communication in between to LSs

## ECR - Elastic Container Registry
Store and manage Docker Images for containers 
Containers are 

## ECS - Elastic Container Service 
Service where images run to make containers like Docker

## EKS Elastic Kubernetes Service 
For orchestration of containers like Kubernetes 

## Lambda
Serverless architecture 
Can run any code without provisioning /managing server 
Pay only for compute when it is scheduled ( no need to run  server every day)

## Batch
Enables to run hundreds of computing jobs on AWS 

## Elastic BeanStalk
Deploying web application (build pack ) on Ruby/Java/PHP/NodeJS// to AWS, it will deploy using Apache/Nginx/IIS
Free service 

------

# STORAGE

## S3 - Simple Storage
- Like Google Drive/One Drive
- S3 in AWS
- Google cloud Storage In Google , Block in Azure , OSS in Alibaba
- Virtually unlimited. 
- Max. PUT size is 5GB
- Object can be uploaded of max 5TB 
- Works on Linux & Windows both

## EFS - Elastic File System 
- works on Linux 
- Like NFS
- Elastic means  can grow up and down
- Connect using IP of DNS name

Object = dynamic
Block = Fixed like HDD

## FSx
- FsX = for Windows 
- It needs Active Directory 

EFS uses EXT4
FSX uses SMB in window 

## S3 Glacier
- Glacier like archive for long time 
- 9.999999999 % durability
- Police record, medical &  financial record. 
- Cheap service 

## Storage Gateway
- On Prem & Cloud = Hybrid
- Need VPN
  
Cache based = main data in cloud and cache on-prem
Volume-based. =  data of branch to move to HQ

## Backup 
To schedule backup of any service 

--------------
# DATABASE

## RDS Relational DB 
- suite of DB
- DB Server can run 6 types of DB

* Arora (AWS propertiship)
* Postgre SQL, MYSQL, MariaDB --  Community based (They are OpenSource but needs to pay for machine/compute) 
* Oracle & Microsft = License & Compute Charges also 

Oracle license (per month charges )
 
EE Enterprise (6 months free 
SE = Standard Edition

Microsoft license 
Express &  Web --  Free
Standard & Enterprise -- charged

## DynamicDB 
No SQL query like MangoDB

## Elastic-CACHE
- Redis and Memcached (Open Sourced, server cost is charged)
- Popular for Gaming, FinTech, IoT

## Neptune
- Fast reliable graph date bas
- Data Set for an

## RedShift
Like Data warehouse 

## Quantum Ledger DB
- Transparent 
- Fully managed (managed by AWS)
- Immutable 

## Document DB
MongDB compatible DB

Lab for RDS & DynamicDB

--------------

# NETWORK & CONTENT DELIVERY 

Network services Works on Layer 2 /3 and 4 
Content delivery = sharing caching data 

VPC = Virtual Private Cloud 
Network of Router, Switches, Firewall 
VPN, NAT Gateway

All Nodes (Routers, Switch etc) are virtual as they are not physical

Can a VPC consist of multiple region VMs? No

## Cloud Front
- It is like CDN Cache Data Network 
- Clone of your data can be placed in different location where your user location so low latency and fast

## Route 53
- 53 port number 
- DNS based service 
- Domain Name ,DNS record, Zones

## API GW
- monitor/create publish APIs 
- API = Application Programmable In

## Direct Connect 
- The connection between your location and AWS 
- Dedicated fiber line
- Till 10Gbps speed, Where VPN is around 300mbps (or depends on speed you have)

We can use any other DNS services than route 53, can we?  YES but no routing functionality 


## APP mesh
For E2E visibility of microservices for high availability


## Cloud Map 
Discovery service of  all your running services 

## Global Accelerator
- Network Layer service direct traffic to optimal end points 
- Improves availability

---------------------

# DEVELOPER TOOLs

## Code Star 
Develop/build & deploy  apps on AWS 

Code Star & BeanStalk slightly overlaps ?

Code Star is like to VS Code 
At Beanstalk is a real location where the app is deployed ( can be deployed in Docker, lambda function 

Supports JS, Ruby, Python PHP

## Code Commit
Source Control Service Like GIthub, Gtlab, Bitbucket

## Code Build
Compiles code and run test & produce software
Dry run (unit testing)

## Code Deploy
Automates software deployment to EC2, Lambda or on-prem

## Code PipeLine
Its continuous integration and continuous integration for update

## Code Cloud9
Its IDE (Integrated Development Environment) like Eclipse, visual code, atom & sublime

## X-Ray
For analysis, debug and troubleshooting

debug for coding
trouble for infra issues  

--------------------

# MANAGEMENT & GOVERNANCE
 

## AWS Organization 
For consolidated billing and control of multiple accounts

## Cloud Watch 
Monitoring service and alert as well
Can work for EC2, DynamicDB Table, RDS 

## Auto Scaling 
Horizontal scaling 

## Cloud Formation 
A Common Language to describe Cloud network (that is used for future reference ) 
Infra aaS
YAML, JASON can be used.
Deployment manager in GCP, Resource Manager in Azure 
Terraform can make any resource

Programing for App development 
Coding for Infrastructure

## Cloud Trail 
Audit logs for compliance 
Risk auditing

## AWS Config 
For enabling assess audit and evaluate configuration 

## OpsWork
Its a Configuration Management 
Ansible, 
Allow automated Config management
Chef & Puppet = opswork

## Service Catalog
Create catalog IT services


## System Manager 
For getting Inventory management 
Help in getting access in VMs Using SDK (without Putty)


## Truster Advisor 
For suggestion to reduce cost, service 

## Managed Service 
Se of service for automating infra management task 

## Control Tower 
To set up a secure account

## License Manager 
For license migration
BYOL = Bring Your Own Li

Well Architecture Tool
For suggesting best practices

## Health Dashboard
NMS of regions

## Chatbot
To automate answer queries using SLACK

