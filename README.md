# AWS SNS Lambda Notification

This AWS Lambda function is designed to be triggered by an event, specifically an S3 object creation event. Upon triggering, it sends a notification using AWS Simple Notification Service (SNS), providing information about the S3 object that triggered the Lambda function.

## Overview

The AWS Lambda function is created to respond to S3 events. When a new object is created in the specified S3 bucket, the Lambda function is triggered automatically. The Lambda function extracts relevant information about the S3 object and sends a notification via SNS.

## Prerequisites

Before deploying and using this Lambda function, make sure you have:

- An AWS account with appropriate permissions to create Lambda functions, S3 buckets, and SNS topics.
- AWS CLI installed and configured on your development machine.
