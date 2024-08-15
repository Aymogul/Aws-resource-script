# AWS Resource Listing Automation Script
## Overview
This repository contains a script designed to automate the process of listing all resources within an AWS account. The script leverages AWS SDKs to query and aggregate information from various AWS services, providing a comprehensive overview of your AWS infrastructure. This is particularly useful for auditing, cost management, and ensuring compliance with best practices.

The focus of this project is to provide a solution for listing resources of a user 
on AWS in an automated way, and basically could be used to perform cron job as the case may suit the user and the need in the line of automation.

## Prerequisite 
- AWS account 
- IAM user with required permission
- shell script

## Features
- Multi-Region Support: The script can query resources across multiple AWS regions.
- Service Coverage: Lists resources from major AWS services such as EC2, S3, RDS, Lambda, and more.
- Output Formats: Results can be outputted in plain text or saved to a file for easy integration with other tools.
- Error Handling: Includes basic error handling to manage API rate limits and service-specific issues.
