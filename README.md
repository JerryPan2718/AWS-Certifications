# AWS-Certifications
Course Linked: udemy.com/course/aws-lambda-serverless/


## Why AWS Lambda
### Amazon EC2:
- Virtual Servers in the Cloud
- Limited by RAM and CPU
- Continuously running
- Scaling means intervention to add/remove servers

### Amazon Lambda 
- Virtual functions - no servers to manage
- Limited by time - short executions
- Run on-demand
- Scaling is automated

### Benefits of AWS Lambda
- Easy Pricing
  - Pay per request and computing
- Integrated with the whole AWS Stack
- Easy monitoring through AWS CloudWatch
- Increasing RAM will also improve CPU

### AWS Lambda Languages
- aws-nodejs
- aws-python
- aws-java-gradle
- aws-scala-sbt
- aws-csharp

### AWS Lambda Integrations
- API Gateway: provide RESTful API
- Kinesis: real-time streaming data
- DynamoDB: noSQL database
- AWS S3: Simple Storage Service
- AWS IoT Internet of Things
- CloudWatch Events
- AWS SNS: Simple Notification Service

e.g. Thumbnail creation
1. New image in S3 
2. AWS Lambda function creates a thumbnail
3. New thumbnail in S3
4. Metadata in DynamoDB

## The Serverless Framework
- Serverless Framework aims to ease the pain of creating, deploying, managing, and debugging lambda functions.\
- It integrates well with CI/CD tools
- It has CloudFormation support so your entire stack can be deployed using this Framework
- 

