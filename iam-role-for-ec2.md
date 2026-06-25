# IAM Role for EC2

## Role Name

EC2-S3-Access-Role

## Purpose

The IAM Role allows an EC2 instance to securely access AWS services without storing access keys.

## Trusted Entity

Amazon EC2

## Steps to Create the Role

1. Open AWS Management Console.
2. Navigate to IAM.
3. Select Roles.
4. Click Create Role.
5. Choose AWS Service.
6. Select EC2.
7. Click Next.
8. Attach the required IAM Policy.
9. Enter the role name.
10. Review and create the role.

## Attach Role to EC2

1. Open EC2 Dashboard.
2. Select the EC2 instance.
3. Choose Actions.
4. Select Security.
5. Modify IAM Role.
6. Select the created IAM Role.
7. Save changes.

## Verification

- Login to EC2.
- Run AWS CLI commands.
- Confirm access to the permitted AWS resources.
