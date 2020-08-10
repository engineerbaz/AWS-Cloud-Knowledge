# AWS Global Infrastrucure
AWS is universal public cloud provider 
1. Region
2. Availability Zones
3. Edge location
4. Regional Edge

Some Key points 

- 76 AZs 
- 24 Regions 
- 3 more Regions/AZs planned
- 1 Local Zone (For ultralow latency applications)
- 2 Wavelength Zones (For ultralow latency applications)
- 97 Direct connect locations
- 216 Point of Presence (205 Edge & 11 Regional edge)
  
[AWS Infrastrucure](https://infrastructure.aws/)

## Regions
- Provides multiple isloated & Physically seprated has connected with low latency , high throughput & HA networking
- Atleast 2 or more DC/AZs in a Region 

## AZ
Its actual Data Center providing compute, storage, network in different location in same Region

## Edge locations
- Located in major cites / populated areas.
- They are not for deployig services like EC2, EBS, VPC, RDS
- Services like CloudFront & Lambda@Edge to cache data & reduce latency

## Regional Edge cache
Between CloudFront orgin server & Edge location. :)

![Pictorial Infrastrucure](https://bbdf1ad353dd66321bf2-f07dfa5af631485dafad600ccf8838a8.ssl.cf2.rackcdn.com/wp-content/uploads/2017/02/AZ2.png)