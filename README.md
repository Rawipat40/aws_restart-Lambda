# Lambda Hands-On with Python: Count Words in File and Trigger AWS Lambda to Send Email Notification

This repository contains a simple example of using AWS Lambda to trigger a Python function that counts the occurrences of words in a file and sends a notification email with the results.

## Usage

1. **Upload Python Code to AWS Lambda:**

    Upload the `lambda_function.py` file to AWS Lambda using the AWS Management Console or AWS CLI.

2. **Set Up an S3 Bucket:**

    Create an S3 bucket where you will upload the file for word count analysis.

3. **Create an S3 Event Trigger for Lambda:**

    Configure the S3 bucket to trigger the Lambda function whenever a file is uploaded.

4. **Test the Setup:**

    Upload a text file containing words to the configured S3 bucket. Check your email for the word count notification.

## Lambda Function Details

The `lambda_function.py` file contains a Python function that performs the following steps:

1. Retrieves the uploaded file from the S3 bucket.
2. Reads the contents of the file and counts the occurrences of each word.
3. Constructs an email message with the word count results.
4. Sends the email notification using the Simple Email Service (SES).

## Example

![Lambda1](https://github.com/Rawipat40/aws_restart-Lambda/assets/141838218/0779459f-ea8f-4b6e-ab34-567d31b3a878)
![Lambda2](https://github.com/Rawipat40/aws_restart-Lambda/assets/141838218/ff13cb6e-d44a-4ceb-a780-c3f1c1a13d43)
![Lambda3](https://github.com/Rawipat40/aws_restart-Lambda/assets/141838218/30d7643c-bbaf-4862-9263-5087d5a49d51)
![Lambda4](https://github.com/Rawipat40/aws_restart-Lambda/assets/141838218/ed7a1ae9-d4bb-4579-87a1-f6afb051439f)
![Lambda5](https://github.com/Rawipat40/aws_restart-Lambda/assets/141838218/6e8cac8a-15eb-4308-9061-66089d3ad7ed)
![Lambda6](https://github.com/Rawipat40/aws_restart-Lambda/assets/141838218/558b678b-08ad-4ec9-b802-48b2d42e3051)
![Lambda7](https://github.com/Rawipat40/aws_restart-Lambda/assets/141838218/012e7355-209f-4b3d-962b-b02d3be4b16e)
![Lambda8](https://github.com/Rawipat40/aws_restart-Lambda/assets/141838218/e4354b56-6d80-4f26-9a8f-d11e27d11cc6)
![Lambda9](https://github.com/Rawipat40/aws_restart-Lambda/assets/141838218/64c636aa-0b5f-408b-a50c-86e63f660f20)
![Lambda10](https://github.com/Rawipat40/aws_restart-Lambda/assets/141838218/07da6689-cadf-4671-823f-3946c76d9fc5)

