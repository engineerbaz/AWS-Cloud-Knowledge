# AWS Regions & Avalailblity Zones
AWS is universal public cloud provider 

## Regions
- Provides multiple isloated & Physically seprated has connected with low latency , high throughput & HA networking
- Atleast 2 or more DC in a Region


## AZ
Its actual Data Center providing compute, storage, network in different location in same Region


# AWS Global Infra
- 76 AZs 
- 24 Regions 
- 3 more Regions/AZs planned
- 1 local zone for ultra low latency
- 97 Direct connect locations
- 216 Point of Presence (205 Edge & 11 Regional edge)

## Edge locations
- Located in major cites / populated areas.
- They are not for deployig services like EC2, EBS, VPC, RDS
- Services like CloudFront & Lambda@Edge to cache data & reduce latency

## Regional Edge cache
Between CloudFront orgin server & Edge location. :)
