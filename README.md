# VertexMind-AWS-Cloud-Securitys
AWS Cloud Security Internship Project – VPC configuration, Security Groups, IAM roles, S3 encryption and CloudTrail monitoring.

# AWS Cloud Security Implementation

## Internship Project
**Organization:** VertexMind  
**Domain:** Cloud Computing  
**Project:** AWS Cloud Security Mission

## 1. Project Overview
This project demonstrates the implementation of cloud security using Amazon Web Services (AWS). It focuses on securing cloud infrastructure through network configuration, identity and access management, storage encryption and activity monitoring.

## 2. Objectives
- Create and configure an AWS Virtual Private Cloud (VPC).
- Configure public and private subnets.
- Implement secure Security Group rules.
- Create IAM roles and attach appropriate permissions.
- Configure S3 bucket security and encryption.
- Enable AWS CloudTrail for activity monitoring.

## 3. Technologies Used
- Amazon Web Services (AWS)
- Amazon VPC
- Amazon EC2 Security Groups
- AWS IAM
- Amazon S3
- AWS CloudTrail

## 4. Implementation

### VPC Configuration
Created a Virtual Private Cloud to provide an isolated network environment.

### Security Group
Configured inbound network rules:
- SSH – Port 22 (restricted to My IP)
- HTTP – Port 80
- HTTPS – Port 443

### IAM Configuration
Created an IAM role:
- Role Name: VertexMind-EC2-Role
- Trusted Entity: EC2
- Policy: AmazonEC2ReadOnlyAccess

### S3 Storage Security
Created an S3 bucket:
- Bucket Name: vertexmind-security-storage-anusiya
- Public access: Blocked
- Default encryption: SSE-S3 (verify in AWS console)

### CloudTrail Monitoring
Created a multi-region CloudTrail:
- Trail Name: VertexMind-Security-Trail-01
- Region: Asia Pacific (Sydney)
- Management event logging: To be verified
- Logging status: To be verified

## 5. Security Best Practices
- Follow the principle of least privilege.
- Restrict SSH access.
- Block public access to S3.
- Enable encryption for stored data.
- Monitor AWS account activity using CloudTrail.
- Protect account credentials.

## 6. Screenshots
Screenshots of the AWS configurations are available in the Screenshots folder.

## 7. Conclusion
This project provided practical experience in configuring AWS cloud security services, managing access permissions, protecting cloud storage and monitoring cloud infrastructure.

**Created as part of the VertexMind Cloud Computing Internship.**
