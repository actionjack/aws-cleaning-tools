# AWS-cleaning-tools

### Requirement
-Python
-Boto3

`~/.aws/credentials` file with the following content:
`[default]
aws_access_key_id = YOUR_ACCESS_KEY
aws_secret_access_key = YOUR_SECRET_KEY`

We just need a read access.

### Tools
aws-ami.py:
-Support both EC2, CloudFormation and Lauch config AMI. It list all the unused AMI's
