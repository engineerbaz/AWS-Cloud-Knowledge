
Total 165+ services covering Compute, Networking, Security, business application, IoT and etc

# COMPUTE

## EC2:
- ElasticCompute Cloud EC2 for any compute service of RAM & CPU 
- Could be on Windows or Linux

## LightSail
- Both LS & EC2 are compute service but the difference is 
    -- Complete package (including CPU, RAM. HDD, networking )
    -- No scaling in LS
-- LS is only public
-- Monthly charges

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
