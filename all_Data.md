# AWS Service Introduction -  Part 3

## SERVICES - Security, Identity & Compilance


## AWS IAM 
- Enables you to Securely control access to AWS services and resources for your user
- Using IAM, can create & Manage AWS users & group & use permissions to allow & deny 

## RAM 
- resource Access Manager 
- Enables you to easily & securely share AWS resources with any AWS account or within organization
- Share AWS Transit GW, subnets configurtaion and Route 53 , 
****

## Cognito
- Lets add user sign up/in & access control to you web or mobile app


## Secret Manager
- Makes it easier to manage Secret (database cred, pwd,3rd party API Key)
- Can store & control access to these secret centrally 

## Guard Duty
- Manage threat detection service
- IDS 
- Check account
  
## Inspector 
- Automated Security product
- Check threat VM vulunerability


## Macie
- Security service that uses machine learning to automatically discover , classify & protect sensitive data 


## SSO 
- Single Sign-On (SSO) Makes it easy 

******

## Certificate Manager


## KMS
- Key Management Service
- managed service to create the encryption keys used to encrypt data

## CLoudhsm
- Hardware Security Module
- Hardware based that generate and use own encyption 

KMS > HSM

## Directory Service
- Like Microsoft Active Directory
- Managed service 
- works on windows 7 , server 2012

## WAF & Shield 
- WAF is Web Application Firewall 
- Lets you monitor web requests for Amazon Cloudfront distribution and restrict access to your contecnt
- Shiel is managed DDoS protection service that safeguards web Application running on AWS
- stateful
- 2 stype of Shield 
- shield can be attached to VMs

## Artificat


## Hub
- Like Suite
- single  place that aggregates organizes & prioritize your security

-----

# Mobile service

## Amplify
- CI of Hosting service for modern web application 

## Mobile Hub
- Featuure selection and configurtaion and automatically provisions 

## App Sync
- automatically updates the data in web and mobile application  in realtime and update data for offline users as they reconnect

## Device Farm
- App testing service taht lets you test and interact with android /IoS and web app 

## Mobile Analytics

# AR & VR 
- Augmented Reality
- service
- Virtual Reality 
- 
## Sumerian
Lets you create and run VR & AR and 3D 




## Step Function
- Makes easy to coordinate the component 


## EventBridge
- Serverless event bus service that makes easy to connect your application with data

## MQ 
- Message Queue
- Message broker service for Apache ActiveMQ taht makes it easy to setup

## SNS 
- Simple Notification service
- Via email, sms 
- for security breach, high billing
- cloud watch only generate event

## SQS 
- Simple Queue service
- For queuing service, make it easy to decouple and scale microservices , distribution systems & serverless application

## SWS
- Simple Workflow service 
- Helps developers build, run, and scale background jobs that have parallel or sequential steps


---

# COST Managemnet

## Cost Explorer
- Tool that Enables you to view and analyze your cost and usage

## Budget
- enbles you to plan service usage/Cost and instance reservation 
- how close your budget.

## Marketplace Subscription 
- Its like Google playstore for android
- Like Cisco sell Virtual Firewall
- Two prices involved
  - Owner
  - AWS resoource cost

---

# Customer Engagement

## Amazon Connect 
- CCaS = Contact Center as Service 
- Call Center services 

# Pinpoint 
- makes easy to engage customers by tracking the way in which they interact with Applications
- A targeted push Notification and mobilr engagement 
  
## SES 
- Simple Email service
- Cloud based email sending service 
- like SMTP server

---

# Business Applications

## Alexa for businsess 
- Can help people stay organized and focused thing that matter.
- Hardware 

## Chime
- Communication software

## Workmail 

## WorkSpace 
- DaaS = Desktop as a Service 
- can easily provision virtual, Cloud-based microsoft windows Desktop
- Horizan in VM 
- Zen  Desktop in Citrix 
- virtual PC in microsoft*
- Horizan in VMware 

## AppStream 2.0
- only share some or one app to user 
- ZenApp in Citrix
- RemoteApp in microsoft

## Workdocs
- Secure , file collaboration and 

## WorkLink 
- Provides secure data

----

# IoT
Internet of Things 

