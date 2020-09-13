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

## IAM
- Identity & Access Managemnet 
  - Enables you to 
  - Free Service
  - Global 

## Root account
- First time account
- Max options available

## IAM Features
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
- Grant least PERMISSION 
- Turn on AWS CloudTrail for AUDIT
- Configure strong PASSWORD 
- Enable MFA for privileged users 
- use IAM ROLES for Amazon EC2 instance
- use IAM roles for SHARE Access
- ROTATE security credentials regularly
- restrict priviliged access furtehr with CONDITIONS
- reduce or remove use of ROOT 

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
- Trail created in North Viriginia will be globally.
































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

















