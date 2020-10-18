# VPN  - Virtual Private Cloud

- Allow users to use AWS resources in a virtual network. 
- Can be customized their virtual networking environment ( Selecting own IP address range, creating subnets, and configuring route table and network gateway)
- 5 VPCs can be made per region
- Free service except for NAT GW
- Can connect the same / cross-region, cross-account 

## Features
- Store Data in S3 and set permission such that data only be accessed from VPC
- Attach one or more Elastic IP so can be reached from the internet
- Connect VPC with other VPCand access resources in other VPC via private IP Address using VPC peering
- Privately connect to AWS service without using internet GW, NAT or firewall proxy through a VPC endpoint
- Bridge VPC and onsite IT infra with an encrypted VPN connection 
- VPC Flow logs to log infor abt network traffic going in and out network interface **

## Key Concept
- VPCs and Subnets
- A subnet is a range of IP address in VPC
- Using a public subnet for resources that must be connected to the internet, and a private and won’t connect to the internet 
- While creating VPC, must specify a range of IPv4 for VPC in form of CIDR
- CIDR of /16 
- Subnet should be of /24
- No less than /28 subnet allowed

## AMAZON VPC

- Single AWS, 
- Three 3 Zone 
- Three Route Table (can be a single RT for all zone) 
- 1 VPC 
- 1 Router 
- One Subnet comprise in one subnet only, cant overlap 
- Currently, IPv6 is not supported in VPN

## VPN & SUBNET Sizing

- 5 IPs are reserved 
- 10.0.0.0 Network Address 
- 10.0.0.1 
- 10.0.0.2 
- 10.0.0.3 
- 10.0.0.4 
- 10.0.0.5

## VPC Security
- Security Group 
- Stateful Firewall 
- Work on VM level 
- Implicit deny 
- Allow rule only.
- On VPC level 
- Evaluate all rules before deciding whether to all allow traffic 
  
## NACL
- Network Access Control List 
- Stateless 
- Different rule for ingress and egress 
- On Whole Network 

## Flow Logs
- Packet capture & log
- Accessing a Corporate or Home Network 
- Connect VPC to corp data centr by IPSec

## VPC Endpoints
- VPC EP enables you to privately connect your VPC to supported AWS  
- Interface EP 
  - An elastic network with a private IP address from the IP 
- GW EP 
  - Where non-IP based system like S3, Dynamo DB
- Integrated with Other AWS Service 

Dashboard
Component by 
CLI
JSON 
----------------

# AWS Deployment Scenarios


1.  Create VPC with CIDR Block 
Vpc-0407780104d87ad99
172.16.0.0/16 = CIDR Block

2. Create VPC Gateway & Attached
Internet gateway 
ID igw-0862945af0f49ee34

3. Create 4 subnets (2 For Public & 2 for Private )
Zone 1
Public Subnet 1  = 172.16.0.0/24
Subnet ID subnet-0eea2c78ed4f835bf
Private Subnet 1 = 172.16.1.0/24
Subnet ID subnet-04195baa6a17df6d1
Zone 2 
Public Subnet 2  =  172.16.2.0/24
Subnet ID subnet-0c664ffeb9092bb68
Private Subnet 2 = 172.16.3.0/24
Subnet ID subnet-02c3b0d82563b9f97

4. Create Route table (Main route table already exist)
Publie Route Table 
Route Table ID 
Rtb-05b38332fec44a01b
Private Route Table
Automatically created

5. Add public & private subnets in the appropriate route tables
Added 2 public subnets in Private RT
Added 2 private subnet in Public RT

6. add IGW to public route table
Added route 0.0.0.0.0/0 for IGW

7. Create EIP
Created

8. Create NAT Gateway on public Subnet
NAT GW makes in public subnet but attached with the private subnet
NAT Gateway ID 
nat-0149b8e4d30541da2


9. Add NatGW route on main route table (Private ROute table)
Added route of 0.0.0.0/0 

10. verify

