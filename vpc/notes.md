# AWS VPC Notes (Beginner Level)-> Sakshyam koirala

## What I Learned About VPC

Amazon VPC (Virtual Private Cloud) is a service in AWS that allows you to create your own private network in the cloud. It gives you full control over your networking environment.

## Why VPC is Important

- It helps isolate your AWS resources
- You can control inbound and outbound traffic
- It improves security of your cloud infrastructure
- It allows you to design custom networks like in real companies

## Key Components of VPC

### 1. Subnets
- A subnet is a smaller part of a VPC
- There are two types:
  - Public Subnet → Can access the internet
  - Private Subnet → No direct internet access

### 2. Internet Gateway (IGW)
- Connects VPC to the internet
- Required for public subnet access

### 3. Route Table
- Defines how traffic is directed inside VPC
- Helps decide where network traffic goes

---

### 4. Security Group
- Acts like a virtual firewall
- Controls traffic at instance level

### 5. Network ACL (NACL)
- Additional layer of security at subnet level

## What I Practiced

- Created a custom VPC
- Created public and private subnets
- Attached Internet Gateway
- Configured route tables
- Understood EC2 placement inside VPC

## Key Learnings

- VPC is the foundation of AWS networking
- Public subnet is for internet-facing resources
- Private subnet is for internal resources
- Security groups are essential for protection
- Proper routing is required for communication

## Final Understanding

VPC is like building your own private city in AWS where you control roads (routes), security (firewalls), and buildings (instances).
