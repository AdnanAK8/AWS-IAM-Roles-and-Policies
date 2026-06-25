# IAM Policy with Granular Permissions

## Objective

Provide only the required permissions following the Principle of Least Privilege.

## Policy Description

The policy grants read-only access to a specific S3 bucket.

## Allowed Actions

- s3:GetObject
- s3:ListBucket

## Restricted Actions

The following actions are not allowed:

- Delete Bucket
- Delete Object
- Create Bucket
- Modify Bucket Policy
- Put Object
- Full Administrative Access

## Policy Attachment

The custom IAM policy is attached to the EC2 IAM Role.

## Testing

1. Connect to EC2.
2. Execute:

aws s3 ls s3://example-bucket

3. Verify that bucket contents are listed.
4. Attempt restricted operations and verify that Access Denied is returned.

## Result

Only the required S3 permissions are granted successfully.
