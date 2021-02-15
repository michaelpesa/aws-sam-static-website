# SAM Static Website

This project contains an AWS Serverless Application Model (SAM) template that creates the resources for hosting a static website, including:
- A CloudFront distribution for the website
- An SSL certificate for the CloudFront distribution
- An S3 bucket for the static website content
- An S3 bucket for the CloudFront distribution logs
- A Lambda function for performing URL redirection
- DNS A and AAAA alias records
- Bucket policies and IAM roles required for the resources

This project also contains the code for the Lambda URL redirection function.
