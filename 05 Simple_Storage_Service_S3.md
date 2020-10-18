# 05 S3 
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

