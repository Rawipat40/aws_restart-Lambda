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
