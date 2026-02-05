# aws-lambda-api-gateway
Serverless backend implementation using AWS Lambda, API Gateway, and IAM with test deployment and logging.
🚀 AWS Lambda Serverless Application
📌 Overview
This project demonstrates a serverless application built using AWS Lambda.
The Lambda function is triggered via API Gateway and processes HTTP requests without managing servers.
🎯 Features
Serverless compute using AWS Lambda
REST API using Amazon API Gateway
IAM role-based access
IAM role-based access
Logging and monitoring via CloudWatch
Lightweight and scalable architecture
🛠️ Technologies Used
AWS Lambda
Amazon API Gateway
IAM
CloudWatch
Python / Node.js
📁 Project Structure
aws-lambda-serverless-api/
├── lambda_function/
├── events/
├── policy/
└── README.md
⚙️ Prerequisites
AWS Account
AWS CLI configured
Basic knowledge of Lambda & API Gateway
🧪 Lambda Function Example
The function receives an HTTP request and returns a JSON response.
🚀 Deployment Steps (Manual)
Create Lambda function
Upload function code
Attach IAM role
Configure API Gateway trigger
Test endpoint
📊 Monitoring
Logs available in AWS CloudWatch
Metrics for invocation and execution time
📈 Future Enhancements
Add DynamoDB integration
CI/CD using GitHub Actions
Terraform or SAM deployment
👩‍💻 Author
Anjali Singh
📜 License
MIT License
implemented a serverless application using AWS Lambda integrated with API Gateway. The function handles HTTP requests, uses IAM for permissions, and logs execution details to CloudWatch.
• Built a serverless backend using AWS Lambda and API Gateway with IAM-based security and CloudWatch monitoring.