## IoT Core 
- secure, bi directional Communication between inter-Connected device 
  - Sensor
  - Actuators
  - Embeded microcontrollers 
  - smart Applications
  - AWS Cloud 
- possible to collect telmetry data form multiple device and store and analyze data


## FreeRTOS
- Free RealTimer OS  

## IoT Evernt 

## Greengrass

## SiteWise 
- For Industrial 

## IoT 

----

# Game 

## Gamelift 

## RoboMaker
- Robot OS  


## Managed BlockChain 
- For 

## Ground Station
- Enables you to control satellite Communication, downlink and process satellite and data 

---
===========================================================================================

# Trusted Advisor

There are 5 parameter on which basis of trusted Advisor works

## Cost Optimization
- Tells how to optimized costing 
- 
## Perfomance 
- How to manage KPI
  
## Security
- If any unused port is open
  
## Fault Tolerance 

## Service Limits
- max limit is 20 in a region


- Recent Changes
- Access management
- Exclude Items
  - supress some features/column in report
- Supports API
- Core Checks recommendation 
  - by default 4 Supports
    - Basic - Free - 7 Core checks 
      - Service Limits
      - S3 bukets permission, Security Group
    - Developer - $ 29
    - Business - $ 100
    - Enterprise - $ 15000 

=============================

# CloudTrail
For Auditing services
- Governance
  - ISO27001, 27003, PCI DSS , etc 
- Compilance
- Operational Auditing
- Risk Auditing

</br>
By default log time is 90 days , otherwise need to archive in S3 buckets for years </br>

- Integration with AWS CloudWatch logs
- Security Automation
- Security Analysis & Troubleshooting 
- Event History
- Multi Region configurtaion
- Log File encryption
- Log File Integrity Validation 
- Data Event
- AWS Lambda
=============================

## IAM
- Identity & Access Managemnet 
  - Enables you to manage access to AWS Service & resources securely.
  - Access to AWS & Authorization to service
  - Free Service
  - Global so same Username/password works on all regions

### Root account
- First time account, who sign up 
- No rule applied 
- Max options available

### IAM Features
- Shared access to AWS account
  - Grant same permission to group of people
- Multi Factore authetication 
  - 2-Factor authetication
- Identity Federation 
  - Admin can allow users who already have password 
  - incorporate Network 
- Identity information Assurance
- GRanular permission
  - Can grant different permission to different people for different resource

### Manage IAM Users & their access
- IAM Access can be created using 
  - AWS Management console
  - AWS Command Line Tool
  - API
  - SDK
  
  - Access ID - if console
- Username & password - if using chrome 


- Role > resource
- group > users 

## Manged Federated users & their permission 
- Enables Identity federation to allow existing Identities (user, group & roles) 
- supports SAML 2.0

### Best Practice
- Create individual USERS
- Manage permission with GROUPS
- Grant least PERMISSION / privilege
- Turn on AWS CloudTrail for AUDIT
- Configure strong PASSWORD 
- Enable MFA for privileged users 
- use IAM ROLES for Amazon EC2 instance
- use IAM roles for SHARE Access
- ROTATE security credentials regularly
- restrict priviliged access furtehr with CONDITIONS
- reduce or remove use of ROOT 

* Microsoft Active Directory suggestes 42 days credential change 
-------

## Virtual Tour AWS

- AWS IQ 
  - Its like a freelancing platform

- Every region has different capabilities 
  - different amount available

- Resource Groups are like favourities/bookmark

- Searcing any service
  - By Groups
  - alphabetical order
  - Writing by search


## LAB - Trusted Advisor
- Global
- If 50% information error then becomes critical 
- 

May b... Linux is comparatively more secure than windows










</br>

================================================
# LAB - CloudTrail

- CloudTrail is a regional service
- 90 days logs
- not writeable
- read only
- Trail is created for accessing data for more than 90 days 
- Log data is available after 24hours of creation of Trail
- Trail created in **North Viriginia will be globally**.
- Key Points
  - Prefix = Folder in S3
  - Tags = Labels
  - Types of Event 
    - Management = O&Management
    - Data event = logs inside of resouce
    - Insight = logs related to sign-in , out.
  - CloudTrail logs is created in a folder in S3 
  - Data Formate is YYYYMMDDT


