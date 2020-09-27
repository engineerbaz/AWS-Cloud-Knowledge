# LAB Session

# LAB - Trusted Advisor
- Global
- If 50% information error then becomes critical 
- 

May b... Linux is comparatively more secure than windows

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


----
# LAB S3 
-----
1. Create S3 bucket with unique name.
2. Create & enable Versioning, encryption & tags.
3. Create 53 bucket policy & apply on bucket.
4  Deploy static website hosting & verify.
5. Create life cycle rule.
6. Change S3 storage types



ARN (Amazon Resource Nummber)
arn:aws:s3:::s3bazs3