# **AWS Service Introduction **
------------------------------------
Total 165+ services covering Compute, Networking, Security, business application, IoT and etc
- Compute 
- Storage 
- Network
- Database 
- migration & transfer
- Analytics
- Special (IoT/ML/AI)

[AWS Documentation ](https://docs.aws.amazon.com/index.html)

# COMPUTE

## EC2:
- Pure Compute Service based on RAM & CPU
- ElasticCompute Cloud EC2
- Could be on Windows or Linux
- On-demand, spot
- Per hour & Per second based pricing

## LightSail
- VPS Server
- Both LS & EC2 are compute service but the difference is 
  - Complete package (including CPU, RAM. HDD, networking )
  - No scaling in LS
  - LS is only public
  - Monthly charges

- VPS server on an hourly basis with complete package (CPU, RAM, HDD, data OUT service) 
- LS is fixed-configuration and no communication in between to LSs

## ECR 
- Elastic Container Registry
- Store and manage Docker Images for containers 


## ECS 
- Elastic Container Service 
- Service where images run to make containers like Docker

## EKS 
- Elastic Kubernetes Service 
- Allows to run Kubernetes on AWS
- For orchestration of containers like Kubernetes 

## Lambda
- Serverless architecture 
- Can run any code without provisioning /managing server 
- Pay only for compute when it is scheduled ( no need to run  server every day)

## Batch
- Enables to run hundreds of computing jobs on AWS 
- Free service , just need to pay only EC2 resource

## Elastic BeanStalk
- Deploying web application (build pack ) on Ruby/Java/PHP/NodeJS/Go & Docker to AWS, it will deploy using Apache/Nginx/IIS
- Free service 

## Serverless application Repository
- Managed Repository for Serverless application
- Allows to find, deploy, publish, share, store & assemble serverless architecture

--------

# STORAGE

## AWS S3 
- Simple Storage service (S3)
- Object Storage service
- Google cloud Storage In Google , OSS in Alibaba
- Virtually unlimited. 
- Max. PUT size is 5GB
- Object can be uploaded of max 5TB 
- Works on Linux & Windows both
- 99.999999999% durability

## EFS 
- Elastic File System 
- works on Linux 
- Like NFS
- Elastic means  can grow up and down
- Connect using IP of DNS name

Object = dynamic </br>
Block = Fixed like HDD

## FSx
- FsX = for Windows 
- It needs Active Directory 
- two types
  - Windows File server
    - Native windows FS
  - Lustre
    - Optimized for compute-intensive workload

EFS uses EXT4 </br>
FSX uses SMB in window 

## S3 Glacier
- Glacier like archive for long time 
- 9.999999999 % durability
- Police record, medical &  financial record. 
- Cheap service 

## Storage Gateway
- hybrid storage service that enables On Prem application to seamlessly use AWS Cloud = 
- Need VPN
  
Cache based = main data in cloud and cache on-prem </br>
Volume-based. =  data of branch to move to HQ

## Backup 
- To schedule backup of any service 
- Easy to centralize and automate the backup of data across AWS services & on-Prem


--------------

# DATABASE

## RDS 
- Relational Database Service
- Makes it easy to setup, Operate & Scale a relational DB in cloud
- suite of DB
- DB Server can run 6 types of DB
  - Arora 
    - AWS propertiship
  - Postgre SQL, MYSQL, MariaDB
    - Community based (They are OpenSource but needs to pay for machine/compute) 
  - Oracle & Microsft 
    - License & Compute Charges also 

- Oracle license (per month charges )
 - EE Enterprise (6 months free )
 - SE = Standard Edition

- Microsoft license 
  - Express &  Web --  Free
  - Standard & Enterprise -- charged

## DynamicDB 
- No SQL query like MangoDB
- Fast & Flexible, Low latency
- DynamoDB can handle more than 10 trillion requests per day and can support peaks of more than 20 million requests per second.

## ElastiCache
- Redis and Memcached (Open Sourced, server cost is charged)
- Popular for Gaming, FinTech, IoT

## Neptune
- Fast reliable graph Database
- Core of Neptune is for HP graph DB , can store billions of relationships and queries in msec latency

## RedShift
- Amazon Redshift is a fast, fully managed, petabyte-scale data warehouse 
- Like Data warehouse 

## QLDB 
- Quantum Ledger DB
- Fully Managed Ledger Database
- Transparent, Immutable & Cryptographically verifiable transaction log
- Fully managed (managed by AWS)


## Document DB
- MongDB compatible DB
- Fast, reliable, Fully managed

Lab for RDS & DynamicDB

--------------
# Migration & transfer

## Migration Hub
- A single location to track progress of application migration across multipleAWS & Partnar solutions
- Alos provide Key metrics and progress

## Application Discovery Service
- helps Enterprise customers to plan migration by gathering information about on-prem DC

## Database migration Service
- Helps you to migrate DB to AWS quickly & securely

## Server Migration Service
- SMS is an agentless service makes it easier and faster to migrate thousnad of on-prem workload to AWS

## AWS Transfer for SFTP

- Fully managed service enables to transfer files over SFTP (Secure FTP), into & out of Amazon S3
- SFTP is also known as SSH FTP (Secure Shell)
- used to exchange workflow across different industries (FinTech, Health, retails)

## Snowball
- petabyte-scale data transport solution that uses apploances to transfer large amount in/out to cloud

## DataSync
- Data transfer service that simplifies, automates, accelerates moving & replicating data bw on-prem storage & AWS Storage over internet or AWS DirectConnect
- It remobves the need to modify applications, Develop screipt or manage Infrastructure

---------

-----------------

# NETWORK & CONTENT DELIVERY 

Network services Works on Layer 2 /3 and 4 </br>
Content delivery = sharing caching data 

- VPC = Virtual Private Cloud 
- Network of Router, Switches, Firewall 
- VPN, NAT Gateway

All Nodes (Routers, Switch etc) are virtual as they are not physical
</br>
Can a VPC consist of multiple region VMs? No

## VPC
- Virtual Private Cloud
- Logically isolated section in AWS Cloud, resource can be launched
- both IPv4 and IPv6 can work

## Cloud Front
- Content delivery Network
- It is like CDN Cache Data Network 
- Clone of your data can be placed in different location where your user location so low latency and fast

## Route 53
- 53 port number 
- DNS based service 
- Domain Name ,DNS record, Zones
- effectively connects user requests to infrastructure running in AWS – such as Amazon EC2 instances, Elastic Load Balancing load balancers, or Amazon S3 buckets 
- and can also be used to route users to infrastructure outside of AWS

## API GW
- create/publish/maintain/monitor APIs 
- API = Application Programmable In

## Direct Connect 
- The connection between your location and AWS 
- Dedicated fiber line
- Till 10Gbps speed, Where VPN is around 300mbps (or depends on speed you have)

We can use any other DNS services than route 53, can we?  YES but no routing functionality 

## APP mesh
- For application level networking
- E2E visibility of microservices for high availability

## Cloud Map 
- Discovery service of  all your running services 

## Global Accelerator
- Network Layer service direct traffic to optimal end points 
- Improves availability

---------------------

# DEVELOPER TOOLs

## Code Star 
- Develop/build & deploy  apps on AWS 
- Dashboard for all software development

Code Star & BeanStalk slightly overlaps ?
</br>
Code Star is like to VS Code 
At Beanstalk is a real location where the app is deployed ( can be deployed in Docker, lambda function 
Supports JS, Ruby, Python PHP

## Code Commit
- Source Control Service Like GIthub, Gtlab, Bitbucket

## Code Build
- Compiles code and run test & produce software
- Dry run (unit testing)

## CodeDeploy
- Automates software deployment to EC2, Lambda or on-prem
- helps in avoiding downtime during updates /rollout

## Code PipeLine
- Its continuous integration and continuous integration for application and infrastructure update

## Code Cloud9
- Its IDE (Integrated Development Environment) like Eclipse, visual code, atom & sublime

## X-Ray
- Analyze, debug and troubleshooting

debug for coding
trouble for infra issues  

--------------------
