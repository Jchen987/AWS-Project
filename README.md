# AWS-Project: EC2 CloudFormation Deployment

This project contains a **CloudFormation template** used to automate the creation and deletion of an EC2 instance within AWS.

## Description
The primary goal of this template is to provision an EC2 instance that is pre-configured with **Session Manager access**, allowing for secure management without needing SSH keys.

## Features
* **Automated Provisioning**: Quickly spin up resources using `ec2instance_template.yaml`.
* **Security**: Uses IAM roles for Session Manager access.
* **Cleanup**: Easy deletion of all resources by deleting the CloudFormation stack.

## Getting Started

### Prerequisites
* An active **AWS Account**.
* IAM permissions to create EC2 instances and CloudFormation stacks.

### Deployment Steps
1. Log into your [AWS Console](https://console.aws.amazon.com/).
2. Navigate to **CloudFormation**.
3. Upload the `ec2instance_template.yaml` file.
4. Follow the prompts to create the stack.

## Files in this Repository
* `README.md`: Project documentation.
* `ec2instance_template.yaml`: The main CloudFormation template.
