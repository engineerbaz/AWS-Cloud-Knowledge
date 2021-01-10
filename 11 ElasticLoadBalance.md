# Elastic Load Balancing (ELB)
ELB distributes incoming applications or network traffic across multiple targets ie EC2, container & IP address in multiple AZ
ELB scales your load balancer as traffic to application changes over time and can scale to the vast majority of workload automatically. 

### Types of LB 
- Private LB
- Public LB 
 - When you to access web/app from outside 

User hits DNS
If traffic 

### Feature of ELB
- High Availability 
- Distributes traffic in multiple AZs
- It has a single IP 
- Health Check
- ELB can detect unhealthy targets, stop sending traffic to them, and then spread the LB across the remaining healthy target
- Security Feature 
- Provides integrated certificate management & SSL/TLS decryption, allowing you to flexibility to centrally manage the SSL setting of the LB and offload CPU intensive work from app
- Layer 4 & 7
- L4 is TCP/UDP, called NLB
- L7 is HTTP/HTTPS, called ALB or classical 
- Operational/ Monitoring 
- For Pricing 18 - 20$ per hour


### Type of Load Balancer 
- ALB
 - Works on HTTP / HTTPs 
 - For different Target groups 
 - User can configure listener rules to router requests 
 - ELB scales over time when app changes 
 - It has rule in Listener having target group 
- CLB
 - Works on HTTP / HTTPs 
 - Routing decision on at transport layer (TCP/SSL) 
 - Requires fixed relationship between the LB port and ther container instance port
- NLB
 - Works on UDP/TCP (L4 Transport)
 - NLB is designed to handle traffic as it grows 

#### Accessing ELB
- Console 
- CLI
- SDK 
- Query API

#### ELB related Service 
- EC2
- ECS
- CloudWatch
- VPC
- Route53


### Infrastructure - Elastic & Scalability Deployment Scenario



