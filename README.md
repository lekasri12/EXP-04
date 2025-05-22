# EXP-04 Deployment and configuration of a Private Cloud  in AWS
### NAME : G LEKASRI
### REGISTER NUMBER : 212223100025
# Aim:
To set up of a Private Cloud  in AWS.
         Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.
# Procedure:
1. Plan Your VPC:
● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.

● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.

● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
● Plan internet connectivity:
Determine if you need public internet access and how to configure it.

● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.

3. Create Your VPC:
•	Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.

•	 Choose "Create VPC": Initiate the VPC creation process.

•	Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
•	other necessary settings.

•	Create subnets: Define subnets within your VPC to isolate different parts of your
	network.
 
•	Create route tables: Specify how traffic is routed within and outside the VPC.

•	 Create security groups: Define access control rules for your resources.

5. Deploying Resources:
•	Launch EC2 instances: Create and launch virtual machines within your VPC.

•	 Set up RDS instances: Deploy databases for your applications.

•	Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.

•	Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

4.Managing and Monitoring:
•	Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.

•	Configure logging and auditing: Track access and activity within your VPC for
security and compliance.

•	Implement security best practices: Regularly review and update your security
configuration.

•	Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.


Snap Shot:
![image](https://github.com/user-attachments/assets/013bb3ef-f76e-46a3-b7d1-e0baca0ea3fe)

 

 1: Create VPC
 ![image](https://github.com/user-attachments/assets/e0a4bda9-a138-4135-901d-6fc3cf10ab51)

 
 2: Configuring Subnets
 ![image](https://github.com/user-attachments/assets/d01d7bf6-0a87-4ccf-8ea8-d866edd9aca2)


 3: Configure Subnets
 ![image](https://github.com/user-attachments/assets/8b011f51-9394-4987-b20c-7647b43f67ca)


 4: Setting Internet gateway
![image](https://github.com/user-attachments/assets/1bdc5fe4-c862-4da4-8055-467cc3ec8592)

 
 5: Setting Internet gateway
![image](https://github.com/user-attachments/assets/36e261e9-02bd-4138-ba67-a550053e98ce)

 6: Setting Internet gateway
![image](https://github.com/user-attachments/assets/ce784708-92d2-4075-9bc9-2c94df71fb24)

 
 7: Creating route table
![image](https://github.com/user-attachments/assets/ad2d9ba1-32f4-4e4e-a298-4d123099ea2a)

 
 8: Configuring route table
![image](https://github.com/user-attachments/assets/ed78e0b6-f713-4159-ac47-adc12a33f51d)

 
 9: Editing routes
![image](https://github.com/user-attachments/assets/bbf7def9-db5d-44f1-a08b-5b73acd68f06)

 10: Creating route table





# Result:
Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.
