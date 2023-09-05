# AWS
Secure VPC Setup with EC2 Instances
Project:

I've used the following approach for a secure VPC network. I used load balancing and auto-scaling for efficiency.

Design and configure a VPC: Create a VPC with custom IP ranges. Set up public and private subnets. Configure route tables and associate subnets.

Implement network security: Set up network access control lists (ACLs) to control inbound and outbound traffic. Configure security groups for EC2 instances to allow specific ports and protocols.

Provision EC2 instances: Launch EC2 instances in both the public and private subnets. Configure security groups for the instances to allow necessary traffic. Create and assign IAM roles to the instances with appropriate permissions.

Networking and routing: Set up an internet gateway to allow internet access for instances in the public subnet. Configure NAT gateway or NAT instance to enable outbound internet access for instances in the private subnet. Create appropriate route tables and associate them with the subnets.

SSH key pair and access control: Generate an SSH key pair and securely store the private key. Configure the instances to allow SSH access only with the generated key pair. Implement IAM policies and roles to control access and permissions to AWS resources.

Test and validate the setup: SSH into the EC2 instances using the private key and verify connectivity. Test network connectivity between instances in different subnets. Validate security group rules and network ACL settings.

![image](https://github.com/MirzaSameer/AWS/assets/97332699/10c77609-e844-4ecb-ab3d-c44533982561)

![image](https://github.com/MirzaSameer/AWS/assets/97332699/d9298941-9f61-428d-93b9-c834bfd196b8)

![image](https://github.com/MirzaSameer/AWS/assets/97332699/788541be-b09a-4fd1-8ba8-b8ec780d6c54)

![image](https://github.com/MirzaSameer/AWS/assets/97332699/f275d7da-a3e7-4cdf-949d-5f1c3df0f01d)

![image](https://github.com/MirzaSameer/AWS/assets/97332699/51902047-a7bc-4546-866a-ec71cf5417e3)

![image](https://github.com/MirzaSameer/AWS/assets/97332699/f1381319-36a7-468c-83c6-e074c989baa9)

![image](https://github.com/MirzaSameer/AWS/assets/97332699/7b83180c-208d-4049-a59e-cb78c06fc253)

![image](https://github.com/MirzaSameer/AWS/assets/97332699/a0c79b20-c3c6-4cc7-94d2-2c0d3821f3cf)

![image](https://github.com/MirzaSameer/AWS/assets/97332699/29a32e5b-668c-431e-8d52-7ddffb5b0839)
