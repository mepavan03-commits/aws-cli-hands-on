# AWS CLI – Hands-on Practice

This repository documents my hands-on learning and practical work with the AWS Command Line Interface (AWS CLI).

## What I Learned

- AWS CLI basics
- AWS CLI installation and version verification
- AWS CLI configuration
- IAM Role based authentication
- EC2 CLI commands
- S3 CLI commands
- IAM Users and Roles
- CloudWatch CLI commands
- AWS CLI filters
- AWS CLI `--query`
- Basic JMESPath queries
- Output formats: `table`, `text`, and `json`
- Basic AWS CLI troubleshooting

## Hands-on Practice

### EC2
- List running EC2 instances
- Retrieve Instance ID, Instance Type and IP address
- Filter instances by running state
- Use `--query` to display required information

### S3
- List S3 buckets and objects
- Check objects inside a specific S3 bucket
- Copy objects from S3
- Sync S3 objects to a local directory
- Display object sizes in human-readable format

### IAM
- List IAM users
- Retrieve Username, ARN and CreateDate
- List IAM roles
- Filter IAM roles using JMESPath
- Retrieve RoleName and ARN

### CloudWatch
- List CloudWatch metrics
- Filter metrics by namespace
- Filter metrics by EC2 Instance ID
- Find CPU, Network and Status Check related metrics
- Use JMESPath conditions with `contains()`

## Important AWS CLI Options

| Option | Purpose |
|---|---|
| `--region` | Specify AWS Region |
| `--output` | Control command output format |
| `--query` | Select required data from the response |
| `--filters` | Filter resources using AWS API filters |

