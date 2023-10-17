# 3-tiercode
Resources created as part of the 3-tier and also presentation and application layer images are created under ECR 
1 VPC
2 Public subnets
2 Private subnets
2 Autoscaling groups
5 Security Groups
2 Load Balancers, (one private, one public)
2 Private EC2 instances (representing our application tier)
2 Public EC2 instances (representing our presentation tier)
2 Nat Gateways (so private instances can connect to the internet)
2 Elastic IP addresses, one for each Nat gateway
1rds instance
