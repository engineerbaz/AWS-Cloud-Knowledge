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