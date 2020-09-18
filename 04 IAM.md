## IAM - Identity Access Management

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


- Role > resource (service)
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