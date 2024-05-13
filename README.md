
# AWS EC2 & S3 CloudFormation Deployment Project

This project demonstrates how to deploy a security group, an EC2 instance, an Elastic Block Store (EBS) volume, and an S3 bucket using AWS CloudFormation. The aim is to provide a straightforward approach to setting up a basic cloud environment, making it ideal for educational purposes or as a template for more complex infrastructures. By utilizing CloudFormation, this project enables automatic provisioning and management of AWS resources, ensuring that they are consistently configured in a repeatable manner.

## Features
- Security Group: Sets up a basic security group for an EC2 instance with predefined rules.
- EC2 Instance: Deploys an Amazon EC2 instance using the latest Amazon Linux AMI.
- EBS Volume: Attaches an additional Elastic Block Store volume to the EC2 instance.
- S3 Bucket: Creates an S3 bucket for resource storage.
## Prerequisites
- An AWS account.
- Basic understanding of AWS services like EC2, S3, and CloudFormation.
## Implementation Steps
1. Navigate to the CloudFormation Console:

Log in to your AWS Management Console and open the CloudFormation service.

2. Create a New Stack:

Choose 'Create Stack' > 'With new resources (standard)'.

3. Upload the CloudFormation Template:

Select 'Template is ready' and 'Upload a template file'.
Click 'Choose file' and upload the provided CloudFormation template.

4. Specify Stack Details:

Provide a name for your stack in the 'Stack name' field.

5. Configure Stack Options (Optional):

You may specify tags and permissions as needed, though these steps are optional.

6. Set Rollback Configuration:

Choose “Roll back all stack resources” for the rollback behavior if stack creation fails.

7. Review and Create:

Review all settings to ensure they are correct.

Click 'Create stack' to deploy your resources.
## Screenshots

![App Screenshot](https://snipboard.io/RxJkLZ.jpg)
![App Screenshot](https://snipboard.io/rVamQL.jpg)
![App Screenshot](https://snipboard.io/25YxmR.jpg)

## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samuel-tettey-fio/)

## Authors

- [@bigsam233](https://github.com/bigsam233)

