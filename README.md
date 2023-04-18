# AWS-Mass-Emailer

Mass emailing using AWS services.

## Goal

The goal of this project is to develop a cost-effective emailing platform using AWS. 

## AWS Services Implemented:

1. AWS Lambda
      * Uploading and importing CSV files
2. AWS Simple Email Service
      * Sending emails
3. AWS Identity Access Management (IAM)
      * Managing permissions
4. AWS DynamoDB
      * Storing data
5. Security Information and Event Management (SIEM)
      * Monitoring and alerting
      * Allowing us to track the activity on resources and recieve alerts if any suspicious activity is detected
6. AWS EventBridge
      * Setting schedules on sending emails

## How we intend the project to work:

1. The user will upload a CSV file that will trigger an S3 event
2.The function in AWS Lambda will trigger another Lambda function for importing files onto the database and then sending emails to specific email addresses



