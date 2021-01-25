# Design a Compute Strategy

##IaaS
VMs

##PaaS
Azure App Services
Azure Functions
Logic Apps
Service Fabric -> AKS
ACI
Azure Batch -> Large Scale, High Performance, Parallel

## Azure Regions

**Cloud server could go down from time to time, availability must be considered while designing**

* Paired Regions for backup and DR
* Region -> {2/3 Data centers}
* Data centers are auto assigned but can be indicated by setting Availability Zones
* Availability zones for HA
* VMSS vs VMs in Same Availability Set with load balancer

## App Service
* PaaS
* Built-in load balancer
* Integrated with CI/CD
* App Service Plan 

## Service Fabric
* Microservices
* Not cross-platform

## Functions and Logic Apps

## Containers
* AKS vs App Service Containers vs ACI 
* ACI is for testing 

## Managing Costs
* Hybrid Benefit
* Reserve VM Instances
* AutoScaling
* Migrate to serverless and microservices
* Dev Test Labs
* Use dev license
* Auto shutdown
* Azure Pricing Calculator



