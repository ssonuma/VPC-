# Ex 4 Deployment and configuration of a Private Cloud in AWS

## NAME: SONU S
## REG NO: 212223220107

### Aim:
To set up of a Private Cloud in AWS.

### Setting up of a private cloud in AWS:

Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC), involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment, including resource placement, connectivity, and security. Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.

## Procedure:
Plan Your VPC:
● Determine your needs:

Define your use case, including application requirements, security needs, and compliance standards.
● Plan IP address ranges:

Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
● Select Availability Zones:

Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance.
● Plan internet connectivity:

Determine if you need public internet access and how to configure it.
● Define security:

Plan your security groups, network ACLs, and access controls to ensure a secure environment.
Create Your VPC:
• Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.

• Choose "Create VPC": Initiate the VPC creation process.

• Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.

• Create subnets: Define subnets within your VPC to isolate different parts of your network.

• Create route tables: Specify how traffic is routed within and outside the VPC.

• Create security groups: Define access control rules for your resources.

Deploying Resources:
• Launch EC2 instances: Create and launch virtual machines within your VPC.

• Set up RDS instances: Deploy databases for your applications.

• Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables.

• Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

Managing and Monitoring:
• Use AWS CloudWatch: Monitor your VPC and resources for performance and health.

• Configure logging and auditing: Track access and activity within your VPC for security and compliance.

• Implement security best practices: Regularly review and update your security configuration.

• Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.

## Output:

Snapshot 1: Create VPC image

![image](https://github.com/user-attachments/assets/f6728758-8d97-4270-b3ef-50da38761185)


Snapshot 2: Configuring Subnets

![image](https://github.com/user-attachments/assets/fdde8648-30e9-4b29-a785-5154a2d8a646)


Snapshot 3: Configure Subnets

![image](https://github.com/user-attachments/assets/73ad5f55-16cc-481e-ae4f-0397c3020716)


Snapshot 4: Setting Internet gateway

![image](https://github.com/user-attachments/assets/ab0ef2ca-c0dd-432d-a597-a15d297201da)


Snapshot 5: Creating Internet gateway

![image](https://github.com/user-attachments/assets/1a39b181-72e5-470f-836c-d88e035f561c)


Snapshot 6: Setting Internet gateway

![image](https://github.com/user-attachments/assets/1ab32b45-6a08-40c1-9dcd-67c23329c7e5)


Snapshot 7: Creating route table

![image](https://github.com/user-attachments/assets/e1132fac-2f4e-4139-b902-d4e58fcc75e8)


Snapshot 8: Configuring route table

![image](https://github.com/user-attachments/assets/ae4d9f4e-2cff-4c3b-83c6-ffacdcb7de09)



Snapshot 9: Editing routes

![image](https://github.com/user-attachments/assets/39d1706d-aaca-4444-9be2-37fc04a18375)




Snapshot 10: Creating route table

![image](https://github.com/user-attachments/assets/7a6efa1a-fabc-4231-88e5-db544de73617)




Result:
Thus, a private cloud on AWS involves using VPCs has been created for a dedicated, isolated network where we can manage our resources and control access according to our requirements.
