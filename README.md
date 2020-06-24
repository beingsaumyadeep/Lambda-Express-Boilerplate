# AWS Lambda Express Boilerplate
Credits - Main Repo : [AWS Serverless Express](https://github.com/awslabs/aws-serverless-express)
[Original Documentation](https://github.com/awslabs/aws-serverless-express/tree/master/examples/basic-starter)

### Uses AWS Cloudfront for setting up AWS Lambda, AWS API GateWay and AWS S3 Bucket


## Setup Steps
Required AWS account & `AWS CLI` on the system.
1. Clone the Repo 
2. Run on any terminal to configure the Express Stack `npm run config -- --account-id="<accountId>" --stack-name="<cloudfrontstackName>" --bucket-name="<bucketName>" [--region="<region>" --function-name="<functionName>" ]`. 
3. Run `npm run setup` (Windows User: `npm run win-setup`) this installs the node dependencies, creates an S3 bucket (if it does not already exist), packages and deploys your serverless Express application to AWS Lambda, and creates an API Gateway proxy API.

## Node.js version

Node.js version 12.x