# LAB - IAM
**Tasks**
- Create User, Group & roles
- Create & delete user access keys
- Create custom policy
- MFA
- KMS encryption configurtaion & implementation


users > human
group > combination of account/user
roles > for services
customized managed policies > policy on group
Identity provider > outside AWS

Security Status 
- MFA
- create individual IAM users 
- use group to assign perission 
- apply an IAM policy


### User
- Select AWS Access Type 
  - Access 
    - Access Key ID 
    - Secret access keys
  - Management console
    - password 

- Managed Policy
  - Can be used many users 
- Inline Policy 
  - for only one user 

## Role 
Roles can be applied on 
- AWS Service
- Another AWS Account 
- Web Identity
- SAML 2.0

================================================
# S3 
- Simple Storage Service (S3)
- Low cost, Scalable, web based
- Global Service
- Object based 
- Like PAYU (Pay As You Use)
- For storing files and folders 
- Scalable (Either 1MB or 1TB)
- Data stored in Resource called bucket
- Can store 0 byte to 5TB
- S3 charges for Storage, request, Data Transfer & Data Acceralation
- S3
  - S3 is a universal namespace, name must be unique
  - PUT = upload
  - GET = Download

- S3 Object 
  - Key = name of Object
  - Value = sequence of bytes
  - Version ID = for Versioning
  - Metadata = data about data 
Can also has ACL. 

## Amazon S3 Storage Classes
Different SC for different puposes. 

### General Purpose
  1. S3 Standard
   -  Offers high durability, availablity & performance for frequently accessed data
   -  Delivers Low latency & high throughput
### Unknown & Changing Access 
  2. Intelligent Tiering
    - When data/user-base is frequently changing 
    - using for optimizing cost by automatically movingd data to most cost efficient access tier without performance impact
    - stores data in two tiers
      - optimized for frequent access 
      - lower cost tier, optimized for Infrequent access
### Infrequent Access
  3. S3 Standard IA 
      - less frequently accessed but requires rapid access
      - lower fee than s3;
      - but Retrieval fee 
  4. S3 One Zone IA
      - lower cost for Infrequently accessed data
      - but not required multiple availablity zone data resilience
      - same as standard IA + When dependent in a single zone
### Archive 
  5. Glacier
    - Very Cheap but for archival only 
    - expedited, standard or bulk
    - a standard retrieval time takes 3 - 5 hours
  6. Glacier Deep archive
    - new for long-term data archival
    - lowest cost
    - needs 5 - 12 hours time 

## AWS Features
  - S3 batch 
  - Versioning
    - bydefault not enabled
    - Once enabled, only able to be suspend
  - MFA
    - For deletion
  - S3 Object Lock
    - Enforce WORM (Write-Once-Read-Many)
  - ..
  - Cost Allocation
  - Storage Class Analytics
  - CloudWatch Metric in S3
  - CloudTrail
  - .
  - IAM 
  - Control List 
  - ..
  - Presigned URL  
  - Audit Log
  - SSE
  - VPC Endpoint
    - data between VPC & S3 
    - Within AWS services 
  - encryption
  - Inventory
  - Amazon Macie
    - For Machine 
  - S3 Select
  - Athena 
    - analyze data in S3
    - serverless
  - Transfer Acceralation 

- Free Software for Transfer data to S3
- s3 browser
- cloud berry lab


# LAB S3 
-----
- Create S3 bucket

ARN (Amazon Resource Nummber)
arn:aws:s3:::s3bazs3

=====


# Cloudfront
- Its like CDN 
- Content Delivery Network. 
- For caching web files 
- 216 POP (205 Edge location , 11 Regional Edge Cache)

## Content Delivery

## CF Features
- Faster Perfomance & Simple
  - Requester pays 
- Can be used with other AWS Service
- Elastic 
- Reliable
- Origin Failover 



































'











































































=================


Basic AWS Job
===========
AWS
Linux basics
Network Basics

Intermediate OR advanced AWS Job
===========================
AWS
Linux
Devops
Network
Scripting (JSON, Shell, )
Security  

=================================

















