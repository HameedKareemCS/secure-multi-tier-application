
## Secure Multi-Tier Web Application

### Overview
This project focuses on the design and implementation of a production-grade, multi-tier web application within the AWS cloud environment. 
As organizations move toward SaaS-based product delivery, the ability to secure data at every layer, from the network perimeter down to the database level, is a critical skill. 
This project serves as a practical demonstration of deploying a secure, resilient infrastructure that protects sensitive customer data against common threats.

##### The Challenge
Modern web applications are often targets for unauthorized access and data breaches. When deploying applications to the cloud, "default" configurations are rarely sufficient. This project addresses the challenge of moving beyond basic cloud setups by implementing strict network segmentation, layered security controls, and encryption at every boundary. The goal is to simulate the security responsibilities typical of a day-one cloud engineer at a company managing a customer-facing SaaS platform.


##### Learning Objectives
The primary objective of this project is to gain hands-on experience with foundational AWS security services. Key technical outcomes include:

**Network Segmentation**: Mastering the use of VPCs, public subnets, and private subnets to isolate application components.

 - **Identity and Access Management (IAM)**: Applying the principle of "Least Privilege" to ensure that services, instances, and users only
   have access to the resources they strictly need.
   
   **Data Protection**: Implementing KMS-managed encryption for data at rest, specifically for RDS (databases) and S3 (storage).
   
   **Threat Mitigation**: Deploying Web Application Firewalls (WAF) to filter malicious traffic and utilizing AWS native tools (CloudTrail,
   VPC Flow Logs) for continuous infrastructure auditing and
   observability.


## Architecture Design
- I will be updating this README as I work towards achieving this.

## Project Log
- **Phase 1: Foundation** - [Date]: Initial setup of VPC and security groups.
- **Phase 2: Compute** - [Date]: Launching EC2 instances.
- **Phase 3: Data** - [Date]: Configuring RDS with encryption.

## Key Learnings
- [List specific security configurations you implemented.]
