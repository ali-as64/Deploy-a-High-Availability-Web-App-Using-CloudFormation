# Deploy-a-High-Availability-Web-App-Using-CloudFormation
# Project 2 - Deploy a High-Availability Web App using CloudFormation
Nokia & BIT Scholarship at Udacity
This template deploys Infrastructure for web servers for a highly available web app 
using CloudFormationa ie. VPC, with a pair of public and private subnets spread 
across two Availabilty Zones. It deploys an Internet Gateway, with a default 
route on the public subnets. It deploys a pair of NAT Gateways (one in each AZ), 
and default routes for them in the private subnets.


## The files included are: 

1. WebAppUdagram.jpeg : project architecture diagram
2. image of result-screenshot for project deployed.
3. simple dummy website to see functioning of the project 
4. create.sh : Cloudformation create stack script. 
5. update.sh : Cloudformation update stack script.
6. destroy.sh : Cloudformation delete stack script.
7. infra_network.yml : Udagram Project's CloudFormation script.
8. infra-network-param.json : Udagram Project's CloudFormation script parameters
9. server.yml : Udagram Project's CloudFormation script
10. server-param.json : Udagram Project's CloudFormation script parameters.

