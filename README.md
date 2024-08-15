# AWS Resource Listing Automation Script
## Overview
This repository contains a script designed to automate the process of listing all resources within an AWS account. The script leverages AWS SDKs to query and aggregate information from various AWS services, providing a comprehensive overview of your AWS infrastructure. This is particularly useful for auditing, cost management, and ensuring compliance with best practices.

The focus of this project is to provide a solution for listing resources of a user 
on AWS in an automated way, and basically could be used to perform cron job as the case may suit the user and the need in the line of automation.


## Features
- Multi-Region Support: The script can query resources across multiple AWS regions.
- Service Coverage: Lists resources from major AWS services such as EC2, S3, RDS, Lambda, and more.
- Output Formats: Results can be outputted in plain text or saved to a file for easy integration with other tools.
- Error Handling: Includes basic error handling to manage API rate limits and service-specific issues.


## Prerequisites
Before running the script, ensure you have the following:

AWS CLI: Installed and configured with the necessary permissions to query AWS resources.

Bash Shell: The script is written for Unix-like environments (Linux, macOS, WSL on Windows).

IAM Permissions: The IAM user or role running the script should have read-only permissions to all AWS services being queried.

## Setup

### STEPS
1. clone the Repository:
```sh
https://github.com/Aymogul/Aws-resource-script.git
```

2. Configure AWS CLI:
Ensure your AWS CLI is configured with the necessary credentials and default region
```sh
aws configure
```

3. Make script Executable:
Give execution permission to the script
```sh
chmod +x aws_resource_list.sh
```

### Usage 
1. Run the script
This can be executed directly from the command line after
