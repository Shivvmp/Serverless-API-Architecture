# Serverless-API-Architecture
#Project Description:

Developed a fully serverless API architecture on AWS, leveraging services like Lambda, API Gateway, Aurora Serverless, and S3. The architecture ensures high availability, security, and scalability, with Terraform automating the infrastructure deployment. The API is routed through API Gateway to Lambda functions deployed within a VPC, interacting with Aurora Serverless for database operations. S3 is used for storage, and Secrets Manager secures sensitive information. The setup includes robust monitoring with CloudWatch and DNS management via Route 53.

#Technologies:
AWS Lambda
API Gateway
Aurora Serverless
S3
Secrets Manager
Terraform
CloudWatch
Route 53
VPC Endpoints

#Flow:

API Gateway handles incoming requests and routes them to AWS Lambda.
Lambda functions execute API logic, with data stored in Aurora Serverless.
Secrets Manager secures credentials, and S3 stores binary data.
Terraform automates the infrastructure deployment, and CloudWatch monitors performance.
Route 53 manages DNS routing, ensuring smooth access to the API.
