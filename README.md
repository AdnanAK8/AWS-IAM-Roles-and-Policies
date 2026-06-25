# AWS IAM Roles and Policies

## Overview
This project demonstrates how to create IAM Roles and IAM Policies in AWS to securely grant permissions to EC2 instances. The project follows the Principle of Least Privilege by allowing only the necessary permissions required to access AWS resources.

## Objectives
- Create an IAM Role for an EC2 instance.
- Create an IAM Policy with granular permissions.
- Attach the policy to the IAM Role.
- Attach the IAM Role to an EC2 instance.
- Verify secure access to AWS resources.

## IAM Concepts

### IAM Role
An IAM Role is an AWS identity that provides temporary permissions to AWS services without using long-term credentials.

### IAM Policy
An IAM Policy is a JSON document that defines what actions are allowed or denied on AWS resources.

### Principle of Least Privilege
Grant only the permissions required to perform a specific task.

## Repository Structure

AWS-IAM-Roles-and-Policies/
- README.md
- iam-role-for-ec2.md
- iam-policy-granular-permissions.md
- iam-setup-documentation.md
- trust-policy.json
- s3-access-policy.json
- LICENSE

## Steps Performed

1. Created an IAM Role.
2. Selected EC2 as the trusted service.
3. Created a custom IAM Policy.
4. Attached the policy to the IAM Role.
5. Assigned the IAM Role to an EC2 instance.
6. Verified access to the allowed S3 bucket.

## Learning Outcomes

- Understanding IAM Roles
- Creating IAM Policies
- AWS Permission Management
- Principle of Least Privilege
- Secure EC2 Access
