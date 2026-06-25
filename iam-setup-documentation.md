# IAM Setup Documentation

## Prerequisites

- AWS Account
- IAM Permissions
- EC2 Instance
- S3 Bucket

## Step 1: Create IAM Role

- Open IAM Console.
- Create a new role.
- Select EC2 as the trusted entity.

## Step 2: Create IAM Policy

- Open IAM Policies.
- Create a custom JSON policy.
- Specify only the required permissions.

## Step 3: Attach Policy

Attach the custom policy to the IAM Role.

## Step 4: Attach Role to EC2

Assign the IAM Role to the EC2 instance.

## Step 5: Verify

Use AWS CLI from the EC2 instance to verify access.

Example:

aws s3 ls

## Challenges Faced

- Understanding IAM permission structure.
- Configuring trust relationships.
- Applying least privilege permissions.
- Testing policy permissions.

## Conclusion

The IAM Role and IAM Policy were successfully configured, allowing secure access from EC2 to AWS services while following AWS security best practices.
