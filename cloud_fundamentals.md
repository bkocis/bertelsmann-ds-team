
#### Notes from the Cloud fundamentals Lessons

# Cloud fundamentals

## What is cloud computing? 
- pay as you go
	- pay be time used 
- autoscaling
	- automatic scaling of resources 
- serverless 
	- only code is written by developer, someone else does setting of servers etc

## Types of cloud computing:

- Infrastructure-as-a-Service (IaaS) - The provider supplies virtual server instances, storage, and mechanisms for you to manage servers.(AWS, Digital Ocean) 

- Platform-as-a-Service (PaaS) - A platform of development tools hosted on a provider's infrastructure. ("GoDaddy", "Salesforce")

- Software-as-a-Service (SaaS) - A software application that runs over the Internet and is managed by the service provider.(gmail, office365)


## Cloud Deployment Models

- Public Cloud - A public cloud makes resources available over the Internet to the general public.

- Private Cloud - A private cloud is a proprietary network that supplies services to a limited number of people.

- Hybrid Cloud - A hybrid model contains a combination of both a public and a private cloud.

The hybrid model is a growing trend in the industry for those organizations that have been slow to adopt the cloud due to being in a heavily regulated industry. The hybrid model gives organizations the flexibility to slowly migrate to the cloud.


## __AWS__ - Global Infrastructure

- Region - A region is considered a geographic location or an area on a map.

- Availability Zone - An availability zone is an isolated location within a geographic region and is a physical data center within a specific region.

- Edge Location	- An edge location is as a mini-data center used solely to cache large data files closer to a user's location.

Additional Information
- There are more Availability Zones (AZs) than there are Regions.
- There should be at least two AZs per Region.
- Each region is located in a separate geographic area.
- AZs are distinct locations that are engineered to be isolated from failures.


## __AWS__ - Shared Responsibility Model

AWS is responsible for security OF the cloud, we are responsible for security IN the cloud.

AWS is responsible for:

- Securing edge locations
- Monitoring physical device security
- Providing physical access control to hardware/software
- Database patching
- Discarding physical storage devices

Developer is responsible for:

- Managing AWS Identity and Access Management (IAM)
- Encrypting data
- Preventing or detecting when an AWS account has been compromised
- Restricting access to AWS services to only those users who need it


## __AWS__ Compute services 

### EC2
[Elastic Cloud Compute](https://www.amazonaws.cn/en/ec2/)

### EBS - for EC2 instances [Volums]
Elastic Block Store (EBS) is a storage solution for EC2 instances and is a physical hard drive that is attached to the EC2 instance to increase storage. Persist data even after EC2 instance is removed. 
[Elastic Block Store](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html)
